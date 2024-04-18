# Case Study - Analyzing Sales Data Using Alteryx

## Problem Statement:
DC Industries (a fictitious company), a prominent retail department store operating across three regions in the USA, aims to leverage its sales data to enhance operational efficiency and maximize profitability. By analyzing their sales data comprehensively, they seek to address critical questions regarding sales performance, such as identifying the top 25 most profitable orders, determining the most lucrative day of the week, examining profitability variations across product categories and regions, and pinpointing the sub-categories contributing the most profit within each category.

## Data Used:
1. Two customer files containing orders by customers: Customer orders-west.xlsx and Customer orders-east.xlsx
   
<img width="1254" alt="Screen Shot 2024-04-18 at 10 50 58 AM" src="https://github.com/Twinkle-Rakesh-Jain/Sales-Data-Analysis-Using-Alteryx/assets/159181933/2b0d7aca-4b0f-4fbb-97c5-d0123782256b">


<img width="1253" alt="Screen Shot 2024-04-18 at 10 51 26 AM" src="https://github.com/Twinkle-Rakesh-Jain/Sales-Data-Analysis-Using-Alteryx/assets/159181933/da5530f3-9553-41fa-9189-b3a9f86abb87">

3. File listing the company regions by state: Regions.csv
   
<img width="1250" alt="Screen Shot 2024-04-18 at 10 51 33 AM" src="https://github.com/Twinkle-Rakesh-Jain/Sales-Data-Analysis-Using-Alteryx/assets/159181933/7d37e424-cbbd-432f-b146-22fa3469574c">


5. File containing detailed order information: Order details.xlsx
<img width="1253" alt="Screen Shot 2024-04-18 at 10 51 40 AM" src="https://github.com/Twinkle-Rakesh-Jain/Sales-Data-Analysis-Using-Alteryx/assets/159181933/89839b57-aa32-40f3-b938-a87d64f3d5d1">

## Step-by-Step Analysis:

### 1.Data Blending & Conversion:

1. Merged customer files, eliminated duplicate records, and incorporated region data to provide a comprehensive dataset.
   
2. Extracted the day of the week from order dates to facilitate analysis.
   
3. Generated regional counts for strategic insights.


<img width="1406" alt="Screen Shot 2024-04-17 at 9 19 13 PM" src="https://github.com/Twinkle-Rakesh-Jain/Sales-Data-Analysis-Using-Alteryx/assets/159181933/044b2730-f596-42da-9377-5be5f9c07923">


   
### 2.Data Transformations:

1. Standardized order details and streamlined data formats.

2. Pivoted payment mode data to enhance readability and interpretation.

3. Calculated profitability metrics and categorized profitability levels for in-depth analysis.

4. Integrated all relevant data into a consolidated master order file for streamlined analysis.

<img width="1408" alt="Screen Shot 2024-04-18 at 9 01 54 AM" src="https://github.com/Twinkle-Rakesh-Jain/Sales-Data-Analysis-Using-Alteryx/assets/159181933/7922cc41-a64d-49b5-b240-2814ecbaf52a">


### 3.Ready, Set, and Analyze:

1. Identified the top 25 most profitable orders to prioritize high-value transactions.

2. Analyzed sales patterns to determine the most profitable day of the week for targeted marketing efforts.

3. Explored profitability trends by product category and region to optimize resource allocation and marketing strategies.

4. Delved into sub-category performance to uncover niche opportunities for revenue growth.

<img width="1416" alt="Screen Shot 2024-04-18 at 9 59 25 AM" src="https://github.com/Twinkle-Rakesh-Jain/Sales-Data-Analysis-Using-Alteryx/assets/159181933/ebd6cbc4-389b-45ae-be3d-7a92086819f3">


## Applications of Alteryx in Real World:
1. Alteryx serves as a versatile platform for seamless data blending, preparation, and analysis, empowering businesses like DC Industries to unlock actionable insights.
   
2. Its efficient workflow processing capabilities enable rapid analysis, facilitating timely decision-making and strategic planning.
   
3. By automating repetitive tasks, Alteryx enhances productivity and frees up resources for strategic initiatives.
   
4. Alteryx's compatibility with various data formats facilitates seamless data exchange with other platforms, enabling cross-functional collaboration and comprehensive data-driven decision-making.
   
5. This project exemplifies the transformative impact of Alteryx in empowering organizations to extract actionable insights from complex datasets, enabling DC Industries to optimize sales strategies, enhance operational efficiency, and drive sustainable growth in a dynamic retail landscape.


