# READ ME

## Project Links
> [Tableau](https://public.tableau.com/shared/JZDRGH7D5?:display_count=n&:origin=viz_share_link)
> 

## **Overview**

This project aims to analyze data from the London public bike-sharing system to understand bike share trends and potentially predict future bike shares. The data utilized in this project is sourced from various platforms including the Transport for London (TfL) Open Data service, freemeteo.com for weather data, and the UK government's bank holidays dataset. The analysis covers the period from January 1, 2015, to December 31, 2016.

## **Data Sources**

1. **Transport for London (TfL) Open Data**: The cycling dataset obtained from TfL's data service provides information on bike shares including start time, temperature, humidity, wind speed, weather conditions, holiday indicators, weekend indicators, and seasonal categorization.
    - Source: [TfL Open Data](https://cycling.data.tfl.gov.uk/)
    - Attribution: Contains OS data © Crown copyright and database rights 2016 and Geomni UK Map data © and database rights [2019], Powered by TfL Open Data
2. **Weather Data**: Weather-related data such as real temperature, feels-like temperature, humidity, wind speed, and weather code is sourced from freemeteo.com.
    - Source: [freemeteo.com](https://www.freemeteo.com/)
3. **UK Bank Holidays**: Bank holiday information for the UK is obtained from the UK government's official website.
    - Source: [UK Government Bank Holidays](https://www.gov.uk/bank-holidays)

## **Data Description**

- **timestamp**: Timestamp indicating the time of bike share (grouped by hour).
- **cnt**: Count of new bike shares.
- **t1**: Real temperature in Celsius.
- **t2**: Feels-like temperature in Celsius.
- **hum**: Humidity percentage.
- **wind_speed**: Wind speed in km/h.
- **weather_code**: Category of weather (described below).
- **is_holiday**: Boolean field indicating if it's a holiday (1) or not (0).
- **is_weekend**: Boolean field indicating if it's a weekend (1) or not (0).
- **season**: Categorical field representing meteorological seasons: 0 - spring, 1 - summer, 2 - fall, 3 - winter.
- **weather_code descriptions**:
    - 1: Clear (mostly clear but may have some haze/fog)
    - 2: Scattered clouds/few clouds
    - 3: Broken clouds
    - 4: Cloudy
    - 7: Rain/light rain shower/light rain
    - 10: Rain with thunderstorm
    - 26: Snowfall
    - 94: Freezing fog

## **Project Description**

The project involves the creation of a dashboard in Tableau to analyze bike sharing data in London. It includes the following steps:

1. **Data Preparation**: Acquiring, cleaning, and preparing the cycling dataset obtained from TfL's data service, along with weather data and UK bank holiday information.
2. **Exploratory Data Analysis**: Analyzing the dataset to understand its structure, identify patterns, and explore relationships between variables.
3. **Visualization Development**: Using Tableau to create visually appealing and informative visualizations, including charts, graphs, and dashboards.
4. **Insight Generation**: Deriving insights from the visualizations to understand factors influencing bike sharing behavior, such as weather conditions, holidays, weekends, and seasons.
5. **Dashboard Creation**: Designing and building an interactive dashboard that provides a comprehensive overview of bike sharing trends and patterns in London.
6. **Validation and Testing**: Ensuring the accuracy and functionality of the dashboard by validating the data and conducting thorough testing.
7. **Documentation and Sharing**: Documenting the project process and findings, and sharing the dashboard with stakeholders for feedback and insights.

## **Acknowledgments**

- This project was made possible by the availability of data from Transport for London (TfL), freemeteo.com, and the UK government.
- I acknowledge the tutorial by [Mo Chen on YouTube](https://www.youtube.com/watch?v=nl9eZl1IOKI&t=673s) for guidance in executing this data analysis project.

Thank you for your interest in my project! If you have any questions or feedback, please feel free to contact us.
