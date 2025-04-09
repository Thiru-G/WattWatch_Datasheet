Understood. Here’s a revised version of the README tailored for the combined daily dataset (where each file contains both behavior journal and corresponding appliance usage data):

WattWatch Dataset: Behavior-Synced Daily Energy Usage Records

This repository contains the full 6-month dataset generated as part of the research project:

“Development and Implementation of a User-Centric Real-Time Energy Monitoring and Feedback System for Energy Conservation.”

Each entry in this dataset links user behavior with device-level electricity usage, collected in five controlled room-level setups. The dataset is designed to study how personalized feedback, app-based nudges, and usage summaries influence consumer electricity usage patterns over time.

⸻

Dataset Description

Each file corresponds to one real-life test profile and contains daily records for 6 months (March–August 2024), divided as:
	•	March–May: Passive monitoring (no feedback)
	•	June–August: Active feedback system in use (via Proposed WattWatch app)

Each day logs both qualitative behavioral summaries and quantitative usage metrics for every electrical device used.

⸻

Profiles Covered
	•	Profile 1: 21-year-old male college student
	•	Profile 2: 21-year-old female college student
	•	Profile 3: Hall used by an Indian couple (45–50 years old)
	•	Profile 4: Shared bachelor apartment (3 roommates)
	•	Profile 5: Faculty cabin (institutional use)

⸻

File Structure

WattWatch_Datasheet/
│
├── 21M_FullData.csv
├── 21F_FullData.csv
├── Couple_FullData.csv
├── Bachelors_FullData.csv
└── Faculty_FullData.csv

⸻

Column Definitions

Column	Description
Date	Calendar date
Day	Day of the week (e.g., Monday)
Behavior Journal	1–2 line free-text summary of the user’s activities or contextual notes
Device	Name of the electrical appliance
Rated Power (W)	Device’s nominal power consumption in watts
Time Used (hrs)	Duration (in hours) the device was active on that day
Energy Consumed (kWh)	Computed as (Rated Power × Time Used) ÷ 1000
Total Daily Load	Sum of kWh consumed by all devices for that day
App Feedback Used	Indicates whether feedback & nudges were active (True/False)



⸻

Use Cases

This dataset supports:
	•	Energy behavior research in controlled residential and institutional environments
	•	Quantitative evaluation of feedback mechanisms and nudging strategies
	•	Temporal analysis of device-specific consumption vs. contextual routines
	•	Simulation and ML-based demand prediction models

