
# AirBnb_Booking_Exploratory_Data-Analysis

My project is driven by the desire to explore the interplay between various attributes associated with Airbnb listings. My primary interest lies in the real estate sector, where I aim to highlight the pivotal role of data analysis. By leveraging data analysis, investors can gain valuable insights into the potential profitability of locations, including factors such as occupancy rates, average rental income, and return on investment. These insights can ultimately contribute to the economic growth of a region. The project focuses on analyzing critical aspects like location, pricing, customer trends, and competition.

## Choice of Data Source:
New York City, as one of the world's busiest and most renowned destinations, holds a unique position. It consistently draws a substantial portion of foreign visitors to the United States, with a staggering 67 million visitors in 2019. Given the city's popularity, it serves as one of the prime markets for Airbnb listings. Therefore, I have opted to utilize the New York Airbnb dataset as the foundation for my project.
## project architecture



## Dataset Description

For this project I am using a dataset 
https://drive.google.com/file/d/1OPtvqdDdHnfFw_OLDjx90ubj_CHh3qgx/view?usp=sharing

There are 16 parameters, the parameters consists information about the AirBnb name along with the price as well as 14 other features. There are around 49000 records in the dataset.

Parameters are :

id : Unique ID
name : Name of the listing
host_id : host ID
host_name : Name of the host
neighbourhood_group : location

neighbourhood : area

latitude : latitude coordinates

longitude : longitude coordinates

room_type : listing space type

price : price in dollars

minimum_nights : minimum nigth to be paid for

number_of_reviews : number of reviews

last_review : content of last review date

reviews_per_month : number of check per month/number of reviews 
per month

calculated_host_listings_count : total count

availability_365 : Availability around the year

### Project Implementation:
The core objective of this project is to unravel the intricate relationship between Airbnb listing prices in New York City and various associated attributes. The project comprises several essential phases:

1. **Data Wrangling:** I perform data wrangling to clean and refine the dataset, ensuring that it is ready for analysis.

1. **Data Transformation:** To benefit from parallel processing and enhance efficiency, I utilize Spark RDD (Resilient Distributed Datasets) for data transformation.

1. **Data Visualization:** Data visualization is a pivotal component of the project. It helps convey insights effectively and enables stakeholders to grasp the findings intuitively.

1. **Data Storage:** To facilitate further analysis and exploration, I store the clean and transformed data in MongoDB, a NoSQL database suitable for handling semi-structured data.

1. **Interactive UI Deployment:** To make the pre-analyzed results of the data accessible and user-friendly, I deploy an interactive user interface on the Heroku platform.

By following these steps, my project aims to provide a comprehensive understanding of the dynamics between Airbnb prices and various influencing factors in the bustling New York City market.

#### Main libraries used 
- pandas used for data manipulation and aggregation
- matplotlib used for data visualization and behaviour with respect to the target variable.
- Numpy used for complex numerical operations.




