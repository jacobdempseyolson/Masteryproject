# User Data Analysis

## Overview
This project analyzes user behavior, engagement, and travel patterns using structured SQL queries. The analysis helps categorize users based on booking frequency and engagement, providing insights into customer behavior for targeted marketing and business strategies.

## Data Sources
The dataset consists of multiple tables, each providing specific information about users, their sessions, flights, hotels, and overall engagement:

- **Users**: Demographics, signup details, and home location.
- **Sessions**: User interactions, booking activity, and engagement metrics.
- **Flights**: Travel frequency, preferred airlines, and spending on flights.
- **Hotels**: Hotel stays, spending, and booking behavior.
- **Engagement & Segmentation**: Calculating engagement scores and categorizing users into meaningful segments.

## SQL Query Breakdown
The SQL query consists of several Common Table Expressions (CTEs) to structure the data logically before producing the final report.

### 1. User_Details
Extracts user demographic information and categorizes users based on age:

- Extracts user ID, gender, marital status, and birthdate.
- Calculates user age using the birthdate.
- Classifies users into age groups (Teenager, Young Adult, Middle-Aged, Senior).
- Extracts signup date and truncates it to the nearest month.
- Includes home location details, including city, country, and home airport.
- Checks for missing latitude/longitude in airport data.

### 2. Session_Data
Analyzes user session behavior:

- Counts the total number of sessions per user.
- Finds the first and last session for each user.
- Calculates the average session duration.
- Determines the booking ratio, i.e., sessions where a flight or hotel was booked.
- Computes average usage of flight and hotel discounts.
- Tracks total page clicks and cancellations.

### 3. Flight_Data
Evaluates flight booking trends:

- Counts total flights booked per user.
- Finds the average flight fare spent.
- Determines the user's preferred airline.
- Calculates average seats booked per trip.
- Counts total checked bags.
- Computes the average trip duration.

### 4. Hotel_Data
Examines hotel stay trends:

- Counts total hotels booked per user.
- Calculates the average hotel spending per room.
- Finds the average number of nights stayed per booking.
- Counts total rooms booked.

### 5. Lifetime_Value
Computes the lifetime value of each user:

- Summarizes total spending on flights and hotels.
- Uses `COALESCE` to handle missing data and ensure correct calculations.

### 6. Travel_Frequency
Tracks travel activity per user:

- Counts the total number of trips taken.
- Counts distinct active years based on session data.

### 7. Customer_Engagement
Measures user engagement using a weighted score:

- Booking ratio contributes **30%** to the engagement score.
- Total sessions contribute **40%** (normalized by the maximum total sessions).
- Lifetime value contributes **30%** (normalized by the highest lifetime value).
- Calculates average clicks per session.

### 8. Booking_Segment
Classifies users based on their booking activity:

- **High Bookers**: Booking ratio >= 50%.
- **Medium Bookers**: Booking ratio between 20% and 50%.
- **Low Bookers**: Booking ratio below 20%.

### 9. Travel_Engagement_Segment
Categorizes users based on travel frequency and engagement:

- **Frequent High Engagers**: 10+ trips and engagement score >= 0.7.
- **Frequent Medium Engagers**: 5+ trips and engagement score >= 0.5.
- **Occasional Low Engagers**: Less frequent travelers with lower engagement.

## Final Output
The final query aggregates all the processed data and generates a user-level report, including:

- **User demographics and location data.**
- **Session behavior**, including total sessions, session duration, and booking trends.
- **Flight and hotel booking statistics.**
- **Lifetime value estimation.**
- **User segmentation based on engagement and booking trends.**

## Business Insights & Use Cases
This analysis helps businesses:

- Target high-value customers with personalized offers.
- Improve engagement strategies for low-booking users.
- Analyze travel trends to optimize services and pricing.
- Identify potential retention risks by tracking cancellations and low engagement.

## How to Use
### Clone this repository:
```bash
git clone https://github.com/jacobdempseyolson/Masteryproject/user-data-analysis.git
```


### Analyze the output and use insights for business decision-making.

## Future Improvements
- **Incorporate real-time data streaming** for dynamic analysis.
- **Enhance segmentation** with machine learning models.
- **Add additional behavioral insights** like peak booking times and seasonal trends.

## Contributors
- **Jacob Dempsey-Olson** - Data Analyst & SQL Developer

