# Title
Zomato Restaurant Data Analysis Using Python

## Project Objective
The objective of this project is to analyze Zomato’s restaurant dataset and extract meaningful insights about customer preferences and restaurant trends.
This helps in:
* Understanding which restaurant types are most popular
* Analyzing the role of online delivery vs. offline services
* Exploring ratings distribution and customer voting patterns
* Identifying preferred price ranges for dining out

## Dataset Used
<a href="https://github.com/mayu268/Zomato_anlaysis/blob/main/Zomato-data-.csv">Zomato Restaurant Dataset</a>

## Questions / KPIs
* Do more restaurants provide online delivery compared to offline services?
* Which types of restaurants are most favored by the general public?
* Which restaurant received the highest number of votes?
* What is the distribution of ratings across restaurants?
* What price range do couples prefer for dining out?

## Process
* Importing Libraries:
    * Used pandas, numpy, matplotlib, and seaborn for analysis and visualization.
* Dataset Loading:
* Data Cleaning & Preparation:
    * Converted rate column to float (removing /5 from ratings).
    * Checked for missing/null values.
    * Verified dataset structure using .info() and .head().
* Exploratory Data Analysis (EDA):
    * Restaurant Types → Countplot of categories from listed_in(type).
    * Votes Analysis → Grouped data by restaurant type and plotted total votes.
    * Highest Voted Restaurant → Identified restaurant with maximum votes.
    * Online Orders → Countplot of restaurants offering online vs. offline orders.
    * Ratings Distribution → Histogram of ratings.
## Final Conclusion
* Restaurant Types: Dining restaurants dominate the dataset and attract more votes.
* Online vs. Offline: Majority of restaurants do not accept online orders, though online ordering is growing.
* Highest Voted Restaurant: Identified the most popular restaurant based on votes.
* Ratings: Most restaurants fall within the 3.5–4 rating range, showing moderate to good customer satisfaction.
* Cost Preferences: Couples generally prefer restaurants with affordable mid-range costs.

Cost Analysis → Explored approximate cost for couples.
