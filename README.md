Google Play Store Data Analysis

Overview : This project analyzes the Google Play Store dataset to uncover insights about app ratings, pricing, installs, and categories. The analysis involves data cleaning, handling missing values, removing duplicates, detecting and treating outliers, and answering business-related questions through statistical and visual methods.

**Features :

Data Cleaning: Conversion of data types, handling missing values, removing duplicates, and treating outliers.

Univariate Analysis: Understanding individual features such as app ratings, pricing distribution, and most common categories.

Bivariate Analysis: Identifying relationships between app installs, ratings, and pricing.

Visualizations: Bar charts, histograms, scatter plots, and box plots for better data interpretation.

**Dataset Information

*Columns Included: App Name, Category, Rating, Reviews, Size, Installs, Type (Free/Paid), Price, Content Rating, Genres, Last Updated, Current Version, Android Version.

*Key Transformations:

Converted data types (Price, Installs, and Last Updated).

Replaced missing values using median and mode.

Removed duplicate entries.

Capped outliers using percentiles.

**Business Questions Answered

What is the average app rating on the Play Store?

What percentage of apps are free vs paid?

What is the most common app category?

Which category has the highest number of apps?

How are app prices distributed?

Do free apps have better ratings than paid apps?

Which categories have the highest average ratings?

Does a higher number of installs correlate with higher ratings?

Do paid apps generate more installs than free apps?

Which categories have the most paid apps?

**How to Use

Open the Jupyter Notebook (GooglePlayStore_Project.ipynb).

Run the cells to execute data cleaning, transformation, and visualization steps.

Modify filters and explore different insights based on your requirements.

**Requirements

Python Libraries:

Pandas

NumPy

Matplotlib

Seaborn

**Insights & Business Impact

Understanding user preferences in terms of free vs paid apps.

Identifying popular categories and their growth potential.

Recognizing how pricing strategies impact app installs and ratings.

Providing recommendations for app developers and businesses to optimize their offering
