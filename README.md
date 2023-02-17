# British Airways - Customers Review

This project is a part of the Data Science virtual internship program offered by Forage with British Airways.

# Task Categories:
1. Web scraping to gain company insights
2. Predicting customer buying behaviour

## Webscraping to Gain Company Insight
**Background Information:** Customers who book a flight with BA will experience many interaction points with the BA brand. Understanding a customer's feelings, needs, and feedback is crucial for any business, including BA. This first task is focused on scraping and collecting customer feedback and reviewing data from a third-party source and analysing this data to present any insights you may uncover. Customer review data for Britis Airways was collected from Skytrax.

### Situation
The goal was to scrape, clean, analyze and visualize the reviews data. 

### Task
The task was to  scrape british airline reviews from the skytrax website. Analyze and visualize customer reviews.

### Actions
- The code was written to scrape customer reviews, ratings, and verification status from a website.
- A function was defined to clean the data in the review, rating and verification columns.
- The cleaned data was used to create a new column called "Analysis" which assigned a sentiment score to each review using the VADER library.
- The frequency of each sentiment score was counted and visualized using a bar chart.
- The verification column was visualized using a pie chart.

### Result
-  code was able to clean, analyze and visualize the customer review data effectively.
- The bar chart showed the distribution of sentiment scores for the customer reviews.
- The pie chart showed the distribution of verification status for the customer reviews.
- The data analysis provided insights into customer opinions and experiences with the airline.

### Technologies used
- Python 
- Google Sheets 
- Pandas, Numpy, Jupyter Notebook


## Predicting customer buying behaviour
###Background Information
Customers are more empowered than ever because they have access to a wealth of information at their fingertips. This is one of the reasons the buying cycle is very different to what it used to be. Today, if you’re hoping that a customer purchases your flights or holidays as they come into the airport, you’ve already lost! Being reactive in this situation is not ideal; airlines must be proactive in order to acquire customers before they embark on their holiday.


### Situation
This task involves building a high quality predictive to predict the successful bookings using customer bookings data.

### Actions
1. Importing Necessary Libraries
2. Data Cleaning
3. Spliting the data into test and train datasets
4. Building the model
5. Fitting
6. Testing the model
7. Visualizations

### Results
- Accuracy of the model predicting successful or incomplete booking is 61%
- Top 3 features that can influence successful flight booking are:
        1. Purchase Leads
        2. Length of stay
        3. Flight hour
- There is a 66% chance of predicting true incomplete booking correctly





