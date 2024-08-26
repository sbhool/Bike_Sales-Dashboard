This project is to analyze the customer behaviour in the bike industry

Data Preparation and Transformation:

1)Duplicate Removal: We began by removing duplicates, eliminating 26 duplicate entries and retaining 1000 unique records.

2)Data Cleaning: The 'Marital Status' and 'Gender' columns were standardized for clarity ('M' to 'Married', 'S' to 'Single', 'F' to 'Female', and 'M' to 'Male').

3)Formatting: The 'Income' column was set as Currency type, and decimal places were removed.

4)New Column Creation: An 'Age Groups' column was introduced, categorizing ages into 'Old', 'Middle Aged', or 'Adolescent' based on an Excel formula.

5)Value Modification: In the 'Commute Distance' column, '10+ Miles' was changed to 'More than 10 Miles' for better interpretation.

Pivot Table Analysis and Visualization::

1. Average Income vs. Bike Purchases:
The data reveals a positive correlation between average income and bike purchases. Interestingly, males tend to purchase more bikes than females.

2. Commute Distance vs. Bike Purchases:
The highest number of bike purchases is for commutes within 0-1 miles. However, as the commute distance increases, especially beyond 10 miles, bike purchases significantly drop.

3. Age vs. Bike Purchases:
Middle-aged individuals are the most active bike purchasers, indicating that this age group values biking for commute.

4.Occupation vs. Bike Purchases:
Professional people are purhcasing more bikes as compared to the other profession.

5. North america people are more bike lovers as compared to Europe and Pacific.

Additionally, I've incorporated slicers for marital status, region, and education to provide a more granular analysis.
