# Be A Wise Host in Airbnb
### Team: Happy Data
### Members: Chenchen He, Jing Wang, Yahan Hu

## Introduction:
Airbnb is a popular online marketplace that enables people to list, find or rent houses for a processing fee. The data from “Inside Airbnb” provides detailed information on the listing of houses, host information, and detailed guests reviews. The analytics of Airbnb’s datasets could really help Airbnb hosts make more profits.

This big issue can be seperated into four sub-logical questions:

1) Find a worthy neighborhood where the houses are sold at a lower price level but leased at a higher price level

2) Figure out the best house-type which could help hosts obtain the highest rental per person.

3) Determine the proper price to lease

4) Write good descriptions to attract more guests


## Data Description:
#### Dataset location
"Inside Airbnb”: http://insideairbnb.com/get-the-data.html
#### There are four CSV files:
●	The listing.csv file is the summary information and metrics for house listings in New York City. The file mainly shows data in id & name of room and host, room’s location and neighborhood, the price of the room, the limit of duration for booking and reviewers’ response.

●	The lisings_detailed.csv file consists of 96 columns with 50041 observations, which provides detailed information on all listings in New York City.

●	There are two CSV files for reviews. First is reviews.csv which is a summary reviews date for listing_id(the id of the room in listing file, int64) and review date(str) to facilitate time-based analytics and visualizations linked to the listing dataset. Second is a reviews_detail.csv, which include listing_id(the id of the room in listing dataset, int64), id(the id for the review,int64), date(str), reviewer_id(int64) and name(str), comments(str).

## Analytics Description:
Mainly use categorical regressions with machine learning algorithms, Text Mining and Visualization.

For detailed analytics, please refer to summary.

https://github.com/ChenchenCU/Be-A-Wise-Host-in-Airbnb/blob/master/Be%20A%20Wise%20Host%20in%20Airbnb%20Summary.pdf
