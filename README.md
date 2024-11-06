Description:
Welcome to your personal Weather Dashboard that will give you weather for your desired location. Once you search for a location, it will save your previous searches as easy to click buttons. Use these buttons to view the weather for the selected city. You will always be presented with the last city you typed in the search box when you revisit the page.

Used OpenWeather API to retrieve weather data for cities. Also Used localStorage to store any persistent data.

Table of Contents
Pseudocode

Tech-Features-Used

Questions

Demo

Pseudocode
search for a city to presented with current and future conditions for that city and that city is added to the search history
view current weather conditions for that city to presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index
view the UV index to presented with a color that indicates whether the conditions are favorable, moderate, or severe
view future weather conditions for that city to presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, and the humidity
click on a city in the search history to again presented with current and future conditions for that city
open the weather dashboard to presented with the last searched city forecast
Tech-Features-Used
Open weather current & 5 day forecast API's: https://openweathermap.org/api
JQuery: https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js
Bootstrap: https://getbootstrap.com/
Moment.js: https://momentjs.com/
Font Awesome: https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css
Current Location: https://freegeoip.app/json/
An event listener for the search buttons and save to local storage
Event listeners
Ajax
script.js
Index.html
Styles.css
This project features responsive design using a Bootstrap layout Has responsive layout for:
Small devices (landscape phones, 320px and up)

Large devices (desktops, 992px and up)

To Execute File: Open in browser

Code Validation:
These use W3C Code Validators for HTML and CSS
esprima Syntax Validator
