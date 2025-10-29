# E-Commerce User Activity Analysis

## Project Overview
This project analyzes activity logs from an e-commerce platform to understand user behavior and retention patterns. It covers funnel building, cohort analysis preparation, and retention tracking, with findings presented in a professional, easy-to-read format.

## Data Set
The dataset used for this analysis includes logs of user activities on the e-commerce platform. Each row represents an event, such as a product page view, shopping cart opening, or purchase, with the following columns:

- `user_id`: Unique customer ID
- `event_type`: Type of activity (e.g., page view, add to cart, purchase)
- `category_code`: Category of the product
- `brand`: Manufacturer of the product
- `price`: Price of the product in USD
- `event_date`: Date of user activity in YYYY-MM-DD format

## Project Link
[E-Commerce User Activity Analytis](https://docs.google.com/spreadsheets/d/1GqDN19U7kItK0lO4Mc5l-rx8eSj1FjeFdRhsEnA5eaQ/edit?usp=sharing)

## Introduction
As a new junior analyst at an e-commerce company, I was tasked with analyzing raw user activity logs to understand how customers interact with the website. The project focuses on building a conversion funnel, conducting cohort analysis, and calculating retention rates to uncover insights that improve engagement and conversions.

## Project Objectives

1. Build a conversion funnel to understand how well product page views convert into purchases.
2. Create acquisition cohorts based on the month of a user's first purchase and track retention month-by-month.
3. Calculate retention rates and summarize insights for each cohort.
4. Organize, document, and format the analysis for executive presentation.

## Methodology

1. **Conversion Funnel Analysis:** Built a conversion funnel in a pivot table to track user movement through three stages (views, adds to cart, and purchases). Calculated overall and next-step conversion rates.
2. **Cohort Preparation and Analysis:** Filtered the dataset to isolate purchase events and created acquisition cohorts based on the first purchase month. Monthly data columns were generated to track the age of each cohort, enabling detailed retention tracking.
3. **Retention Rate Calculation:** Aggregated the purchase data into cohorts and calculated retention rates for each cohort over a four-month period.
4. **Documentation and Formatting:** Summarized the results in an executive summary sheet, organized sheets for easy navigation, and formatted tables for readability.

## Visual Representations

### Conversion Funnel

This funnel shows how users interact with the website, from product views to purchases, and calculates conversion rates.

<img alt="Screenshot 2025-10-29 at 5 21 50 PM" src="https://github.com/user-attachments/assets/6cc95556-38ac-4f5d-8290-3c8a056cdadb" width="500" height="300"  />

### Retention Rates by Cohort

This visualization shows the retention rates across cohorts, helping to understand customer retention trends over time.

<img alt="Screenshot 2025-10-29 at 5 26 18 PM" src="https://github.com/user-attachments/assets/92abb045-f6bc-4b7b-8726-71fbe5f796a8" width="500" height="300" />

### Unique Users by Cohort

This chart represents the number of unique users for each cohort, calculated by month. It highlights the initial user engagement and retention patterns over time for each cohort, providing insights into cohort-based user retention and engagement.

<img alt="Screenshot 2025-10-29 at 5 27 44 PM" src="https://github.com/user-attachments/assets/6f655b48-bacd-40b9-9d5b-0f7a08588cb0" width="500" height="300" />

## Key Findings

- **Conversion Funnel:**
  - Out of 10,459 users, 10,453 viewed items, 3,036 added items to their cart, and 1,081 made a purchase.
  - Conversion rate from viewing to adding to cart: 29.04%.
  - Conversion rate from viewing to making a purchase: 10.34%.
  - Conversion rate from adding to cart to purchasing: 35.61%.
 
- **Retention Rates:**
  - **September 2020 cohort:** 12.50% purchased in the first month, 6.25% in the second, none in the third, and 3.13% in the fourth.
  - **October 2020 cohort:** 7.49% purchased in the first month, 3.74% in the second, 0.53% in both the third and fourth months.
  - **November 2020 cohort:** 5.46% purchased in the first month, 2.94% in the second, and 0.42% in the third.
  - **December 2020 cohort:** 4.43% purchased in the first month and 2.96% in the second.
  - **January 2021 cohort:** 6.87% purchased in the first month.

## Conclusion

The analysis highlights key areas for improvement in user experience and retention. Optimizing the checkout process could increase conversion rates, and targeted marketing could enhance customer retention.

## Recommendations for Improvement

- **Reduce Drop-Off at Checkout:** Implement strategies such as simplifying the checkout process, offering discounts for completing purchases, or providing reminders for abandoned carts.
- **Engagement Strategies for New Users:** Create targeted engagement campaigns to encourage repeated visits within the first month after purchase, potentially increasing retention rates.

## Future Directions

1. **Advanced Funnel Analysis:** Further break down conversion rates by product categories or brands to understand specific product performance.
2. **User Segmentation Analysis:** Segment users based on spending patterns, frequency of visits, or other demographic factors to tailor marketing efforts.
3. **A/B Testing for Checkout Process:** Conduct A/B tests on different checkout experiences to identify the most user-friendly design.

---

This project provides valuable insights into user engagement and retention patterns, and the recommendations presented are aimed at helping the company drive better customer retention and improve the overall shopping experience.



