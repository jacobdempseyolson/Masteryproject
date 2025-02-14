

# **TravelTide Rewards Program & User Data Analysis**  

Welcome to the **TravelTide Rewards Program & User Data Analysis** repository. This project leverages advanced data analysis techniques to support the creation of a personalized rewards program while providing deep insights into customer behavior, engagement, and travel patterns. By integrating customer segmentation and SQL-based user analysis, the initiative delivers actionable insights to enhance marketing strategies, improve customer engagement, and drive loyalty.  

---  

## **Project Overview**  

This repository combines two critical initiatives for TravelTide:  

1. **Rewards Program Development**:  
   - The rewards program focuses on customer segmentation and perk customization, offering targeted rewards based on preferences and behaviors.  
   - Leveraging K-Means clustering, we identify distinct customer groups to design a multi-level rewards structure that aligns with individual needs.  

2. **User Data Analysis**:  
   - Using structured SQL queries, the project delves into customer demographics, booking habits, and travel trends.  
   - By categorizing users based on engagement and booking activity, TravelTide gains a granular understanding of its customer base, enabling precise marketing strategies.  

---  

## **Data Sources**  

The project is powered by data from several key sources:  

- **Users**: Includes demographics, signup information, and home locations.  
- **Sessions**: Captures user interactions, booking activity, and engagement metrics.  
- **Flights**: Provides insights into travel frequency, spending, and airline preferences.  
- **Hotels**: Analyzes hotel booking behavior, spending, and duration of stays.  
- **Engagement & Segmentation**: Focuses on calculating engagement scores and categorizing users.  

---  

## **Key Features**  

### **Rewards Program Development**  

- **Customer Segmentation**:  
   - K-Means clustering groups customers into distinct segments.  
   - Optimal cluster count is determined using methods like the **Elbow Plot** and **Silhouette Score**.  

- **Perk Customization**:  
   - Identifies perks most likely to resonate with specific customer groups, such as bonus miles, discounts, or exclusive offers.  
   - Suggests a multi-level rewards system (e.g., Silver, Gold, Platinum) to cater to varying levels of engagement and loyalty.  

- **Data-Driven Recommendations**:  
   - Provides clear, actionable steps for designing a tailored rewards program.  
   - Encourages targeted promotions and personalized incentives to enhance customer satisfaction.  

### **SQL-Based User Analysis**  

The SQL analysis uses Common Table Expressions (CTEs) to logically structure data before generating a final user-level report. Key components include:  

1. **User Demographics**: Extracts user details like age, gender, and home location, classifying them into meaningful categories.  
2. **Session Behavior**: Tracks session counts, average duration, booking ratios, and cancellations.  
3. **Flight and Hotel Trends**: Analyzes booking habits, spending, and travel preferences.  
4. **Lifetime Value Calculation**: Aggregates total spending on flights and hotels to compute user-level lifetime value.  
5. **Travel Frequency**: Measures trip counts and identifies active travel years.  
6. **Customer Engagement Scoring**: Assigns an engagement score based on booking activity, session data, and lifetime value.  
7. **User Segmentation**: Categorizes customers into High, Medium, or Low Bookers and further segments based on travel frequency and engagement.  

### **Final Output**  

The analysis culminates in a comprehensive user-level report, summarizing:  

- Demographics and location data.  
- Engagement metrics, session behavior, and booking patterns.  
- Spending trends and lifetime value.  
- User segments based on travel and booking activity.  

---  

## **Business Insights & Use Cases**  

### **For TravelTide**  

- **Targeting High-Value Customers**: Focus on high-value users with personalized incentives and rewards.  
- **Improving Engagement**: Address low-engagement users with tailored promotions.  
- **Optimizing Services**: Use travel trend insights to refine offerings and pricing strategies.  
- **Identifying Retention Risks**: Track low activity and cancellations to preempt churn.  

### **For Customers**  

- A rewards program that evolves with their preferences and behavior.  
- Access to perks and incentives tailored to their unique travel patterns.  

---  

## **How to Use**  


# User Data Analysis  
git clone https://github.com/jacobdempseyolson/Masteryproject/user-data-analysis.git  
```  

### **2. Install Dependencies**  

For the rewards program, install dependencies with:  
```bash  
pip install -r requirements.txt  
```  

For SQL analysis, use a compatible database system such as PostgreSQL or MySQL.  

---  

## **Future Improvements**  

- Incorporate **real-time data streaming** for dynamic insights.  
- Enhance segmentation with **machine learning models**.  
- Add analysis of **seasonal travel trends** and peak booking times.  

---  

## **Contributors**  

- **Jacob Dempsey-Olson**: Data Analyst & SQL Developer.  
- **Your Name**: Rewards Program Designer & Data Scientist.  

---  

This project delivers a robust combination of advanced analytics and customer segmentation, laying the groundwork for a data-driven rewards program that fosters loyalty and satisfaction.
