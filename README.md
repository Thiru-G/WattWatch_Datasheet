# WattWatch_Datasheet
A dataset repository for “WattWatch: Electricity Consumer Behavior Monitoring and Feedback for Energy Conservation Using IoT.” This project uses IoT data to provide insights into energy usage, cost savings, and user engagement with conservation recommendations.
Here’s a refined GitHub README dataset description suitable for a research paper and with a reference to the YouTube video description.

---

# WattWatch Dataset: Electricity Consumer Behavior Monitoring and Feedback for Energy Conservation Using IoT

Welcome to the WattWatch dataset repository! This dataset is part of our capstone project, "WattWatch: Electricity Consumer Behavior Monitoring and Feedback for Energy Conservation Using IoT." It supports our energy management system by providing real-time data insights on consumer electricity consumption, enabling personalized feedback, and fostering energy conservation behaviors.

### Project Summary

WattWatch is an IoT-based energy monitoring and feedback system aimed at empowering users with actionable insights into their energy consumption patterns. By analyzing this dataset, researchers and developers can better understand user interactions with energy feedback mechanisms and evaluate the impact of feedback on promoting energy-saving behaviors. Our team’s objective is to harness this data to encourage efficient energy use, reduce costs, and support sustainable energy practices.

### Dataset Description

The dataset spans a six-month period, capturing daily records for each participant. The variables included in this dataset are designed to measure both objective energy consumption and subjective user interactions:

| Column Name                    | Data Type  | Description                                                                                             |
|--------------------------------|------------|---------------------------------------------------------------------------------------------------------|
| `Date`                         | Date       | The date of the record entry, spanning from 2024-05-01 to 2024-10-31.                                   |
| `User ID`                      | Categorical| Unique identifier for each user, representing individual households.                                     |
| `Total Consumption (kWh)`      | Float      | Total electricity consumption per day in kilowatt-hours (kWh).                                          |
| `Peak Consumption (kWh)`       | Float      | Energy consumed during peak hours (kWh), calculated based on hourly usage patterns.                     |
| `Off-Peak Consumption (kWh)`   | Float      | Energy consumed during off-peak hours (kWh), complementing peak consumption values.                     |
| `Cost (INR)`                   | Float      | Daily electricity cost calculated using standard rates from TNEB.                                       |
| `Cost Savings (INR)`           | Float      | Estimated cost savings from behavioral changes, with recommendations like adjusting A/C during cool hours.|
| `Logins/Day`                   | Integer    | Number of times the user accessed the WattWatch app per day, reflecting engagement level.               |
| `Feedback Interaction (%)`     | Integer    | Percentage of feedback viewed or acknowledged by the user per day.                                      |
| `Recommendations Implemented (%)` | Integer | Percentage of daily recommendations followed by the user, indicating behavioral compliance.             |
| `Uptime (%)`                   | Float      | Uptime percentage of the IoT system, calculated per day.                                               |
| `Data Integrity (%)`           | Float      | Integrity of data capture and transmission from sensors, represented as a percentage.                   |
| `Downtime (min)`               | Integer    | Minutes of downtime recorded per day due to connectivity or hardware issues.                           |
| `Temperature (C)`              | Float      | Daily average temperature in Celsius, potentially influencing energy consumption.                       |

### Usage and Access

The dataset is designed to be accessible and modifiable to support a wide range of energy behavior studies. By referencing this data, researchers can analyze the correlation between temperature, user interaction with the WattWatch app, feedback response rates, and daily energy cost savings.

### Contributors

- Bhavithrah Jegan (20BEE1015)
- Thirumalai Srinivasan G (20BEC1155)
- Project Guide: Dr. Sangeetha R G

For more details, check our demonstration video [here](https://www.youtube.com/watch?v=your-video-link). Join us on this journey as we leverage IoT technology to build a more sustainable future through informed energy consumption!
