# whatsForDinner
Read Me:

Link: http://cs336finalsrecipe.us-east-1.elasticbeanstalk.com

Table Of Contents 

	Setting up Application Locally
	Core Functionality
	Key Features
	Future ambitions 


1. Setting up Application Locally

	-  Git clone repository: https://github.com/krajput96/336finalproj

	-  Create Virtual Environment: virtualenv my-app

	-  Source my-app/bin/activate

	-  Remove "host = '0.0.0.0'" from application.run()

	-  python application.py

2. Core Functionality
	
	This app provides an interface to quickly cross reference ingredients and
	their quantities available in your fridge, with a set of recipes to provide 
	which recipes can be made with ingredients on hand. 

	We take this one step further by also providing recipes which are missing 1,
 	2, 3 ingredients missing. 

	Users are allowed to subselect by cuisine choices, order by protein values,
	and caloric values. 

	We take this one more step further by providing each tuple in the table 
	with an in depth information page. This page contains information on serving
	size of recipe, time to make recipe, and recipe instructions. These specific 
	details will be filled in the future, currently we provide the ingredients,
	and quantities required. 

3. Key Features
	
	One key feature is, on the recipes description page, we not only give details
	on making the recipe, but also on where to buy the missing ingredients, and 
	especially on how to navigate to that particular store (using MapQuest API). 
	Currently we have provided the addresses of the target store, but can modulate	      
	starting location, and generate new instructions accordingly. 

	Another key feature we have is informative graphs on the recipes which are 
	currently used to display patterns and trends in data, but can be adapted to
	display cuisine frequency by location, or which ingredients are most popular
	(for stores to know what to stock). 

4. Future Ambitions

	We would like to integrate with a smart fridge to 1) dynamically update what
	is and isn't available in the fridge. 2) Send notifications to smart phone
	to notify low quantity of an ingredient if it is used often. 3) Integration 
	with Amazon Fresh to deliver missing ingredients for selected recipes. For 
	example if a user says they would like to cook a meal in 3 days, get missing
	ingredients shipped to them on time for that. 
