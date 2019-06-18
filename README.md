# Friend Finder Application 

## You Got A Friend In Me

## Description

*Friend Finder* implements friend matching based on the user's responses to a twelve question survey. The user responds to questions with values from 1 (Strongly Disagree) to 5 (Strongly Agree). When the survey is submitted, an existing user record closest to the current user's responses is found and returned. The closest set of user responses is defined as the set with the lowest absolute difference for all twelve questions combined.

*Friend Finder* application is meant to simulate a simple dating app. The application is implemented using a [Node.js](https://nodejs.org/en/) and [Express](https://expressjs.com/) server on the back end and the [Bootstrap](https://getbootstrap.com/) CSS framework on the front end.


### Use the App:
This application is hosted on Heroku: [Click Me!](https://you-got-a-friend-in-me.herokuapp.com/)
Answer the 12-question survey and be matched to a friend based on your answers!

![](./app/public/images/gif.gif)

## Installation:

To install the application follow the instructions below:

	git clone https://github.com/EBayler/FriendFinder.git
	cd FriendFinder
	npm install
	
## Running Locally:

To run the application locally and access it in your browser, first set the `PORT` environment variable to the value to:

	export PORT=3000
	
After the `PORT` environment variable has been set, run the Node.js application with the command below.

	node server.js
	
The application will now be running locally on `PORT`, port 3000. You can then access it locally from your browser at the URL `localhost:3000`.

________________________________

## Technologies Utilized:
HTML | CSS | JavaScript | jQuery | AJAX | Bootstrap | Heroku | Google Fonts

## Dependencies:
express | mysql | body-parser | fs

