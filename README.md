# Happy Cow Sales Analysis

This project presents a comprehensive analysis of sales data from **Happy Cow Ice Cream’s** retail outlet on the University of Hong Kong (HKU) campus. The analysis was conducted using data extracted from multiple sources including a Word document (project brief and detailed analysis), an Excel file containing daily and monthly sales figures, and a PDF providing additional context and background on the company’s operations and market environment.

## Overview

Happy Cow Ice Cream, originally established by a pair of vegan entrepreneurs, has grown into a well-recognized brand in Hong Kong. Under the leadership of CEO Mary Schroeder, the company shifted its focus toward expanding its market share among local consumers. This analysis was undertaken to:
- Clean and restructure the raw sales data.
- Examine customer trends by segment (Students, Staff, and Tourists).
- Analyze flavor performance and seasonal trends.
- Generate actionable insights to support inventory management, promotional strategies, and future forecasting.

## Data Sources

- [**Happy Cow Sales Analysis.docx**](Happy_Cow_Sales_Analysis.docx)

    Contains the project background, standard assumptions, limitations, detailed sales analysis, and conclusions.

- [**Happy Cow Sales Analysis Reference Material.xlsx**](Happy_Cow_Sales_Analysis_Reference_Material.xlsx)

    Final, cleaned dataset with all relevant calculations and visualizations.

- [**Happy Cow Sales (Raw).xlsx**](Happy_Cow_Sales_Raw_File.xlsx)

    Original dataset with daily/monthly sales data before cleaning or restructuring.

- [**Happy Cow Ice Cream.pdf**](Happy_Cow_Ice_Cream.pdf) 

    Provides broader context on the company’s history, market positioning, customer segmentation, and retail operations at HKU, along with insights into competitive strategies and promotional events.

## Background & Objectives

The analysis was initiated after it became clear that the existing data required substantial cleaning and restructuring. The primary objectives were to understand:

1. **Who is buying?**  
   Identifying customer groups—students, staff, and tourists—and their purchasing behaviors.

2. **What is selling?**  
   Evaluating performance across different ice cream flavors and formats (e.g., single scoops versus multi-scoops), with a particular focus on the surprisingly zero revenue from tubs.

3. **When are purchases occurring?**  
   Analyzing time trends and seasonality, especially in relation to academic calendars and campus activity patterns.

## Standard Assumptions

- **Operational Days:**  
  Days with \$0 revenue (typically Sundays or scheduled closures) are assumed to represent full-day closures of the shop.
- **Customer Demographics:**  
  Given the campus location, the majority of transactions are assumed to involve students, with staff and tourists forming smaller segments.
- **Product Categorization:**  
  Flavors have been grouped into Regular, Summer, and Winter categories based on their revenue performance and seasonal trends.

## Analysis & Findings

### Sales Breakdown

- **Product Format Analysis:**
  - **Tubs:** Recorded \$0 in sales. The absence of tub purchases may indicate pricing or branding issues.
  - **Scoops:**  
    Analysis of single, double, and triple scoop transactions shows that multi-scoop orders (reflected by negative numbers due to discount adjustments) are marginal compared to the overall sales volume. The 6-month total revenue reached approximately \$273,857.

### Flavor Performance

- **Top Performing Flavors:**  
  Salted Caramel emerged as the top seller (~\$38,988 over 6 months), followed by Mango, Chocolate, Mint Chocolate, Pure Coconut, and Strawberry. These flavors, with average revenues well above the overall mean (around \$14,142 per flavor), are recommended to remain as regular offerings.

  ![image](https://github.com/user-attachments/assets/c959dd42-b2b2-445e-9b4b-83f09deec316)

- **Seasonal Adjustments:**  
  - **Summer Flavors:**  
    Mango and Pure Coconut consistently perform well during the summer months. Other flavors (e.g., Lime Coconut, Pina Colada) might be more successful as limited-time offerings to spark interest.

   ![image](https://github.com/user-attachments/assets/02e39251-027e-4d14-b22b-c4699dd48a13)

  - **Winter Flavors:**  
    Certain flavors, such as Vanilla Bean, underperform in the summer and could be repositioned as winter offerings to drive demand during colder months.
  
  ![image](https://github.com/user-attachments/assets/b85e7615-d5a2-484f-b83b-22786bc993eb)


### Customer Segment Trends

- **Students:**  
  Sales dip significantly near the end of April (start of summer break) and recover in September.
- **Staff:**  
  Sales peak in June and July, aligning with the gap between the spring and summer semesters.
- **Tourists:**  
  Although a smaller segment, tourist traffic can provide additional off-peak revenue opportunities and justify seasonal promotions.
  
(![image](https://github.com/user-attachments/assets/5ed22ed0-d9f2-45bd-b71f-49b2ec1d7161)

### Additional Insights (from the PDF)

The PDF details Happy Cow’s evolution and data-driven approach:
- **Company History & Expansion:**  
  Traces the brand’s journey from niche vegan origins to broader retail exposure under data-focused leadership.
- **Retail Store Dynamics:**  
  Explains the HKU store’s layout, promotional efforts, and its unique constraints (e.g., proximity to Starbucks, limited advertising).
- **Promotional Initiatives:**  
  Past collaborations (e.g., with Lush) highlight the potential benefits of aligned branding and targeted marketing.

## Recommendations

1. **Inventory Management:**  
   - Remove tubs from inventory due to consistent lack of sales.
   - Increase inventory of high-performing flavors (e.g., Salted Caramel, Mango) to match demand.
2. **Promotional Strategies:**  
   - Offer targeted discounts or bundles to staff in June and July to capitalize on peak staff traffic.
   - Run student-focused promotions during summer months to boost sales despite lower campus attendance.
3. **Seasonal Product Offerings:**  
   - Reposition slow-selling summer flavors as limited-time promotions to create scarcity and interest.
   - Introduce winter-exclusive flavors (or repurpose existing underperformers) to drive cold-weather sales.
4. **Data Collection:**  
   - Collect a full year’s worth of sales data to refine these insights and ensure seasonal coverage (especially for fall/winter months).
   - Reassess flavor performance after the full dataset is obtained.

## Limitations & Future Work

- **Data Limitations:**  
  Only 6 months (Spring/Summer) of data were available, mostly from a single campus-based location.
- **Scope for Future Analysis:**  
  - Capture an entire fiscal year to account for missing seasonal data.
  - Expand analysis to additional store locations.
  - Explore dynamic pricing or loyalty programs to further engage repeat customers.
