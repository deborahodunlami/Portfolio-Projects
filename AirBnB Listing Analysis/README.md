# Introduction:
This report presents a detailed analysis of Airbnb listings in Paris, concentrating on host activity, pricing distribution, and the effect of rules implemented in 2015. The analysis aims to identify patterns and insights that might be useful to prospective hosts, guests, and policymakers.
# Dataset Overview:
The dataset consists of 279,712 entries with 33 columns, including attributes like *listing_id*, *host_id*, *host_since*, *host_location*, *neighbourhood*, *city*, *price*, and various review scores.
# Data Preparation and Cleaning:
- **Encoding and Memory Management:** The data was read with the specified encoding *ISO-8859-1* and *low_memory=False*.
- **Missing Values:** Significant missing values were found in columns like *district*, *host_response_time*, and review scores.
- **Date Conversion:** The *host_since* column was converted to datetime format.
# Analysis and Findings:
**Missing Values Analysis**
-	Columns such as *district*, *host_response_time*, and review scores had a high percentage of missing values, which could affect analysis accuracy.

**Listing Analysis**
-	**Neighborhood Distribution:** Certain neighborhoods like Buttes-Montmartre and Elysee have a higher concentration of listings, likely due to their popularity and central location.
-	**Price Distribution:** Prices vary widely, with most listings in the lower price range, but some outliers exist with extremely high prices.

**Review Scores Analysis**
-	Review scores are generally high, indicating positive guest experiences. Most scores cluster around 8-10.

**Correlation Analysis**
-	Strong positive correlations exist between various review scores, suggesting that high ratings in one aspect often correlate with high ratings in other aspects.

**Impact of 2015 Regulations**
**-	New Hosts:** The growth rate of new hosts slowed down slightly after 2015, suggesting that the regulations introduced some barriers for new hosts.
**-	Average Price:** There was a noticeable dip in average prices around 2015, indicating that the regulations might have temporarily stabilized or reduced prices.  
# Detailed Insights:
**Neighborhood Price Analysis**  
&nbsp;&nbsp;&nbsp;&nbsp; A table was created to show the mean price by neighborhood, sorted from low to high. This revealed significant price variations across different neighborhoods.  
  
**Accommodations in the Most Expensive Neighborhood**  
&nbsp;&nbsp;&nbsp;&nbsp; In the most expensive neighborhood, a table was created to show the mean price by the number of accommodates. Prices tend to increase with the number of accommodates, reflecting the higher cost for larger properties.  
  
**Hosts Over Time**  
&nbsp;&nbsp;&nbsp;&nbsp; A table and dual-axis line chart were created to show the count of new hosts and average price over time. This highlighted trends before and after the 2015 regulations.  
# Visualization Highlights:
- **Horizontal Bar Charts:** Showed the average price by neighborhood and by accommodates in the most expensive neighborhood.  
- **Line Charts:** Illustrated trends in the count of new hosts and average prices over time, providing a clear view of the market dynamics.
# Conclusion:
The analysis of Airbnb listings in Paris reveals several key insights:
-	The 2015 regulations had a noticeable impact, moderating the growth of new hosts and stabilizing prices temporarily.
-	Review scores are generally high, indicating positive guest experiences.
-	Significant variations exist in prices across different neighborhoods and accommodations, highlighting the diverse market.

This comprehensive analysis provides valuable insights for various stakeholders in the Airbnb market in Paris, offering a detailed understanding of trends, prices, and regulatory impacts. These findings can be leveraged to make informed decisions and strategies in the short-term rental market.
# Future Recommendations:
**1.	For Potential Hosts:**
-	Understand neighborhood dynamics and pricing trends to strategically list properties.
-	Consider the impact of regulations and market trends when entering the market.

**2.	For Policymakers:**
-	Monitor the long-term effects of regulations to balance market growth and housing availability.
-	Ensure regulations support a healthy, competitive market while protecting local housing needs.

**3.	For Market Analysts:**
-	Use the insights to predict future trends and advise stakeholders accordingly.
-	Continuously analyze market data to stay informed about changes and emerging patterns.
