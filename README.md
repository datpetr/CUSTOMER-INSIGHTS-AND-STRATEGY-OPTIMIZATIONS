# **Customer insights and strategy optimizations**

## Abstract
Datsenko Petr

### **Abstract**
![image](https://github.com/user-attachments/assets/1532ba63-4da3-4600-bc5d-31bca7e59e53)

- **Objective:** Analyze US consumer behavior through demographics and purchasing patterns.
- **Visual Tools:**
  - Canvas maps visualize state-level differences in purchasing categories.
  - Bubble charts reveal patterns in purchase amounts across demographics.
- **Key Focus Areas:**
  - Age and gender correlations with purchasing patterns.
  - Impact of discounts and promotions on consumer decisions.
  - Influence of loyalty programs and subscription models.
  - Effects of shipping types and payment methods on review ratings and repeat purchases.
- **Outcome:** Derive strategic insights to optimize national marketing strategies based on consumer behavior insights.

### Exploratory Data Analysis

#### Variables Analyzed:
- Age
- Gender
- Purchase Amount (USD)
- Review Rating
- Subscription Status
- Frequency of Purchases

#### Descriptive Statistics and Interpretations:

| Variable               | Descriptive Statistics                           | Interpretation                                                                 |
|------------------------|---------------------------------------------------|---------------------------------------------------------------------------------|
| Age                    | Mean, Median, Standard Deviation, Min, Max        | Central tendency and spread of customer ages, providing insights into age distribution. |
| Gender                 | Count, Percentage                                 | Analysis of gender composition to understand demographic representation.         |
| Purchase Amount (USD)  | Mean, Median, Standard Deviation, Min, Max        | Central tendencies and spread of purchase amounts, identifying spending patterns. |
| Review Rating          | Mean, Median, Standard Deviation, Min, Max        | Assessment of average customer satisfaction levels based on review ratings.      |
| Subscription Status    | Count, Percentage                                 | Understanding prevalence of subscription services and implications for revenue.  |
| Frequency of Purchases | Mean, Median, Standard Deviation, Min, Max        | Evaluation of average customer purchase frequency, providing insights into engagement levels. |


### **Data Tidying and Cleaning Steps**

  - **Tool Used:** Tableau for meticulous data preparation.
  - **Task:** Identified and removed duplicate state entries from the "country.xlsx" file.
  - **Analogy:** Similar to a curator refining an art collection to ensure each piece contributes uniquely.
  - **Objective:** Ensure data clarity and uniqueness before proceeding with detailed analysis.

**Questions and Graphs**

![image](https://github.com/user-attachments/assets/b3973881-b0f0-41ea-8816-fc24c5c621aa)

**1. How do gender and location correlate with specific purchasing patterns, such as purchase amounts and preferred categories?**
- **Objective:** Investigate correlations between gender, location, and purchasing patterns.
- **Tools Used:**
  - Interactive map: Provides visual insights into geographic consumer behavior.
  - Stacked bar charts: Display gender-specific preferences and purchase amounts.
- **Visualization Benefits:**
  - Dynamic exploration: Hover over states to reveal detailed stacked bar charts.
  - Insights: Uncover nuanced consumer behaviors and preferences.
  - Comprehensive understanding: Goes beyond traditional data analysis to depict complex purchasing patterns.
- **Outcome:**
  - Enhanced understanding of gender-specific purchasing behaviors across diverse geographic locations.
  - Illustrates the interplay between gender, location, and specific purchasing categories through vivid visual representations.


**2. How do factors like the color, size of purchased items, and age vary with customer demographics?**

![image](https://github.com/user-attachments/assets/8b0ec0f5-f63b-4cd5-b1ea-2fc073a359c2)

- **Objective:** Explore age trends and product preferences using a packed bubble chart.
- **Tools Used:**
  - Packed bubble chart: Utilized for advanced visualization of consumer demographics.
- **Visualization Benefits:**
  - Detailed insights: Highlights dominant color choices and popular product sizes.
  - Nuanced understanding: Reveals interactions between age groups and product preferences.
- **Outcome:**
  - Unveils top color preferences like shades of gray and white.
  - Highlights popular product sizes such as throw sizes.
  - Provides insights into how age influences consumer choices and preferences.


**3. How influential are discounts and promotional codes in influencing customer purchasing decisions? Do specific demographics or customer segments respond more to these promotions?**

![image](https://github.com/user-attachments/assets/369ed1ab-a196-4710-b60e-a3d4aa817cc0)

- **Objective:** Investigate the influence of discounts and promotional codes on consumer purchasing decisions.
- **Tools Used:**
  - Side-by-side bar chart: Used for visual representation of category preferences and purchasing dynamics.
- **Visualization Benefits:**
  - Insights into category preferences: Highlights dominance and unexpected preferences.
  - Reveals consumer engagement dynamics: Shows effects of promotions on purchasing behavior.
- **Outcome:**
  - Detailed understanding of promotional strategy effectiveness.
  - Nuanced insights into consumer decision-making across demographics.
  - Challenges preconceived notions about consumer behavior and promotions.


**4. How do the shipping type and payment method preferences vary among customer segments? Does the choice of shipping type affect the review ratings or repeat purchase behavior?**

![image](https://github.com/user-attachments/assets/7df85ee1-fd24-4e8d-a544-a195a1a409e5)

- **Objective:** Explore shipping type and payment method preferences across customer segments.
- **Tools Used:**
  - Heatmap: Visualizes relationships between review ratings, shipping types, and payment methods.
- **Visualization Benefits:**
  - Reveals nuanced relationships: Shows how shipping and payment choices affect review ratings.
  - Highlights gender-based differences: Illustrates varying satisfaction levels among male and female customers.
- **Outcome:**
  - Enhanced understanding of customer preferences and perceptions.
  - Insights into the impact of shipping and payment choices on review ratings.
  - Provides data-driven insights for optimizing customer experience strategies.


**5. How do review ratings correlate with repeat purchases, subscription status, and demographic factors? Can customer feedback be used to predict future purchasing behavior or preferences?**

![image](https://github.com/user-attachments/assets/1ff68c94-da33-4438-808c-ddb84f5f3629)

- **Objective:** Explore correlations among review ratings, repeat purchases, subscription status, and demographics.
- **Tools Used:**
  - Network diagram: Chosen for visualizing complex relationships.
- **Visualization Benefits:**
  - Clear representation of correlations: Illustrates connections between variables.
  - Focus on geographic variations: Highlights how subscription status affects ratings across locations.
- **Outcome:**
  - Enhanced understanding of customer interactions and preferences.
  - Insights into the influence of subscription status on review ratings.
  - Provides strategic insights for future marketing and customer engagement strategies.

**6. What are the patterns in purchase amounts across different customer segments, product categories, and locations? How do these patterns relate to the frequency of purchases and customer lifetime value?**

![image](https://github.com/user-attachments/assets/ca7b3b73-8b46-4b55-b439-54ee9cc076b0)

- **Objective:** Explore purchase patterns and item popularity using a waterfall chart.
- **Tools Used:**
  - Waterfall chart: Chosen for visualizing purchase amount distribution.
- **Visualization Benefits:**
  - Illustrates uniformity in purchase quantities across items.
  - Provides cumulative totals for purchased items, aiding in data interpretation.
- **Outcome:**
  - Insights into consumer behavior related to purchase amounts.
  - Guidance for strategic decisions based on purchase patterns.

**7. How do categories relate to shipping types and purchases? Is there a connection between choosing a specific category and a particular type of delivery?**

![image](https://github.com/user-attachments/assets/9faf00d7-4d21-4063-9441-e2fa901cb402)

- **Objective:** Explore connections between item categories, shipping preferences, and purchasing behavior using a Sankey diagram.
- **Tools Used:**
  - Sankey diagram: Chosen for visualizing complex relationships.
- **Visualization Benefits:**
  - Visualizes balanced distribution of purchased items across categories and delivery types.
  - Emphasizes high-value transactions for detailed analysis.
- **Outcome:**
  - Insights into consumer decision-making regarding item selection and delivery preferences.
  - Comprehensive view of correlations between item categories and shipping methods.
### **Dashboard**

![image](https://github.com/user-attachments/assets/4e622f18-519c-405c-9012-6a72611e3885)

![image](https://github.com/user-attachments/assets/36d1ca10-eee2-4785-a470-be52d29f11e6)

- **Objective:** Develop a comprehensive dashboard to analyze customer demographics, age trends, shipping methods, payment preferences, and promotional impacts.
- **Tools Used:**
  - Dashboard interface integrating multiple data sources.
- **Visualization Benefits:**
  - Enables exploration of diverse state-specific trends.
  - Facilitates insights into consumer behaviors and preferences.
- **Outcome:**
  - Holistic view of purchasing patterns across different variables.
  - Efficient navigation and comprehension of extensive data.

### **Conclusion:**

Through our journey in the "Customer Insights and Strategy Optimizations" project, we explored a diverse array of data using stacked bar charts, bubble charts, side-by-side bar charts, network diagrams, heatmaps, Sankey diagrams, and waterfall charts. These visualizations uncovered insights into customer preferences, seasonal purchasing patterns, discount influences, loyalty through subscriptions, and correlations between shipping methods, payment preferences, and customer satisfaction. Our discoveries guide strategic improvements and underscore the importance of data-driven decision-making.
