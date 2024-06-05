# National Rail Exploratory Analysis

## Executive Summary

This report provides an exploratory analysis of National Rail's operational data to help identify the most popular routes, determine peak travel times, analyze revenue from different ticket types and classes, and diagnose on-time performance along with contributing factors. The findings aim to inform strategic decisions to enhance service efficiency, optimize scheduling, and improve customer satisfaction.


## About Database

This data was provided by Maven Analytics (https://maven-datasets.s3.amazonaws.com/UK+Train+Rides/UK+Train+Rides.zip).


| Data Structure          | Number of Records                       | Number of Fields      |
| :---------------------- | :-------------------------------------- | :---------------------|
| Single Table            | 31,653                                  | 18                    |


## Challenge Objective

1. Identify the most popular routes
2. Determine peak travel times
3. Analyze revenue from different ticket types & classes
4. Diagnose on-time performance and contributing factors

### Approach Used

##Power BI Analysis

1. **Data Preparation:** 

> 1. Data Source: Import the provided CSV file into Power BI.
> 2. Data Cleaning: Use Power Query to clean and transform the data, ensuring consistency in date formats, handling missing values, and removing duplicates.
> 3. Data Creation: Create a date table using DAX
> 4. Data Modeling: Establish relationships between different tables 
> 5. Calculations: Create necessary calculated columns and measures using DAX for metrics like total trips, average delays, and revenue.

2. **Dashboard Creation:**

> 1. Key Metrics and KPIs

> 2. Visualization Layout (Report and sample Tickets)
* Use scatter plots to visualize the relationship between delays and revenue.
* Create trend lines to illustrate correlations and to show revenue growth over time..

> 3. Interactivity and Drill-Down on charts for detailed insights (e.g., drilling down from overall revenue to revenue by ticket type).

### Operational Analysis

The operational analysis focuses on identifying the most popular routes, determining peak travel times, and diagnosing on-time performance along with contributing factors. The goal is to optimize train schedules, manage passenger flow efficiently, and enhance service reliability.

#### Key Insights

1. Most Popular Routes:

> Manchester Piccadilly to Liverpool Lime Street, London Euston to Birmingham New Street, and London Kings Cross to York are the top routes by frequency.
> Increasing capacity and frequency on these routes can enhance service efficiency and customer satisfaction. Strategic investment in infrastructure on these routes can yield high returns due to concentrated demand.
> The following routes are the most utilized by passengers:
>* Manchester Piccadilly to Liverpool Lime Street: 4628 trips
>* London Euston to Birmingham New Street: 4209 trips
>* London Kings Cross to York: 3922 trips
>* London Paddington to Reading: 3873 trips
>* London St Pancras to Birmingham New Street: 3471 trips

2. Peak Travel Times:

> Peak travel times are identified in the early morning (06:00-07:00) and evening (17:00-18:00), indicating rush hour periods.
> Adjusting schedules to add more trains during peak hours can reduce congestion and improve service levels. Off-peak promotions could help spread demand more evenly, optimizing resource use.
>High-frequency travel times are:
>*06:00-07:00: 3112 trips
>*17:00-18:00: 3113 trips
>*18:00-19:00: 2888 trips
>*08:00-09:00: 2301 trips
>*16:00-17:00: 2179 trips

3. On-time Performance and Delay Analysis:

> The overall on-time performance is 86.82%.
> Addressing the root causes of delays to uncover operational bottlenecks and efficiency issues, such as technical issues or weather-related disruptions, through targeted investments and operational improvements can enhance reliability and passenger satisfaction.
> Major Delay Reasons:
>*Weather: 995 instances
>*Technical Issues: 707 instances
>*Signal Failures: 523 instances
>*Staffing Issues: 410 instances
>*Traffic: 314 instances

> Routes with Highest Delays:
>*Liverpool Lime Street to London Euston: 780 delays
>*Manchester Piccadilly to Liverpool Lime Street: 354 delays
>*London Euston to Birmingham New Street: 242 delays
>*Manchester Piccadilly to London Euston: 240 delays
>*London Kings Cross to York: 131 delays

#### Recommendations
1. Service Optimization:
* Enhance capacity on high-frequency routes, especially during peak times.
* Implement targeted infrastructure upgrades and maintenance on key routes with high delay frequencies.

2. Operational Improvements:
*Strengthen technical support and maintenance protocols to reduce delays caused by technical issues and signal failures.
*Improve weather resilience measures and enhance communication systems to manage weather-related disruptions effectively.

### Financial Analysis

The financial analysis aims to examine revenue from different ticket types and classes to identify opportunities for revenue optimization and growth. The focus is on enhancing profitability through strategic pricing and promotional efforts.


#### Key Insights

1. Revenue Contribution by Ticket Classes and Ticket Types:

> Standard class and Advance ticket types generate the highest revenue.
> Advance and Anytime tickets are the primary revenue drivers.
> Revenue contributions are as follows:
>* First Class: £149,399
>* Standard: £592,522
> Revenue from Ticket Types:
>* Advance: £309,274
>* Anytime: £209,309
>* Off-Peak: £223,338
> Standard class tickets significantly outpace first class in revenue, indicating a higher volume of standard class passengers. Focusing marketing and promotional efforts on high-revenue ticket classes and optimizing pricing strategies can boost overall revenue. While offering premium services or amenities can justify higher prices in first class, increasing profitability.

2. Revenue Trends Over Time:

> Analyzing revenue trends over different periods helps in identifying seasonal variations and growth patterns.
> Implementing dynamic pricing and targeted promotions during high-demand seasons can maximize revenue. Additionally, understanding off-peak periods can guide discount strategies to maintain steady revenue streams.

3. Correlation Between Operational Efficiency and Revenue:

> Delays and on-time performance can significantly impact customer satisfaction and ticket sales.
> Enhancing operational efficiency by reducing delays can lead to increased repeat business and higher revenue. Investments in technology and infrastructure that improve reliability can offer significant economic benefits in the long run.


#### Strategic Recommendations
1. Optimize Resource Allocation:
* Operational: Increase train frequency and capacity on the most popular routes during peak travel times.
* Financial: Allocate marketing budget towards promoting high-revenue ticket types and classes, and consider implementing dynamic pricing models.Analyzing customer purchasing behavior to fine-tune ticket pricing and identify opportunities for premium pricing on high-demand routes and times.

2. Enhance Customer Experience:
* Operational: Focus on improving on-time performance by addressing key delay factors through investments in infrastructure and technology.
* Financial: Enhance service offerings in first class and consider introducing bundled ticket options to encourage higher spending per transaction.

3. Invest in Infrastructure:
* Operational: Prioritize infrastructure improvements on high-demand routes and during peak times to reduce congestion and delays.
* Financial: Infrastructure investments should be evaluated based on their potential to increase operational efficiency and long-term revenue growth.

4. Implement Data-Driven Strategies:
* Operational: Use data analytics to continuously monitor and improve service efficiency and passenger satisfaction.
* Financial: Leverage revenue data to fine-tune pricing strategies and promotional campaigns, ensuring they align with demand patterns.


**Conclusion:**

By integrating these insights, National Rail can enhance both operational efficiency and financial performance. The focus should be on optimizing high-demand routes, improving on-time performance, and strategically targeting revenue growth opportunities through data-driven decision-making. This balanced approach will ensure sustained growth and customer satisfaction, positioning National Rail as a leading service provider in the passenger train industry.

## Power BI Dashboard results are summarized for executive stakeholders to easily digest all the results and recommendations that came from the report.


## Code

For the rest of the code, check the queries ()