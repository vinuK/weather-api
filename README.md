# Weather API

## DESCRIPTION

   RestFul API to retrieve weather information. 
   
## Usage: 

/api/weather?country=AU&city=Sydney

## Query Parameters:

* city: Name of the city to retrieve weather information for.
* country: Name of the country (optional) to retrieve weather information for.

Console screen shot: !https://github.com/vinuK/weather-api/blob/master/weather-api.png
 

### Curl Example:
```shell
curl -H Content-Type=application/json  http://127.0.0.1:8081/api/weather\?city\=Sydney\&country\=AU
{
	"CurrentWeather" : {
		"Location" : "Sydney Airport, Australia (YSSY) 33-57S 151-11E 3M",
		"Time" : "May 29, 2016 - 04:30 AM EDT / 2016.05.29 0830 UTC",
		"Wind" : " from the SW (230 degrees) at 8 MPH (7 KT):0",
		"Visibility" : " greater than 7 mile(s):0",
		"Temperature" : " 57 F (14 C)",
		"DewPoint" : " 39 F (4 C)",
		"RelativeHumidity" : " 50%",
		"Pressure" : " 30.06 in. Hg (1018 hPa)",
		"Status" : "Success"
	}
}%
```
