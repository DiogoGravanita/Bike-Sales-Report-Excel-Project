# Bike Sales Report Excel Dashboard Project


## Introduction:

This project aims to showcase a comprehensive analysis of bike sales data using Microsoft Excel. Through a series of data cleaning, manipulation, and visualization techniques, we delve into understanding the factors influencing bike purchases.

The dataset comprises various demographic and behavioral attributes of customers, including marital status, gender, income, education, occupation, and more. By leveraging Excel's powerful features such as pivot tables, charts, and dashboards, we uncover insights to inform strategic decisions for marketing and sales efforts.

<br/><br/>

## Project Overview

### Data Source

The dataset used for this analysis is the "Bike Sales.xlsx" file.

### Objectives

 1. Identify Customer Segments: Analyze demographic variables such as age, gender, marital status, and education to segment customers based on their characteristics and preferences.

 2. Understand Purchase Behavior: Investigate factors influencing bike purchases, including income level, number of children, occupation, and commute distance.

 3. Visualize Trends and Patterns: Utilize visualizations such as pivot tables, charts, and graphs to visualize trends in bike sales over time and across different customer segments.

 4. Optimize Marketing Strategies: Gain insights into the most effective marketing channels and strategies for targeting specific customer segments, thereby optimizing marketing efforts and maximizing ROI.

<br/><br/>


## Charts and Visualizations:

Our analysis will be brought to life through a diverse array of charts and visualizations, meticulously crafted to captivate and elucidate:



1. Illustration of Average Income Trends in Relation to Purchases.
2. Insightful Depiction of Age Categories in Correlation with Purchases.
3. Visual Representation of Home Ownership Status and Its Impact on Purchasing Behavior.
4. Occupation Analysis Highlighting Purchase Patterns.
5. Exploration of Purchase Behavior Across Different Car Ownership Levels.
6. Mapping Commute Distances Against Purchase Decisions for Deeper Understanding.




<br/><br/>

<br/><br/>

## Tools and Technologies:

 - Microsoft Excel for Data cleaning and dashboard creation

<br/><br/>

## Data Cleaning and Standardization:
<br/><br/>



### Setting the Stage:

Established dedicated sheets in Excel: Dashboard, Pivot Table, and Working Sheet, ensuring a structured approach to data analysis.

<br/><br/>



### Clearing Duplicates:

Utilized Excel's Data field function to effortlessly eliminate duplicate rows, streamlining the dataset and ensuring accuracy.

<br/><br/>

### Standardizing Marital Status and Gender:

Recognized single-letter entries in Marital Status and Gender fields, enhancing clarity and coherence by standardizing to full-word representations: "Married," "Single," "Female," and "Male."

<br/><br/>


### Data Type Correction and Decimal Reduction:

Transformed the Income column to the appropriate data type, Currency, and streamlined its presentation by reducing decimal values to enhance readability and precision.

<br/><br/>

### Age Bracket Creation:

Introduced a new column to categorize ages into meaningful brackets, facilitating visual analysis and interpretation for better insights.


```excel
=IF(L2>60, "Old Adults",  IF(L2>39, "Middle Age Adults",  IF(L2<=39, "Young Adults", "Invalid")))
```


## Pivot Table Creation and Enhancement:
<br/><br/>

### Ensuring Correct Sorting in Charts:

Detected and rectified sorting discrepancies within the commuting distance category, optimizing visualization accuracy and clarity by standardizing entries to ensure logical sorting.
<br/><br/>

### Pivot Table Generation and Visualization:

Leveraged Pivot Tables to distill complex data into digestible insights, followed by the creation of visually engaging graphical representations, fostering comprehensive analysis and understanding.

<br/><br/>

### Intuitive Interaction with Slicers:

Implemented Slicers for seamless interaction with visualizations, empowering users to dynamically explore and analyze data with ease and precision.

<br/><br/>



<br/><br/>

By meticulously refining and structuring the dataset and employing advanced Excel functionalities, we've laid the groundwork for a comprehensive and insightful data analysis journey.


<br/><br/>

## Data visualization:

### Summary of Dashboard Insights

1. Average Income by Purchase:
Insight: The bar chart reveals the average income levels among customers based on their purchase behavior.
Implication: Understanding income distribution can inform pricing strategies and targeted marketing efforts tailored to different income brackets.

3. Age Category by Purchase:
Insight: This bar chart illustrates the distribution of purchases across different age categories.
Implication: Identifying age group preferences can guide product development and marketing campaigns tailored to specific age demographics.

