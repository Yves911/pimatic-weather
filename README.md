pimatic-weather
===============

Pimatic Plugin that retrieves the forecast on several devices

Configuration
-------------
Add the plugin to the plugin section:

    {
      "plugin": "weather"
    },

Then add the device with the location into the devices section:

    {
      "id": "weather",
      "class": "WeatherDevice",
      "name": "Geneva, Switzerland",
      "degreeType": "C",
      "timeout": 300000
    }

Then you can add the items into the mobile frontend
