# Egardia-Mobile-Development-Assessment
An assessment task for a candidate for the position of mobile developer at Egardia.

# Introduction
David at Egardia is looking for a new car. He made a shortlist of the good options and exported it in JSON file. He will be very happy having an App, where he can scroll over the shortlist and check the details for each car.

# Goal
The goal of the assignment is to deliver source code for an application. The application contains a list of cars. Data is fetched dynamically from a web server.

# Requirements
Your task is to make a simple  App that contains:

Screen with list of cars, showing picture, make, model and price. Picture should be fetched from network using the image url for each car. The piture link can be broken, so the App must show a placeholder insted.
By clicking on the car, the detailed screen must be open, where you can see the bigger picture and more details about the car, such as kilometers and year.
Data
The json data must be fetched from URL every time the App starts, using this link: https://raw.githubusercontent.com/igoregardia/Autos-Android-Assessment/master/autos.json So if the changes happens in json file, the App will always provide the updated data. Keep in mind that in future the new fields can be added to json file, for example the description of car, so the App should ignore new fields instead of crashing with JsonParseException. Warning! Just copying the content and storing it in a local file is not enough.

# Requirements
You are free to use any methodologies, principles, etc.
The source code should be without any errors and needs to compile on Android Studio or Apple xCode without any further coding or configuration effort.
The definition of the user interface is up to the candidate. However, we would like to see Android specific best practices and common design;

# Examination
The solution's source code must be pushed on git repository, you can just fork this repository, push source code of project and make a pull request. You can as well use your own repository, for example Bitbucket and give an access to clone it.
In case of Android please push the compiled APK file as well, in order we can install in test it before watching the code.

Good luck with the assessment!

