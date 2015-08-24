#Ubiquitous Wind Tracking

##Author

Ioannis Petridis


##The Application

The application is developed in Android Studio environment and is currently available only to Android devices. This application measures the speed and the direction of the wind in the device's location. This data, along with other, are send directly to an online Database, for later use.

Overall, the data that is handled with this application, and are stored in the Database are the following:

1. Longitude 
2. Latitude 
3. Wind Velocity 
4. Wind Direction 
5. Altitude 
6. Geographical Accuracy of measurement 
7. Device Id (Unique to each android device)
8. Device Email
9. Timestamp 
10. First name (optional)
11. Surname (optional)
12. Comment (optional)


#Requirements

The application's functionality, relies greatly on an external sensor component and its API which is provided by http://Weatherflow.com. The API and its integration steps are provided in the following page : https://github.com/WeatherFlow/WindMeterSDK/tree/master/Android/Full%20Integration%20Example . In order to make use of this application you have to buy the specific sensor and have an active internet connection (either data or Wi-Fi) and an enabled GPS sensor.


##The application step-by-step

In the starting page of the application, the user is prompted to enable the Internet data / Wi-Fi and the GPS sensor. Afterwards, the user can click on the buttons "Info" and "About Us" in order to view information regarding this application. By choosing the "Measure Now" button, the user is prompted to connect the weatherflow sensor to his android device if he hasn't done so until now. After connecting it, the user must hold the device high so that the anemometer is rotating accordingly to the wind. Thus the application measures the wind for a few seconds. After this process is completed, the user is informed about the wind velocity that has been measured these past seconds, and is prompted to optionally fill in some data. By pressing the "Send Data" button, the data are checked and afterwards stored in my Database. Should some constraint checks fail, the data aren't stored in the Database and an error message is produced within the application. Thus the measurement is over and the application goes to its starting page.


##The Reasons

You might ask, why should someone use this application. The data that are gathered through the measurements can be processed later on and help environmental researches on wind. Crowd-sourcing the information on wind data, greatly increases the data gathering ratio, so the more data we have, the better conclusions we can draw on them.

##Disclaimer

The data that are handled with this application are shown above. Because some of them are considered private (i.e. location longitude and latitude, email, name, device id) by using this application you agree to us using this data. While we won't share this information with the public, we hold no responsibility over the use of it.

##Contact info:

For information regarding the application and the use of the data, don't hesitate to contact me on mrjohnpetridis@gmail.com, Subject: "Ubiquitous-Wind-Tracking info"