5. Home Owner by Purchase:
Insight: The stacked bar chart showcases the proportion of home owners and non-home owners among bike purchasers.
Implication: Insights into home ownership status can inform housing-related marketing strategies and product offerings.

7. Purchase by Occupation:
Insight: This bar chart delineates purchasing behavior across various occupations.
Implication: Understanding occupation-based purchasing patterns can tailor marketing messages and product features to different professional segments.

9. Purchase by Number of Cars Owned:
Insight: The line chart tracks purchase trends in relation to the number of cars owned by customers.
Implication: Insights into car ownership influence can help refine targeting strategies and develop product features catering to specific transportation needs.

11. Commute Distance by Purchase:
Insight: This line chart illustrates purchase behavior relative to commute distances.
Implication: Understanding commuting habits can inform decisions regarding product distribution and promotional strategies tailored to different commuting preferences.

Interactive Slicers:
Region, Marital Status, and Education Degree: Utilize the intuitive slicer buttons to dynamically filter and analyze data based on specific regions, marital statuses, and education degrees, empowering users to extract targeted insights tailored to their preferences and needs.


<br/><br/>

By leveraging the comprehensive insights provided by the diverse array of charts and interactive slicers, stakeholders can make informed decisions and devise targeted strategies to drive business growth, enhance customer engagement, and optimize marketing efforts in the dynamic landscape of bike sales.

<br/><br/>

<br/><br/>


## Dashboard image:
<br/><br/>

<br/><br/>
![image](https://github.com/DiogoGravanita/Bike-Sales-Report-Excel-Project/assets/163042130/81c3d93e-d6be-4f6d-a099-8cf634fc9099)

<br/><br/>


<br/><br/>
<br/><br/>
# Results/findings

<br/><br/>
### Illustration of Average Income Trends in Relation to Purchases:

Insight: On average, individuals who purchased bikes exhibit a higher income, approximately $3,000 to $4,000 more than non-buyers.
Implication: The positive correlation between higher income and bike purchases suggests that bikes may be perceived as a discretionary purchase among more affluent demographics.

<br/><br/>

### Insightful Depiction of Age Categories in Correlation with Purchases:

Insight: Middle age adults demonstrate the highest propensity for bike purchases, followed by young adults, while old adults exhibit minimal purchasing behavior.
Implication: Tailored marketing efforts and product features catering to the preferences and lifestyles of middle age and young adults could potentially drive sales and engagement in these demographic segments.

<br/><br/>

### Visual Representation of Home Ownership Status and Its Impact on Purchasing Behavior:

Insight: The proportion of bike purchasers among home owners and non-home owners appears comparable, indicating a balanced distribution in purchasing behavior.
Implication: Further investigation may be required to ascertain the nuanced relationship between home ownership status and bike purchases, potentially uncovering hidden factors influencing purchasing decisions.

<br/><br/>

### Occupation Analysis Highlighting Purchase Patterns:

Insight: Professionals exhibit the highest ratio of bike ownership, followed by clerical workers and manual laborers.
Implication: Understanding occupation-based purchasing patterns can inform targeted marketing strategies tailored to specific professional segments, maximizing engagement and conversion rates.

<br/><br/>

### Exploration of Purchase Behavior Across Different Car Ownership Levels:

Insight: Individuals owning two cars demonstrate the highest propensity for bike purchases, followed by single car owners, while those with three or four cars exhibit minimal purchasing behavior.
Implication: Targeted marketing campaigns emphasizing the convenience and environmental benefits of biking as an alternative transportation mode could resonate particularly well with individuals owning multiple cars.

<br/><br/>

### Mapping Commute Distances Against Purchase Decisions for Deeper Understanding:

Insight: The majority of bike owners have a commute distance of 0-1 mile, with a significant drop-off in purchasing behavior observed beyond this range.
Implication: Tailoring promotional efforts and product offerings to address the needs and preferences of short-distance commuters could effectively capture a substantial portion of the bike market.


<br/><br/>

## Conclusion:

The comprehensive analysis of various demographic and behavioral factors reveals nuanced insights into the dynamics of bike purchasing behavior. It's noteworthy that on average, individuals in Europe demonstrate a higher propensity for bike purchases compared to other regions, suggesting cultural and infrastructural influences at play. Additionally, single individuals exhibit a higher percentage of bike ownership compared to married individuals, indicating potential lifestyle preferences and mobility needs. By leveraging these findings, stakeholders can develop targeted strategies to enhance customer engagement, optimize marketing efforts, and drive business growth in the competitive landscape of bike sales.
