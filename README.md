# py_yahoo
- - -
A Python Wrapper for [Yahoo Weather API](https://developer.yahoo.com/weather/)  

Documentation for the API is avilable [here](https://developer.yahoo.com/weather/documentation.html)
- - - 
## Installation:
```
pip install py_yahoo
```
## Usage 
```
from py_yahoo import YWeather

yw=YWeather()

#set the location
#check the yahoo weather website for the list of supported cities
yw.weatherat("avinashi")

#set the unit 'c'-->celsius 'f'-->fahrenheit(default)
yw.unit("c")  

w=yw.getweather()

print(m.getatmosphere())   #{'humidity': '58', 'pressure': '1013.0', 'rising': '0', 'visibility': '16.1'}
```

## Methods
The following are the list of available methods
* getlastbuilddate()
* getatmosphere()
* forecast()
* getlatitude()
* getlongitude()
* getlocation()
* getunits()
* getastronomy()
* getwind()
* weatheratwhatdatetime()
* getstatus()
* gettemp()

## Terms
[Yahoo APIs Terms of Use](https://policies.yahoo.com/us/en/yahoo/terms/product-atos/apiforydn/index.htm)
