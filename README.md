# Analyzing-Extraterrestrial-Impacts_Meteorite

This project analyzes a meteorite dataset to uncover insights about meteorite landings, their classifications, masses, and temporal trends. The visualizations and interpretations provide a comprehensive understanding of the patterns in meteorite discoveries and their characteristics.
________________________________________
# Questions Explored

1.	Total Number of Meteorites: How many meteorites are included in the dataset?
2.	Geographical Distribution: Where have most meteorites been discovered?
3.	Top 10 Countries: Which countries have the most meteorite discoveries?
4.	Largest Meteorite: What is the mass of the largest meteorite?
5.	Fall vs. Found: How many meteorites were found versus seen falling?
6.	Meteorite Classes: How many types exist, and how many of each type have been found?
7.	Class-Year Trends: How do meteorite class discoveries change over the years?
8.	Cumulative Mass: How much do all meteorites weigh, and how does the weight vary yearly?
9.	Top Classes by Average Mass and Count: What are the top 10 meteorite classes based on average mass and count?
10.	Discovery Trends: How have meteorite discoveries changed over decades?
11.	Mass by Class: Are there specific meteorite classes with higher masses?
________________________________________
# Visualizations

1. Total Meteorites
A basic count of the dataset entries represents the total meteorites analyzed.
2. Geographical Distribution
•	Map Plot: Displays the distribution of meteorite landings globally.
3. Top 10 Countries
•	Bar Plot: Shows the countries with the highest number of meteorite discoveries.
4. Largest Meteorite
•	Direct extraction and display of the largest meteorite's mass in grams.
5. Fall vs. Found
•	Pie Chart: Compares meteorites that were "found" versus those that "fell."
6. Meteorite Classes
•	Pie Chart: Highlights the predominant meteorite classes, focusing on those with ≥5% contribution.
7. Class-Year Trends
•	Scatter Plot (Bubble): Depicts changes in meteorite discoveries by class and year, with bubbles representing class counts.
8. Cumulative Mass
•	Line Plot: Displays the cumulative extraterrestrial mass on Earth due to meteorites over the years.
•	Bar Plot: Illustrates annual meteorite masses with logarithmic scaling for better visualization of variance.
9. Top Classes by Average Mass and Count
•	Bar + Scatter Plot: Combines average mass and class count for the top 10 meteorite classes.
10. Discovery Trends
•	Line Plot: Tracks yearly discovery counts over time.
11. Mass by Class
•	Box Plot: Explores the mass distribution of the top 5 meteorite classes by total mass.
________________________________________
# Key Insights

1.	Fall vs. Found: 
o	~98% of meteorites were "found," with only ~2% observed falling.
2.	Class Dominance: 
o	Predominant classes include H5 (16%) and L6 (18%).
3.	Temporal Trends: 
o	Discovery rates have risen significantly, likely due to advancements in exploration.
4.	Cumulative Mass: 
o	By 2023, the total extraterrestrial mass on Earth reached approximately 50,235 kg (~55 US tons).
5.	Meteorite Classes: 
o	Class L6 has the highest count, with an average mass of ~1.5 kg.
6.	Mass Distributions: 
o	Certain classes show extreme mass outliers dominating their total mass contribution.
________________________________________
# How to Run

1.	Dependencies: 
o	Python libraries: pandas, plotly, numpy
2.	Steps: 
o	Load the dataset into a DataFrame (df1).
o	Execute the Python scripts provided for each question to generate the visualizations.
o	Interpret the outputs using the corresponding insights.
________________________________________
# Conclusion

The analysis reveals fascinating patterns in meteorite landings. The overwhelming majority of meteorites are "found" rather than observed falling, suggesting a significant delay in detection and recovery. Meteorite classes like L6 and H5 dominate in frequency, while a few classes have exceptionally high masses. Discovery trends show a notable increase in recent decades, likely fueled by better technology and research efforts. The cumulative extraterrestrial mass on Earth has grown significantly over centuries, with some years witnessing massive spikes due to notable meteorite events. This analysis provides a strong foundation for further geospatial and temporal studies in planetary science.
________________________________________
# Future Scope

•	Geospatial Analysis: 
o	Map meteorite discoveries and examine regional trends.
•	Correlation Studies: 
o	Investigate relationships between meteorite mass, classification, and geographic location.
•	Historical Events: 
o	Overlay discovery trends with historical or scientific advancements.

