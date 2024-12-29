# MAVEN-CAFE-REWARDS-ANALYSIS (OVER 30-DAY PERIOD)

# Maven Cafe Promotional Offers Analysis

## Project Background and Overview
Maven Cafe sent out different combinations of promotional offers to existing rewards members over a 30-day period. Here, I explore the effectiveness of these different offers by analyzing customer behaviour in response to various offers. The Result aims to optimize future promotional strategies to increase engagement, offer redemptions, and overall sales. Reccommendations are to be used by marketing and product team of Maven Cafe to better allocate the best offers to the right customers.

## Goals
- **Evaluating Offer Dynamics**: Offer Frequency, Reward Size, and Duration:  These factors influence customer engagement, redemption rates, and overall sales, helping Maven Cafe allocate resources efficiently and optimize customer response to maximize ROI
- **Customer Segmentation**: Identifying key customer segments based on various demographics allows Maven Cafe to target promotions more effectively by focusing on groups with higher engagement and redemption potential
- **Identifying Optimal Offer Delivery Channels**: By determining the most effective channels (social media, mobile, email, web) for delivering offers, Maven Cafe can maximize reach and engagement. This helps to prioritize platforms that yield higher viewing and redemption rates, and therefore more sales.


## Data Structure and Overview
 This data has been provided by Maven Analytics for the Maven Rewards Challenge. 
 1. **Offers dataset**: This includes information about the various offer strategies, including the offer type (BOGO or Discount), difficulty (minimum amount required to trigger the offer), reward (amount in dollars received after completing the offer), duration (limited time required to complete the offer), and various marketing channels used (email, social media, etc.).
 2. **Customers dataset**: This Provides demographic information about the various rewards members, including their gender, age, estimated annual income, and membership date. These segments can then be targeted with tailored offers, ensuring better alignment with customer preferences and behaviors
 3. **Events Dataset**: This dataset is crucial as it includes the data on customer performance with records for each event, such as whether an offer has been received, viewed, completed, or if a transaction has been made unrelated to the offer.


   #### <ins> Data Modeling </ins>
   ![Data structure](https://github.com/user-attachments/assets/bec4ecc1-982e-4807-b4b5-56645377b2ce)

## Data Preparation
- **Imported Data**: Imported multiple CSV files (Offers, Customers, Events) into Power BI.
- **Data Modeling**: Utilized **Power Pivot** to link primary and foreign keys between tables.
- **Data Cleaning**: Used **Power Query** for cleaning and transforming the data for analysis.

## Data Transformation
For easy analysis, I have transformed each offer into the following code: 
"**offer type** - **Difficulty** - **Reward** - **Duration** "
For example: " **discount-10-2-10** " means It is a **discount** offer which requires **$10** to trigger the offer, Gives a reward of **$2** and must be completed within **10 days**

## MAVEN CAFE: PROMOTIONAL OFFERS COMPREHENSIVE REPORT

## PERFOMANCE OF VARIOUS OFFERS AND OFFER TYPES
**Discount** offers emerged as the most successful offer type, accounting for **18,000** completed offers (**53%** redemption rate). Among these, the **Discount-10-2-10** and **Discount-7-3-7** offers drove over **58%** of all completions for this offer type. **BOGO** offers also performed well, achieving a **47%** redemption rate, with **BOGO-5-5-7** and **BOGO-5-5-5** contributing to over **55%** of these redemptions.

![image](https://github.com/user-attachments/assets/65f804f7-702e-4f95-bd49-6d89039a7a4f)


##
## Key Insights
- **Offer Frequency**: Sending offers every 3-4 days led to significantly higher offer completions and transactions compared to weekly offers.
- **Duration & Redemption Rates**: Longer offer durations resulted in higher redemption rates, particularly with moderate rewards.
- **Customer Segments**: Baby Boomers earning over $50K are highly engaged and ideal for targeted future promotions.
- **Channel Effectiveness**: Social Media and Web channels had the highest offer views and conversions, making them crucial for future campaigns.

[Click for Live Dashboard](https://app.powerbi.com/groups/me/reports/4cab4b17-8d9f-42ee-b7ca-c7dbcec72fe9/df410caf5b1688659ee0?experience=power-bi) 
