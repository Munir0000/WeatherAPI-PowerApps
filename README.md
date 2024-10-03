# Weather API Integration in Power Apps

![Weather API Logo](https://via.placeholder.com/150) <!-- Replace with an actual logo/image URL -->

## Project Overview

**Objective:** Integrate Weather API endpoints into Power Apps to display real-time weather information, store historical weather data in Dataverse, and allow users to query weather information based on location.

**Technologies:**
- **Power Apps**
- **Dataverse**
- **Weather API**
- **Custom Connector**

---

## Features

### A. User Interface
- **Weather Search Screen**
  - Input field for users to enter a location (city name or zip code).
  - Button to fetch weather data.
  - Display area for current weather details (temperature, conditions, humidity, etc.).
  
- **Historical Weather Data Screen**
  - Dropdown to select a previously searched location.
  - Display area for historical weather data.

### B. Weather Data Fetching
- **Custom Connector**
  - Create a custom connector in Power Apps to connect to the Weather API.
  - Configure authentication and endpoints (e.g., current weather, forecast).

- **Data Retrieval**
  - Use the custom connector to fetch current weather data and store it in Dataverse.

### C. Dataverse Integration
- **Data Storage**
  - Store fetched weather data (current and historical) in Dataverse for future access.
  - Enable efficient querying and reporting.

- **Data Management**
  - Implement a mechanism to update the weather data at specified intervals or based on user actions.
