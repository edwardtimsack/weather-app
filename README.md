# Weather App
Weather App is scripting application designed to fetch weather forecasts for a specific location and display the weather information in the terminal. This app also includes API Intergration, Unit Conversion e.t.c.

## Installation
+ Download [weather-app.sh](https://github.com/edwardtimsack/weather-app/blob/main/weather-app.sh)
+ Make script file executable
```
chmod +x weather-app.sh
```
+ Run file
```
./ weather-app.sh
```
## Features
+ Location Input
  ~~~
   Allow user to enter their location.
  ~~~
 
+ API Integration
  ~~~
   Using curl to make HTTP requests to a weather API.
  ~~~
 
+ Display Weather Data
  ~~~
   Displaying the retrieved weather data in the terminal. For JSON Parsing we use 'jq' a command-line JSON Processor, to extract specific fields from the API response.
  ~~~
  
+ Error Handling
  ~~~
   Conditional statements and error checking techniques to handle issuses like invalid location input or failed API requests.
  ~~~
  
+ Forecast
  ~~~
   Giving users the opportunity to see the weather forecast for one or more days after current day.
  ~~~

+ Interactive Features
  ~~~
   Use recursion to allow users to check weather for multiple locations sequentially.
  ~~~
  ### API Used

    [weatherAPI.com](https://www.weatherapi.com/)
    
  + Our API Key
      ~~~
      8f920a708a6e478aafa21737230811
      ~~~

  ### Concepts To Be Used
  
  + Basically a table that we are manipulating data from and will also include the following commands:
      ~~~
      if & else if
      function
      grep
      variable
      awk ....
      ~~~
