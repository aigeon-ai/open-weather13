markdown
# open-weather13 MCP Server

## Overview

The `open-weather13` MCP server provides real-time and forecast weather data for any location worldwide. It aggregates and analyzes data from various sources, including global and local weather models, satellites, radars, and an extensive network of weather stations. This ensures accurate and up-to-date weather information.

### Key Features

- **Real-Time Weather Data**: Obtain current weather conditions for any specified location.
- **Diverse Data Sources**: Utilizes information from international weather models, satellites, and local weather stations for comprehensive analysis.
- **Global Coverage**: Access weather information for any location worldwide.

### Performance Metrics

- **Popularity**: 9.9
- **Service Level**: 99%
- **Latency**: 579ms
- **Test Coverage**: 100%

## API Response Fields

- **Coordinate (`coord`)**: Includes longitude and latitude of the location.
- **Weather (`weather`)**: Provides weather condition ID, main weather parameters (e.g., Rain, Snow, Clouds), description, and a weather icon ID.
- **Main Parameters (`main`)**: Encompasses temperature, feels-like temperature, atmospheric pressure, humidity, and temperature extremes.
- **Visibility (`visibility`)**: Measured in meters, with a maximum value of 10 km.
- **Wind (`wind`)**: Details wind speed, direction, and gusts.
- **Clouds (`clouds`)**: Indicates cloudiness percentage.
- **Rain (`rain`)**: Provides rainfall volume over the last 1 and 3 hours, where available.
- **Snow (`snow`)**: Provides snowfall volume over the last 1 and 3 hours, where available.
- **System Information (`sys`)**: Contains internal parameters, country code, and sunrise/sunset times.
- **Timezone (`timezone`)**: Shift in seconds from UTC.
- **City Information**: City ID and name.

## Tools and Functions

### Current Weather by City Name

- **Description**: Retrieve current weather data based on city name.
- **Parameters**:
  - `city`: The name of the city.
  - `lang`: Optional. Specify language for response. Supports various languages.

### Current Weather by Latitude & Longitude

- **Description**: Retrieve current weather data based on geographic coordinates (latitude and longitude).
- **Parameters**:
  - `latitude`: Latitude of the location.
  - `longitude`: Longitude of the location.
  - `lang`: Optional. Specify language for response. Supports various languages.

### 3-Hour Forecast for 5 Days

- **Description**: Obtain a 5-day weather forecast with 3-hour intervals for a specified location using latitude and longitude.
- **Parameters**:
  - `latitude`: Latitude of the location.
  - `longitude`: Longitude of the location.
  - `lang`: Optional. Specify language for response. Supports various languages.

## Subscription Plans

- **BASIC**: $0.00 / mo
- **PRO**: $2.99 / mo
- **ULTRA**: $4.99 / mo
- **MEGA**: $9.99 / mo

Explore the various subscription plans to enhance your weather data experience with the `open-weather13` MCP server.