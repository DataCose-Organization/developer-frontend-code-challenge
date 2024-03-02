# DataCose Code Challenge: Weather App

## Overview

This challenge tasks you with creating a compact weather application using Nuxt 3 and Nuxt UI. Your application will display current weather conditions across a selection of locations and provide a forecast for the coming week.

### Project Setup

A Nuxt 3 project template with Nuxt UI is provided as the base for this challenge. You are required to use this template. Feel free to install additional packages as needed to complete the challenge.

## Challenge Requirements

### Main Page

-   **Weather Table:** The homepage should feature a table displaying weather information for each chosen location, including:
    -   An icon representing the weather condition, based on the WMO code.
    -   The location's name.
    -   The current temperature in degrees Celsius.
    -   The current rainfall in millimeters.
    -   A "Remove" button for each location. Clicking this button should trigger a confirmation popup before the location is deleted from the table.

### Detailed Forecast

-   **Forecast Sidebar:** Clicking on a row within the table should open a sidebar. This sidebar will provide a detailed temperature and rainfall forecast for the next 7 days for the selected location.

### Location Management

-   **Add Location:** Incorporate a button above the table to add new locations. This will open a popup where users can search for and select a location to add to the table. Make sure the user can't submit the form if no location was selected.
-   **Data Persistence:** Utilize a Pinia store to manage the list of selected locations. Ensure persistence of this data to maintain the list even after page refreshes.

### API Integration

-   To fetch weather information, you are to use the [OpenMeteo API](https://open-meteo.com/). Given that this API requires latitude and longitude for location data, utilize [this predefined list of locations](https://gist.github.com/ofou/df09a6834a8421b4f376c875194915c9) as your hardcoded source.

## Evaluation Criteria

Your submission will be assessed based on:

-   **Functionality:** Adherence to the requirements and overall functionality of the application.
-   **Code Quality:** Organization, readability, and documentation of code.
-   **UI/UX Design:** The usability and aesthetic appeal of the application interface.
-   **Innovation and Creativity:** Any additional features or enhancements that improve the app's functionality or user experience.

## Submission Guidelines

-   Your completed project should be submitted as a ZIP file.
-   Include a Loom video walking through the UI.

We look forward to seeing your innovative solution. Best of luck!
