### RobustScaler performs scaling based on the median and interquartile range (IQR).
- More resistant to outliers than StandardScaler or MinMaxScaler.

### Filling NaN using KNN
- Brooklyn and Manhattan have the highest concentration of listings.
- ueens has a moderate density, while Bronx and Staten Island have fewer listings.
- Most listings are entire homes/apartments, followed by private rooms. Shared rooms have the lowest prices.
- Manhattan dominates pricing due to its premium location. Bronx and Queens are more affordable, Brooklyn and Staten Island are  mid-range.
- Entire home/apartment listings are the most expensive. Private rooms have an average price, and Shared rooms are the cheapest.

### Correlation Analysis
- Listings with higher availability tend to be booked more often.
- More frequent bookings lead to more reviews.
- Listings with more bookings generate higher minimum income.
- Longer stays (minimum_nights) correlate with more total booked days

### Visualizing Location Data Based on Neighbourhood Group and Room Type

### Price Distribution by Room Type in Neighbourhood Groups
Entire home/apartment listings dominate Manhattan. Private rooms are more widespread across all areas. Shared rooms are less common.

### Comparative Display of Median Monthly Reviews by Neighbourhood Group
- Bronx, Queens, and Staten Island have the highest median reviews per month (~1.75).
- Brooklyn and Manhattan have lower review rates (~1.25).

  ### Comparison of Minimum Stay Nights by Neighbourhood Group
- Manhattan has the highest median minimum stay (~6-7 nights).
- Brooklyn, Queens, and Staten Island have moderate minimum stays (~4-5 nights).
- Bronx has the lowest minimum stay (~3 nights).

### Comparison of Number of Reviews by Neighbourhood Group
- Queens has the highest median number of reviews (~30).
- Brooklyn, Bronx, and Staten Island follow with ~25 reviews on average.
- Manhattan has the lowest median number of reviews (~22-23) possibly due to higher prices and shorter stays.

### Comparison of Host Listing Counts by Neighbourhood Group
- Manhattan hosts tend to have the highest number of listings per host (~12).
- Other boroughs (Bronx, Brooklyn, Queens, Staten Island) have much fewer (~2-4 listings per host).

### Comparison of Yearly Availability by Neighbourhood Group
- Staten Island has the highest availability (close to 200 days per year).
- Bronx and Queens also have high availability, while Brooklyn and Manhattan have lower availability (closer to 125-150 days).

### Comparison of Number of Reviews by Room Type¶
- Private rooms and entire apartments have the most reviews (~22-24 median reviews). 
- Shared rooms have fewer reviews (~15-18 median reviews)

### Comparison of Host Listing Counts by Room Type
- Entire home/apartments have the highest number of listings per host (~10). 
- Shared and private rooms have significantly fewer listings per host

### Comparison of Yearly Availability by Room Type
Shared rooms tend to be available for longer durations. Entire homes and private rooms may have more seasonal availabilit

### Outliers Analysis
### Creating Model
