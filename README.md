# GeoSpatial Analysis - Zomato Data Analysis Project 🔥

<p align="center">

  [![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
  
  ![GitHub stars](https://img.shields.io/github/stars/Lokesh-Attarde/Geospatial-Analysis-Project)
  ![GitHub forks](https://img.shields.io/github/forks/Lokesh-Attarde/Geospatial-Analysis-Project)
  [![GitHub contributors](https://img.shields.io/github/contributors/Lokesh-Attarde/Geospatial-Analysis-Project.svg)](https://GitHub.com/Lokesh-Attarde/Geospatial-Analysis-Project/graphs/contributors/)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
  [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
</p>  

![zomato](https://user-images.githubusercontent.com/84115928/139818260-1d656ae6-8abb-455f-9c1a-5b036734e484.jpg)

# 📝Problem Statement
Analysis of the following is required by the Sales Director of Zomato Food Chain:

    1. Most famous Restaurant Chains in Bangalore.
    2. Analyse Restaurants which are Accepts Online Order and do not ones.
    3. Highest Voted Restaurant.
    4. Places with Maximum Number of Restaurants / Total Restaurants at different locations of Bangalore.
    5. Total Number of variety of Cuisine Restaurants in Bangalore.
    6. Relationship between "Approx Cost of 2 People" vs "Rating" for those Restaurant that Accepts "Online Order" and for those Restaurants that doesn't Accept "Online Order".
    7. Is there any difference b/w 'Votes' and 'Restaurants' Accepting and Not Accepting "Online_Orders".
    8. Identify Restaurants that are Budgeted Hotels as well as Affordable.
    9. Restaurants having good Rating and Budgeted/Affordable too.
    10. Most Foodie Areas of Bangalore.
    11. Clutter of particular Cuisines in Bangalore. North Indian Restaurants, South Indian Restaurants, Biryani Cuisines.
    12. Analyze where are the Restaurants with Most Average Ratings.

And so many more!!

# ⏳ Dataset
Download the dataset for this project from following Link -
* [Zomato Bangalore Restaurants](https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants/download)

# 📚 Data Analysis
In the datasets, we are provided with 17 columns(Features) of data.

* **url** : Contains the url of the restaurant on the Zomato Website.
* **address** : Contains the Address of the restaurant in Bangalore.
* **name** : Contains the Name of the restaurant.
* **online_order** : Whether Online Ordering is available in the restaurant or not.
* **book_table** : Table book option available or not.
* **rate** : Contains the Overall Rating of the restaurant out of 5.
* **votes** : Contains total number of ratings given for the restaurant.
* **location** : Contains the neighborhood where the restaurant is located.
* **rest_type** : Restaurant type.
* **dish_liked** Dishes people liked in the restaurant.
* **cuisines** : Food styles.
* **approx_cost(for two people)** : Contains the approximate cost for the meal of two people.
* **reviews_list** : Containing rating and review given by the customer.
* **listed_in(city)** : Contains the neighborhood in which the restaurant is listed.

Out of the 17 features given in the datasets, 04 are Continuous and 13 (including the target variable) are Categorical features.

# 🖥️ Technologies:
## 🛠️ Tools Used
* Jupyter Notebook is used as IDE.
* Pandas and NumPy are used for Data Manipulation & Pre-processing and Mathematical functions respectively.
* For visualization of the plots, Matplotlib, Seaborn, Plotly are used.
* Geopy and Folium libraies were used to perform Spatial Analysis.
* GitHub is used as version control system

# 🎉 Tasks performed under Spatial Analysis:
* Extract the **"Latitude"** and **"Longitude"** w.r.t. different Locations using Python's ***Geopy*** Library.
* Generated a **"BaseMap"** of Bangalore using Python's ***Folium*** Library.
* Plotted a HeatMap based of variety of Use Cases with the help of Python's ***Folium "HeatMap" Plugins.***
* Performed **"Marker Cluster Analysis"** on top of the **"HeatMap"** using Python's ***Folium "FastMarkerCluster" Plugins.***

# 🏽‍ Some Exciting Glimpse of the Visuals:
![Glimpse 1](https://user-images.githubusercontent.com/84115928/139532704-82c5ed9a-3019-4689-bda8-4bdf476c9728.gif)

For more details, please go Tableau Dashboard link given below -

# 📋 Challenges Faced during this Project:
* To know about What are the different kinds of challenges encountered during this project, do connect with me for more details.
