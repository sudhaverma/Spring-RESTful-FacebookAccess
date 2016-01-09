# Spring-RESTful-FacebookAccess
Recently, I implemented a Spring application that uses Twitter's APIs to allow you to post tweets on your timeline, find top 20 tweets, search by hashtag and so on. This got me excited and this application now will use Facebook's API to do more interesting things with the data that facebook shares. You can find the Spring twitter application [here](https://github.com/sudhaverma/Spring-RESTtful-Twitter-Application).

# Plan 

I have realized that if I write down the plan for the application before a line of code is written, it keeps me more focused. So here goes a tentative plan about the minimum number of features I want to add to this Spring facebook application: 

* Get a user's data (duh!)
* Show the user information in a better visualization. For e.g 
* Show all locations the user has lived in on a nice map. 
* Show the number of friends, and how that number has grown on a pretty graph. 
* Use a good graph library to draw more graphs! Visualize the data better! 
* Allow a user to post on his/her own timeline. 

# Fetch the data from Facebook App
* Firstly, we need to register third party application with the Facebook application and generate required cusotmer key and customer secret.
* Using this customer key and customer secret as application Id and application secret in application.properties file.
* After getting authorized by the user, fetch all the required data of the user from Facebook application and store it in any relational database(i.e, using MySQL for this application).
* Later retrieve the stored inforamtion from the database for the given user and based on the data, display information in a graphical manner.
* Various other basic features of  user's Facebook data can be cloned using this application.
* By making use of graph library displaying all the requested details to the end user.

#Running the application
* Application.java class present in the project makes the entire applicaiton executable.
