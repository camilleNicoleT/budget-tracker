# Budget Tracker
Heroku Deployment: https://limitless-castle-37461.herokuapp.com/

Github Repo: 

AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 

GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

IMPORTANT

The budget tracker has the following functionality:

The ability to enter deposits offline.

The ability to enter expenses offline.

Offline entries should be added to the tracker when the application is brought back online.

Web Manifest
Because this is a mobile-first application, there is a web manifest with the app’s metadata, to let users’ devices know what they’re installing and how the app should look on the home screen.


Deployed to Heroku Using MongoDB Atlas
Finally, the budget tracker has a server and uses MongoDB as its database, so you’ll need to deploy this application to Heroku using MongoDB Atlas. To review this process, look at Module 18: NoSQL, Lesson 5: Add Mongoose Validation, specifically 18.5.5: Deploy to Heroku.

