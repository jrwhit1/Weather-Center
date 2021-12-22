# Weather-Center
GUI display of Current weather conditions and forecast via OpenWeather.org
Shows current weather conditons at your location and the extended weather forecast below it. The extended forecast was based on the Darksky example in the PySimpleGui examples complete with LED clock but was converted to use the OpenWeather framework. The code has some documentation included.

 You will need a free OpenWeatherMap.org  OneCall API key which you can get at https://openweathermap.org/appid.
This script is set up to access your weather via your latitude and longitude which can be found by going to google.com/maps and enter you address. Then right-click on your marker on the map. The top line is what you need. The first entry is your Latitude, the second you Longitude. Enter these in the script.

Libraries needed:
* PySimpleGUI
*  datetime
* calendar
*  requests
*  os
*  json
![Weather.png](https://github.com/jrwhit1/Weather-Center/blob/main/Weather.PNG)
