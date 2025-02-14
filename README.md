# TravelTide Rewards Program & User Data Analysis

Welcome to the **TravelTide Rewards Program & User Data Analysis** repository. This project combines advanced data analysis techniques and personalized rewards strategies to enhance customer engagement, drive loyalty, and improve marketing strategies. By leveraging customer segmentation and SQL-based user analysis, we gain insights into customer behavior, engagement, and travel patterns, laying the foundation for a targeted rewards program.

## Project Overview

This repository includes two key initiatives for **TravelTide**:

### 1. **Rewards Program Development**
- The rewards program aims to offer personalized rewards based on customer preferences and behavior.
- Using **K-Means clustering**, distinct customer groups are identified, and perks are tailored to these segments.
- The rewards structure is designed with multiple tiers (e.g., **Silver**, **Gold**, **Platinum**) based on customer engagement and loyalty levels.

### 2. **User Data Analysis**
- The project uses structured SQL queries to analyze customer demographics, travel habits, booking preferences, and engagement metrics.
- Users are segmented based on booking activity, session data, and lifetime value, enabling highly targeted marketing strategies.

## Data Sources

The data used in this project comes from several key sources:

- **Users**: Demographics, sign-up information, and home locations.
- **Sessions**: Tracks user interactions, booking activities, and engagement metrics.
- **Flights**: Insights into travel frequency, spending, and airline preferences.
- **Hotels**: Analyzes hotel booking patterns, spending, and stay duration.
- **Engagement & Segmentation**: Calculating engagement scores and categorizing users based on behavior.

## Key Features

### **Rewards Program Development**
- **Customer Segmentation**: K-Means clustering is used to group customers into distinct segments. 
  - Optimal cluster count is determined with the **Elbow Plot** and **Silhouette Score**.
- **Perk Customization**: Based on customer group preferences, perks like bonus miles, discounts, and exclusive offers are customized.
  - A multi-level rewards system is proposed, offering Silver, Gold, and Platinum status with varying perks.
- **Data-Driven Recommendations**: Actionable steps to design a personalized rewards program that boosts customer satisfaction and loyalty.

### **SQL-Based User Analysis**
The SQL analysis generates insights into customer behavior, with several key analyses performed:
- **User Demographics**: Age, gender, and location data.
- **Session Behavior**: Session counts, durations, booking ratios, and cancellations.
- **Flight and Hotel Trends**: Booking habits, spending, and travel preferences.
- **Lifetime Value Calculation**: Total spending on flights and hotels.
- **Travel Frequency**: Measures trip counts and active travel years.
- **Customer Engagement Scoring**: Engagement score based on booking activity and lifetime value.
- **User Segmentation**: Categorizes customers into High, Medium, or Low Bookers based on engagement and frequency.

### **Customer Segments & Rewards Program Tiers**

Using the user data analysis, customers are categorized into the following segments with corresponding rewards program tiers:

1. **Business Traveler**
   - **Platinum**: First Class Lounge Access, Free Airport to Hotel Transport, Priority Boarding, VIP Concierge Service
   - **Gold**: Priority Boarding, Free Hotel with Flight, Free Checked Bags
   - **Silver**: Priority Boarding, Free Hotel with Flight, Free Checked Bags
   - **Bronze**: Priority Boarding, Free Checked Bags

2. **Family Traveler**
   - **Platinum**: First Class Lounge, Free Airport to Hotel Transport, Kids Stay Free, Family Vacation Planning Service
   - **Gold**: Kids Stay Free, Family Vacation Planning Service, Free Hotel with Flight
   - **Silver**: Kids Stay Free, Free Hotel with Flight
   - **Bronze**: Kids Stay Free, Free Checked Bags

3. **Dreamers**
   - **Platinum**: First Class Lounge Access, First Booking Discount, Priority Boarding, Exclusive Offers
   - **Gold**: First Booking Discount, Free Hotel with Flight, Priority Boarding
   - **Silver**: First Booking Discount, Free Hotel with Flight
   - **Bronze**: First Booking Discount, Free Checked Bags

4. **Young Singles**
   - **Platinum**: First Class Lounge Access, Weekend Getaway Bonuses, Free Upgrade on Selected Flights
   - **Gold**: Weekend Getaway Bonuses, Free Hotel with Flight, Priority Boarding
   - **Silver**: Weekend Getaway Bonuses, Free Hotel with Flight
   - **Bronze**: Weekend Getaway Bonuses, Free Checked Bags

5. **Senior / Retired Traveler**
   - **Platinum**: First Class Lounge Access, Senior Discounts, Free Airport to Hotel Transport, Priority Boarding
   - **Gold**: Senior Discounts, Free Hotel with Flight, Priority Boarding
   - **Silver**: Senior Discounts, Free Hotel with Flight
   - **Bronze**: Senior Discounts, Free Checked Bags

6. **High Spender**
   - **Platinum**: First Class Lounge, Luxury Lounge Access, Suite Upgrade (Subject to Availability), Free Hotel with Flight
   - **Gold**: Luxury Lounge Access, Free Hotel with Flight
   - **Silver**: Luxury Lounge Access, Free Hotel with Flight
   - **Bronze**: Luxury Lounge Access, Free Checked Bags

### **Summary of Platinum Status Perks**:
Platinum status includes all Gold and Silver benefits with premium upgrades such as **First Class Lounge Access**, **Free Transportation**, and **Exclusive Upgrades** tailored to each customer type. This provides the highest level of convenience and luxury for frequent travelers.

---


