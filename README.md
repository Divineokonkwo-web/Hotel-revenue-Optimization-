# Hotel-revenue-Optimization
### Table of Contents 

### Description
This project analyzes booking and cancellation data from SHG Hotel Group to uncover the root causes of revenue loss during peak summer months (July & August). By exploring booking patterns, cancellation behavior, and average daily rates, the study identifies opportunities to mitigate losses and boost revenue through smarter reservation strategies.

### Business Introduction 

SHG Hotel Group is a leading hospitality brand known for delivering exceptional guest experiences across multiple destinations. With a diverse portfolio of hotels and resorts, SHG caters to both leisure and business travelers, offering premium accommodations, personalized services, and state-of-the-art facilities.Over the years, SHG has built a reputation for excellence in the hospitality industry, consistently achieving high occupancy rates during peak travel seasons while maintaining competitive pricing strategies.

The group places strong emphasis on customer satisfaction, operational efficiency, and revenue growth, ensuring long-term value for both guests and stakeholders. As part of its continuous improvement efforts, SHG leverages data-driven decision making to understand booking behaviors, manage cancellations, and optimize pricing strategies. This commitment to innovation and analytics enables SHG Hotel Group to remain competitive in an increasingly dynamic and challenging hospitality market.

### Problem/Overview

SHG Hotel have outlined their pressing challenge related to customer retention, ss clarified below 

- High Revenue Loss from Cancellations – SHG Hotel Group lost around $1 million in revenue during the peak summer months (July & August) due to booking cancellations.

- Advance Bookings Risk – Reservations made well in advance have a higher cancellation rate (≈38%), creating uncertainty in occupancy forecasting.

- Missed Revenue Opportunities – Last-minute bookings (within 30 days) have lower cancellation rates (≈20%) and generate a higher average daily rate, but they are underutilized.

- Occupancy Management Challenge – Frequent cancellations lead to empty rooms that could otherwise generate income if managed with an effective overbooking or reallocation strategy.

  ### Aims of the analysis
  
- Identify key factors contributing to revenue loss from cancellations during summer months.

- Compare booking behaviors between advance reservations and same-month reservations.

- Evaluate the impact of cancellations on average daily rates and occupancy.

- Propose data-driven strategies that'll be efficient for revenue maximisation while maintaining customer retention.
  
  ### Procedure

  
1. Data Collection & Understanding

   - Obtained booking and cancellation records from SHG Hotel Group.

   - Reviewed fields such as reservation date, stay date, cancellation status, revenue, and average daily rate.

   - Understood seasonal trends with focus on summer months (July & August).



2. Data Cleaning & Preparation
   - Removed duplicates, handled missing values, and standardized date formats.

   - Created derived variables (e.g., booking lead time, cancellation flag, revenue loss amount).

   - Segmented data into advance bookings (>30 days) and same-month bookings (≤30 days).



3. Exploratory Data Analysis (EDA) using pivot tables 

   - Analyzed cancellation rates across months and booking lead times.

   - Compared average daily rates (ADR) between cancelled vs. non-cancelled bookings.
   - Visualized revenue gained vs. revenue lost due to cancellations.
   - Insights

Summer months (July & August) show the highest cancellation rates, causing ~$1M in lost revenue.

Advance bookings (>30 days): Higher cancellation rate (≈38%) and lower ADR ($169).

Same-month bookings (≤30 days): Lower cancellation rate (≈20%) and higher ADR ($191).

Unoccupied rooms remain a challenge due to mismatch between cancellations and replacement bookings.

### Insights

- Summer months (July & August) show the highest cancellation rates, causing ~$1M in lost revenue.

- Advance bookings (>30 days): Higher cancellation rate (≈38%) and lower ADR ($169).

- Same-month bookings (≤30 days): Lower cancellation rate (≈20%) and higher ADR ($191).

- Unoccupied rooms remain a challenge due to mismatch between cancellations and replacement bookings.

  ### Recommendations

- Implement controlled overbooking during peak summer to offset expected cancellations.

- Prioritize same-month reservations to secure higher revenue with lower cancellation risk.

- Offer non-refundable discounts or loyalty rewards for advance bookings.

- Maintain premium rates for reliable same-month bookings.

- Set up a cancellation monitoring system to track patterns and forecast risks.

