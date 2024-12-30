# MAVEN-CAFE-REWARDS-ANALYSIS (OVER 30-DAY PERIOD)

# Maven Cafe Promotional Offers Analysis

## Table of content
1. [Project Background and Overview](#project-background-and-overview)  
2. [Goals](#goals)  
   - [Evaluating Offer Dynamics](#evaluating-offer-dynamics)  
   - [Customer Segmentation](#customer-segmentation)  
   - [Identifying Optimal Offer Delivery Channels](#identifying-optimal-offer-delivery-channels)  
3. [Data Structure and Overview](#data-structure-and-overview)  
4. [Data Preparation](#data-preparation)  
5. [Data Transformation](#data-transformation)  
6. [Maven Cafe: Promotional Offers Comprehensive Report](#maven-cafe-promotional-offers-comprehensive-report)  
   - [Offers and Offer Types Performance Analysis](#offers-and-offer-types-performance-analysis)  
   - [Customer Segmentation Analysis](#customer-segmentation-analysis)  
   - [Channel Performance and View Rate Analysis](#channel-performance-and-view-rate-analysis)  
   - [Impact of Reward Size and Offer Durations](#impact-of-reward-size-and-offer-durations)  
   - [Offer Frequency Analysis](#offer-frequency-analysis)  
7. [Final Takes](#final-takes)  
---
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

### Offers and Offer Types Performance Analysis
**Discount** offers emerged as the most successful offer type, accounting for **18,000** completed offers (**53%** redemption rate). Among these, the **Discount-10-2-10** and **Discount-7-3-7** offers drove over **58%** of all completions for this offer type. **BOGO** offers also performed well, achieving a **47%** redemption rate, with **BOGO-5-5-7** and **BOGO-5-5-5** contributing to over **55%** of these redemptions.

![image](https://github.com/user-attachments/assets/65f804f7-702e-4f95-bd49-6d89039a7a4f)

### Customer Segmentation Analysis

**Baby Boomers** achieved the highest redemption rate, accounting for **37.02%** of all completed offers. Notably, Baby Boomers earning between $50k and $120k contributed **33.23%** of the total completed offers. Additionally, **Gen X** customers in the **$50k to $90k** **income range** contributed **20.15%** of completed offers. These groups have been highlighed as key segments for a more focused future promotional strategies. This includes **extended durations** to ensure ample time for these demographics, **partnership with products or services** that cater to these demographics, such as travel, wellness, or dining, and include relevant discounts. Also, **Regular feedback** and analysis from these groups will ensure continuous improvement.

![image](https://github.com/user-attachments/assets/88e22579-759c-4a2b-8ebf-d8f47a84e872)

### Channel Performance and View Rate Analysis
Out of the **75.68%** of people who viewed the offers, **57%** completed them, highlighting the importance of channel performance analysis. **Web** platforms (e.g., Google, Bing) had the **highest redemption rate (67%)** despite a **72% view rate**. In contrast, **social media** platforms achieved a **93% view rate** but only a **50%** of these were fulfilled, demonstrating a ***stronger propensity for customers to fulfill offers viewed on web platforms***. This analysis is shown when you filter through the various channels

![image](https://github.com/user-attachments/assets/ec830e75-79a5-4618-8968-db4004a7ce71)

### Impact of Reward Size and Offer Durations

![image](https://github.com/user-attachments/assets/8a2f4b74-1f31-4886-ae87-126148235722)

### Offer Frequency Analysis
Offers sent every **3-4 days** resulted in a **50%** **increase** in **redemption rates** and a **16% boost** in **overall transactions (sales).** This puts into perspective the effectiveness of frequent promotions in order maintaining customer engagement and driving sales growth.

![image](https://github.com/user-attachments/assets/33c2a288-1d76-4119-9f20-1444bde30e27)


## FINAL TAKES
- **Offer Frequency**: Sending offers every 3-4 days led to significantly higher offer completions and transactions compared to weekly offers.
- **Duration & Redemption Rates**: Longer offer durations resulted in higher redemption rates, particularly with moderate rewards.
- **Customer Segments**: Baby Boomers earning over $50K are highly engaged and ideal for targeted future promotions.
- **Channel Effectiveness**: Social Media and Web channels had the highest offer views and conversions, making them crucial for future campaigns.

  ![image](https://github.com/user-attachments/assets/30769cb4-bf1b-4577-b9c2-dfdfeb0c44dd)


[Click for Live Dashboard](https://app.powerbi.com/groups/me/reports/4cab4b17-8d9f-42ee-b7ca-c7dbcec72fe9/df410caf5b1688659ee0?experience=power-bi) 
