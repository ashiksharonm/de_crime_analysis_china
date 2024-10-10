**CHINA CRIME DATA ANALYSIS**

- Acquire Data: Gathering the crime dataset with features like crime type, location, timestamp, demographic details (age, gender), weapon used, and crime scene characteristics (public/private).
- Use of SQL Database: Import the dataset into PostgreSQL and then connect to Python for cleaning and preprocessing the data and further analysis the data.
- Clean & Preprocess: Address missing values, format dates and times correctly, standardize categories (e.g., capitalize crime types consistently), and remove duplicate entries.
- Exploratory Data Analysis (EDA): Use Pandas and Matplotlib to analyze crime rates by location and type, identify temporal trends (hourly, daily, monthly, seasonal), and explore demographic patterns.
- Geospatial Visualization: Employ GeoPandas or ArcGIS to plot crime incidents on a map, creating visualizations like point maps and heatmaps to reveal crime hot spots and patterns.
- Clustering: Utilize K-Means clustering (or other clustering algorithms) to group similar crime incidents based on location, type, and other features, revealing underlying spatial and temporal patterns.
- Time-Series Analysis: Apply time-series models (e.g., ARIMA) to forecast future crime trends by analyzing historical crime data.
- Predictive Modeling: Develop predictive models using Random Forest Classifier to estimate future crime probabilities or classify crime types based on features like Latitude, Longitude, Victim Age and Hour.
