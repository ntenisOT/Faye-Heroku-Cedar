Running Faye Server on Heroku Cedar stack
=========================================

Clone repository
----------------

Browse to your desirable application directory:
	
	cd to_directory

eg:
	
	cd my_faye_server
	
Clone from GitHub:
	
	git clone git://github.com/ntenisOT/Faye-Heroku-Cedar.git
	
Initializing git and first commit
---------------------------------

Initialize git:
	
	git init
	
Add files:
	
	git add .
	
First Commit:
	
	git commit -m "First Commit"
	
Creating a new app on Heroku
----------------------------

Install Heroku gem if you do not have already installed it:
	
	gem install heroku

Creating a new app running on Cedar stack:
	
	heroku create app_name --stack cedar

	
Push code to Heroku
-------------------
	
Push files to Heroku:
	
	git push heroku master
	

Go to you provided by Heroku link and check that your server is up add running!

YOU WILL NEED TO INCLUDE TO YOUR APPLICATION THE FOLLOWING LINKS:
	
	http://appname.herokuapp.com/faye
	
	http://appname.herokuapp.com/faye.js
	
Read More - More Examples
-------------------------

Faye Example Application: No need to run it on Cedar! 

	http://fayeexample.heroku.com/ 
	
	Source code: 

	https://github.com/ntenisOT/Faye-Example-Application 

Faye Server on Heroku Cedar without RedisToGo: 
	
	http://fayeserverexample.herokuapp.com/ 
	
	Source code: 

	https://github.com/ntenisOT/Faye-Heroku-Cedar 

Faye Server on Heroku Cedar with RedisToGo: 

	http://fayeredis.herokuapp.com 

	Source code: 
	
	https://github.com/ntenisOT/Faye-Heroku-Cedar-RedisToGo

References
----------
* Faye - http://faye.jcoglan.com/
* Heroku - http://heroku.com

Special Thanks
--------------
* James Coglan - Faye Developer
