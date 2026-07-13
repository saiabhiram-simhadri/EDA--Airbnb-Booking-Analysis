# EDA--Airbnb-Booking-Analysis
An exploratory data analysis conducted on Airbnb booking data

# Input Files
- Airbnb_analysis.csv - The listing details of around 49k providing information of various aspects of booking.

# Introduction

AirBnb dataset has listings of over thousands of customers, it provides crucial information about the hosting and market demands of different property types across all boroughs in New York City.
Analyzing these listings data can uncover valuable insights into how hosts can manage properties based on type and where they located, to optimize the amenities and pricing for maximizing the revenue thus creating profitable margins.

This project performs a comprehensive Exploratory Data Analysis (EDA) on this data to uncover key drivers of rental success in NYC. The analysis pipeline covers data wrangling and follows systematic approach with UBM (Univariate, Bivariate, Multivariate) to process and reveal insights.

## Dataset Features
 - id
 - name
 - host_id
 - host_name
 - neighbourhood_group
 - neighbourhood
 - latitude
 - longitude
 - room_type
 - price
 - minimum_nights
 - number_of_reviews
 - last_review
 - reviews_per_month
 - calculated_host_listings_count
 - availability_365

# Solution to Business Objective
1. ### Achieving Revenue Optimization (Pricing Strategy)
   
   **Target the $100–$200 bracket**: The initial distribution of pricing and the average price variation across boroughs and room types indicate the highly available price point is between this target range and could potentially lead to higher booking rates if listing is located in high demand area, generating consistent revenue and yielding better profit margins.

   **Exert a Premium for Entire Home/Apt**: Especially in Manhattan, proves that 'Entire Home/apt' properties usually command the ceiling of the market's pricing. So, hosts holding these specific assets should price aggressively above the standard borough median.

2. ### Achieving Market Position (Supply & Demand)

   **Differentiate the Offering**: Count plots indicate that marked supply is heavily saturated in Manhattan and Brooklyn, which means high competition for various price ranges, unless hosts of these properties differentiate their listings through unique guest experiences and services they may face fallback
   in bookings.
   
   **Capitalize on Underserved Boroughs**: Hosts can consider the less competitive markets in boroughs like Queens, Staten Island and Bronx to further expand their investments to capture though comparitively small market, there still exists a steady demand.

3. ### Achieving Enhanced Guest Experience
   
   **Lower the Minimum Night Barrier**: As seen from the stay type based listings and pricing plots, the more popular duration for the guests who are mostly the travellers is 'short term'. This particular stay type tends to stay in high demand all the time compared to higher stay durations. In the context of this data, hosts should consider lowering the stay duration if not completely at least for shorter term to revive poor performing listings that exhibits low bookings and review counts. This could potentially attracts frequent bookings which in turn triggers quicker feedback loops that supports the demand for higher occupancy rate.

   **Monitor Bookings and Feedback Metrics**: Establish proper monitoring system via hosting platform to flag the listings that gets almost zero bookings or when reviews per month falls to zero. This indicates that these properties are drifting out of market relevance, so knowing which listings are failing is the first thing to tackle the problem. By considering occational pricing discounts and improved descriptions can revive the listings into search results and increase visibility, leading to bookings.


# Conclusion
### Technical Framework and Execution

  This exploratory data analysis followed a structured data pipeline by pre-handling the dataset before analysis, which included handling of over 10k missing records in key review tracking metrics and resolving structural anomalies in descriptive based fields and optimizing the data types for efficient processing.

The analysis part was applied with a disciplined Univariate, Bivariate, and Multivariate (UBM) approach, uncovering insights in a sequential setting. Generated new fields based on existing parameters that further provided visibility into the underlying patterns of the market behavior towards different boroughs and properties.

### Final Strategic Impact

  By moving beyond basic, un-targeted plotting, this notebook bridges the gap between the raw data and strategic host positioning. The insights derived provide a overall picture for optimizing pricing, standardizing operations and tackling underperforming assets, to move towards generating a consistent revenue that yields better profit margins. This data-driven analysis serves as a decision making tool eliminating guesswork and allowing hosts and stakeholders to position their rentals for high growth and optimized revenue in a highly competitive and underserved markets.
