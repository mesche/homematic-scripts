Service - Weather Data - Wunderground
=====================================

### Description

Call the Wunderground API via HTTP request to get the current weather data of a certain place.
Store each value like temperature, weather condition, humidity, wind etc. into a system variable.


### Requirements

* CUx-Daemon (CuxD)
* Wunderground API key


### Configuration

CUXD_ID = "CUX2801001:1";              Serialnumber of the CUx-Daemon channel
API_KEY = "<PLEASE INSERT>";           Your Wunderground API key 
API_FEATURE = "conditions";            One or more data features can be combined into a single request
API_LANG = "DL";                       Default: EN - Returns the API response in the specified language
API_QUERY = "Germany/Berlin";          The location for which you want weather information


### Links
* [Aktuelle Wetterdaten über Wunderground Service abrufen und in der Homematic CCU speichern – Homematic-Script](http://www.blogging-it.com/aktuelle-wetterdaten-ueber-wunderground-service-abrufen-und-in-der-homematic-ccu-speichern/programmierung/homematic-script.html)
* [Wunderground Weather API](http://www.wunderground.com/weather/api/)
* [API-Doc - Language Support](http://www.wunderground.com/weather/api/d/docs?d=language-support)



### License
The license is committed to the repository in the project folder as `LICENSE.txt`.
Please see the `LICENSE.txt` file for full informations.


----------------------------------

Markus Eschenbach  
http://www.blogging-it.com
