# Yassir - Expected Time of Arrival (ETA) Prediction

## Project Overview

**Yassir** is a ride-hailing app, and the objective of this project is to accurately predict the **Estimated Time of Arrival (ETA)** at the drop-off point for a single journey. ETA prediction is crucial in enhancing user experience by providing reliable trip times, optimizing resource allocation, and improving overall operational efficiency.

This project involves using trip data and weather data to train a model that predicts how long a journey will take based on various factors like distance, weather conditions, and timestamps.

---

## Dataset Description

The project utilizes two main datasets:
1. **Trip Data** - Captures the details of each journey.
2. **Weather Data** - Provides the weather conditions at the time of the trip.

### Train Data (Trip Data) Columns

- **ID**: Unique identifier for each trip.
- **Timestamp**: The exact date and time when the trip started.
- **Origin_lat**: Latitude of the starting location (pickup point) of the trip.
- **Origin_lon**: Longitude of the starting location (pickup point) of the trip.
- **Destination_lat**: Latitude of the destination location (dropoff point).
- **Destination_lon**: Longitude of the destination location (dropoff point).
- **Trip_distance**: The distance traveled along the fastest route for the trip.

### Weather Data Columns

- **date**: The date for the weather data.
- **dewpoint_2m_temperature**: Dewpoint temperature measured at 2 meters above the ground (in Kelvin).
- **maximum_2m_air_temperature**: Maximum air temperature measured at 2 meters above the ground (in Kelvin).
- **mean_2m_air_temperature**: Average air temperature measured at 2 meters above the ground (in Kelvin).
- **mean_sea_level_pressure**: Average sea level pressure (in Pascals).
- **minimum_2m_air_temperature**: Minimum air temperature measured at 2 meters above the ground (in Kelvin).
- **surface_pressure**: Surface pressure (in Pascals).
- **total_precipitation**: Total amount of precipitation during the trip (in meters).
- **u_component_of_wind_10m**: The U component (east-west direction) of wind at 10 meters above ground level (in meters per second).
- **v_component_of_wind_10m**: The V component (north-south direction) of wind at 10 meters above ground level (in meters per second).

---

## Objectives

1. **Predict ETA**: Develop a model to predict the Estimated Time of Arrival for Yassir trips based on trip and weather data.
2. **Optimize User Experience**: Improve the accuracy of time estimates for users.
3. **Data-Driven Insights**: Leverage trip and weather data to understand factors influencing journey times.

---

## Approach

1. **Data Preprocessing**: Clean and preprocess the trip and weather data to remove inconsistencies, handle missing values, and format timestamps for easier analysis.
   
2. **Feature Engineering**: Generate additional features (e.g., distance calculations, weather conditions) to enrich the model input.

3. **Model Development**: Train machine learning models to predict the ETA based on the trip's origin, destination, distance, and weather conditions.

4. **Model Evaluation**: Evaluate the performance of the models using suitable regression metrics (e.g., RMSE, MAE) to ensure accurate ETA predictions.

---

## Technologies Used

- **Python**: Core language for data processing, feature engineering, and modeling.
- **Pandas**: For data manipulation and analysis.
- **Scikit-Learn**: For machine learning model development and evaluation.
- **NumPy**: For numerical computations.
- **Matplotlib/Seaborn**: For data visualization and insights.

---

## Usage

To use the code or experiment with your own data, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Yassir-ETA-Prediction.git
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook or Python scripts to preprocess the data, train models, and make predictions.

---

## Conclusion

This project aims to provide accurate predictions of travel times within the Yassir ride-hailing platform, improving both customer satisfaction and operational efficiency by leveraging trip and weather data.

---

Feel free to modify or extend this project to explore more sophisticated machine learning techniques or additional features for better ETA prediction!

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For any inquiries or contributions, feel free to reach out to me at [iamdenis46@gmail.com](mailto:iamdenis46@gmail.com).

