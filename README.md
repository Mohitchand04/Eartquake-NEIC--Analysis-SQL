**Earthquake Data Analysis**
Problem Statement:
The National Earthquake Information Center (NEIC) maintains a comprehensive dataset recording significant earthquakes worldwide, dating back to 1965. This dataset includes essential details such as the date, time, location, depth, magnitude, and source of each earthquake with a reported magnitude of 5.5 or higher.

The goal of this project is to perform a thorough SQL analysis on the earthquake data to derive meaningful insights. The analysis aims to:

Determine the frequency of earthquakes over various time periods (yearly, quarterly, monthly).
Identify peak periods of seismic activity.
Calculate statistical measures such as average, maximum, and minimum values of earthquake magnitudes and depths.
Detect any long-term trends or patterns in seismic activity, such as increasing or decreasing earthquake frequencies or magnitudes.
Objective
Provide actionable insights for scientists, disaster management agencies, and the public to improve earthquake preparedness and response strategies

**Dataset Description**
The dataset contains the following columns:

ID: A unique identifier assigned to each earthquake event.
Date: The date of the earthquake.
Time: The exact time the earthquake was recorded.
Latitude: The latitude coordinate of the earthquake’s epicenter.
Longitude: The longitude coordinate of the earthquake’s epicenter.
Type: The type of seismic event (e.g., earthquake, explosion, etc.).
Depth: The depth of the earthquake in kilometers below the Earth’s surface.
Magnitude: The magnitude of the earthquake.
Magnitude Type: The scale used to measure the magnitude (e.g., Richter, Moment Magnitude).
Source: The reporting agency or entity.
Status: The status of the earthquake report (e.g., reviewed, automatic).

**NOTE**
The queries in this project is written in Bigquery so if some query doesn't work in MySQL make sure to check the alternative syntax for SQL for the same.
