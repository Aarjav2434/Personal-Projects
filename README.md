# Weather Data
So i took a dataset called weather data(i have attached the csv file below along with code) and did few things with it about which I will below 

Also I have uploaded the pdf of the code as well as screenshots after every operation

This dataset contains hourly weather observations for a full leap year (8784 records). It includes key meteorological variables such as temperature, humidity, wind speed, visibility, atmospheric pressure, and a textual description of weather conditions. I have answered few questions for this dataset, I have listed down my reasons for including every question 

Calculating all the unique wind speed values in the dataset 

![image](https://github.com/user-attachments/assets/ede7a6d8-d8ab-4e5b-8376-6899abcce78b)



Usefulness :-  We can see every wind speed that ever happened in the data. This helps check that wind turbines and sensors work for all wind levels. It also shows if very strong or very weak winds are common or rare.

Times when weather was “Clear” 

![image](https://github.com/user-attachments/assets/a1c86902-08cc-41c1-87fe-a772e2f99f84)


Usefulness :- We count all the hours with clear skies. Solar panel owners use this to plan how much energy they can make. It also helps event planners pick sunny days for outdoor activities.

Times when wind speed was 4 km/h

![image](https://github.com/user-attachments/assets/4b70d918-8a89-431f-9806-2f1c5fb3e761)

Usefulness :- We count hours with a light breeze of exactly 4 km/h. Farmers need this to decide when to spray crops safely. Kite flyers and park managers also like to know how often gentle breezes occur.

Mean visibility

![image](https://github.com/user-attachments/assets/102efead-90e4-4cc6-b1b4-b4dc357113e7)


Usefulness :- Finding the average distance people can see. This tells drivers and pilots what to expect most of the time. It also helps road and airport teams set safety rules for foggy or clear conditions.

Standard deviation of pressure

![image](https://github.com/user-attachments/assets/be076864-eba7-4f07-bb7e-526a284106aa)


Usefulness :- Measures how much air pressure goes up and down from the average. Big swings often mean changing weather or storms are coming. Meteorologists watch this to give better weather warnings.

Variance of relative humidity

![image](https://github.com/user-attachments/assets/b50d4e50-00f5-4e3c-86ad-0ec63c9d20c3)


Usefulness :- Measures how much the moisture in the air changes over time. Large changes can make indoor spaces feel too damp or too dry. Building managers and HVAC teams use this to keep homes and offices comfortable.

Instances when snow was recorded

![image](https://github.com/user-attachments/assets/823e64e6-9f17-46b9-a4a3-aa1c6c942cec)


Usefulness :- Listing every hour it snowed. City crews use these times to know when to plow roads and clear sidewalks. Climate scientists also study snowfall patterns to track seasonal changes.

Instances when wind > 24 km/h and visibility = 25 km

![image](https://github.com/user-attachments/assets/2d81393e-41b2-4a73-aee5-8ba888626a07)


Usefulness :- Finding times with very strong wind but clear view. Pilots and sailors need this data to plan safe takeoffs and voyages. It also alerts road crews about possible blowing debris on highways.

Mean of each column per weather type

![image](https://github.com/user-attachments/assets/1b89d235-39b6-4489-b093-996805b83268)


Usefulness :- Calculates average temperature, humidity, wind speed, and other metrics for each weather label (rain, fog, clear, etc.). Helps weather apps display accurate icons and advice. Trains predictive models for more reliable forecasts.

Max and min per weather type

![image](https://github.com/user-attachments/assets/1bc4df62-4872-40c7-ba05-e4f0530dbf53)


Usefulness :- Finds the highest and lowest values of temperature, wind speed, etc., under each weather condition. Guides engineers in designing buildings and bridges to withstand extreme events. Helps emergency teams prepare for worst-case scenarios.

Instances when weather is foggy

![image](https://github.com/user-attachments/assets/2bf7007f-fcba-4365-b266-ff9e4ba0386b)


Usefulness :-  Lists every foggy hour in the dataset. Enables road and airport authorities to activate fog lights and issue travel warnings. Assists researchers studying fog frequency and patterns.

Instances when weather is clear and visibility > 40 km

![image](https://github.com/user-attachments/assets/77ee33e4-e0a7-4c97-9805-c4c62228ccba)


Usefulness :- Lists the best hours with perfect visibility and no clouds. Ideal for stargazing, drone photography, and outdoor sports. Helps event organizers select optimal windows for special events.

Instances when weather is clear and (humidity > 50% or visibility > 40 km)

![image](https://github.com/user-attachments/assets/2fd61822-0eaa-40d3-b90d-a26d7ec371f3)


Usefulness :- Identifies clear hours that are either humid or ultra-clear. Useful for photographers seeking sharp, bright shots. Informs gardeners and agricultural planners about optimal times for watering or harvesting.




[file (weather).csv](https://github.com/user-attachments/files/19865679/file.weather.csv)




[vertopal.com_Project 1(Weather data).pdf](https://github.com/user-attachments/files/19872148/vertopal.com_Project.1.Weather.data.pdf)
