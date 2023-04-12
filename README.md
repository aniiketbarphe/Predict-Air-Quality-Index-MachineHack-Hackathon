![INTRO1](https://user-images.githubusercontent.com/84449238/231508978-3cb0ba1e-a04f-4579-b82f-b2f2a0200c2f.JPG)

# Predict-Air-Quality-Index-MachineHack-Hackathon

👋 Welcome to our Hackathon on tackling air pollution! 🌬️ Air pollution is a major global issue that affects the health and well-being of millions of people. 💔 To help you understand the quality of air in your city, we've included some important keywords for you to explore. The Air Quality Index (AQI) is a widely-used measure of air pollution that provides information on the quality of air in a city on a daily basis. 🔍 You can check the AQI of your location or search for the AQI by city, and even view it on a live map.

🤔 If you're wondering why the air quality is unhealthy today, the AQI calculation takes into account the levels of five major air pollutants, including ground-level ozone, particle pollution/particulate matter (PM2.5/pm 10), carbon monoxide, sulfur dioxide, and nitrogen dioxide. These pollutants can have different impacts on health, and their levels are measured to determine the overall AQI. In the United States, you can also find a ranking of air quality by state.

🌡️ The AQI is divided into six levels of air quality, ranging from "good" to "hazardous". It's important to pay attention to the AQI in your area and take precautions if the air quality is poor. With this knowledge, we hope you can take steps to protect yourself and those around you from the harmful effects of air pollution.

👉 The AQI bucket categories are outlined below:

0 - Good (0-50) - This indicates minimal impact.
1 - Satisfactory (51-100) - This category can cause minor breathing difficulties in susceptible individuals.
2 - Moderately polluted (101-200) - This category can cause breathing difficulties in people with lung diseases, such as asthma, as well as discomfort for heart disease patients, children, and older adults.
3 - Poor (201-300) - This category can cause breathing difficulties in people who are exposed to it for prolonged periods, as well as discomfort for individuals with heart disease.
4 - Very Poor (301-400) - This category can cause respiratory illness in people who are exposed to it for prolonged periods.
5 - Severe (401-500) - This category can cause respiratory issues in otherwise healthy people, and may result in very severe health problems for those with lung or heart disease.
6 - Very Severe (500 and above) - This category is considered uninhabitable.
🌍 Our hackathon is focused on finding innovative solutions to reduce air pollution and improve air quality. 🙌 We encourage participants to use their creativity and expertise to develop solutions that can help mitigate the negative impacts of air pollution on health and the environment. Let's work together to create a healthier, cleaner future for everyone! 🌿💪

Train: 495512 x  15
Test: 212363 x 14

The dataset contains observations on the following variables:
City: the name of the city where the air quality is measured
Datetime: the date and time of the air quality measurement
PM2.5: concentration of particulate matter less than 2.5 micrometers in diameter (unit: micrograms per cubic meter, µg/m³)
PM10: concentration of particulate matter less than 10 micrometers in diameter (unit: micrograms per cubic meter, µg/m³)
NO: concentration of nitrogen monoxide (unit: parts per billion, ppb)
NO2: concentration of nitrogen dioxide (unit: parts per billion, ppb)
NOx: concentration of nitrogen oxides (unit: parts per billion, ppb)
NH3: concentration of ammonia (unit: parts per billion, ppb)
CO: concentration of carbon monoxide (unit: parts per million, ppm)
SO2: concentration of sulfur dioxide (unit: parts per billion, ppb)
O3: concentration of ozone (unit: parts per billion, ppb)
Benzene: concentration of benzene (unit: micrograms per cubic meter, µg/m³)
Toluene: concentration of toluene (unit: micrograms per cubic meter, µg/m³)
Xylene: concentration of xylene (unit: micrograms per cubic meter, µg/m³)
AQI_Bucket: the Air Quality Index (AQI) bucket to which the observation belongs. The AQI bucket represents the level of air quality, with higher values indicating poorer air quality.
This dataset contains air quality measurements for several cities, with observations taken at different dates and times. The variables represent different pollutants and their concentrations in the air, as well as the AQI bucket, which provides an overall measure of air quality.

What is the Metric In this competition? How is the Leaderboard Calculated?
The submission will be evaluated using the RMSLE metric. One can usenp.sqrt(mean_squared_log_error(actual, predicted)) to calculate the same
This hackathon supports private and public leaderboards
The public leaderboard is evaluated on 30% of Test data
The private leaderboard will be made available at the end of the hackathon which will be evaluated on 100% of Test data
The Final Score represents the score achieved based on the Best Score on the public leaderboard
