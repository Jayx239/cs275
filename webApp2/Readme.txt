Lab 2
Jason Gallagher
JPG77@drexel.edu
URL: 

User instructions:
1. Open web page
2. Enter user API Key
3. Click "Get Weather" button
4. Enjoy reading the hourly forcast for the next 35 hours!

Technical Details:
The web page uses the wunderground api to work. First an ajax request is made using jquery to abtain the users local zip code.
After obtaining the zip code, another ajax request is made to get the weather data. All data is returned in Json format.
When the weather data is obtained, the Json response is parsed and displayed on the webpage.