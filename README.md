# Steps followed to achieve code challenge.
Step 1: Create Auth.Provider in salesforce and choose provider type as facebook.
Step 2: Enable "log-in-as-facebook" option on log in screen by going to my domain settings in salesforce.
Step 3: Update or customize the automatically created Registration Handler class to complete login process without any errors.
Step 4: Pass the facebook login information like firstname, lastname and email from registrationhandler class to webservice class to perform a callout.
Step 5: Webservicecallout class will perform the callout to third party system called heroku to store user information into the database.
