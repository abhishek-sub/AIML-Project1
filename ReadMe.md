# Introduction
This is an assignment for professional certificate course which focuses on practical application of data analysis, plotting, statistical summarization and data vizualization skills and techniques to a machine learning problem.

The goal of the project is to use data analysis, vizualization and probability distribution to distinguish between customers who accepted a coupon versus those who did not. The dataset used for this project is foud here:

[Link to Dataset](/data/coupons.csv)

The link to Jupyter Notebook can be found here: [Link to Jupyter Notebook](/Coupons_project.ipynb)

## Initial Data Analysis
There are 12684 entries out of which 12576 entires in 'car' cloumn are null values.The null values in 'Car' column was filled with a 'No' to indicate that there was no value provided. There were a few other columns which had null entires but they are minimal and can be safely ignored.

## Findings
The over all coupon acceptance rate was 57%, with most folks preferring coffee house coupons.

### Bar Coupon related findings
- 42% of the coupons were accepted
- 76% of customers who frequently visited bars (3 times or more in a month) accepted bar coupons as compared to 37% coupon acceptance rate for customer who visited bars less regularly
- Among those who do visit bars more frequently the younger visitors (less than 30) are more likely to accept coupons as compared to older people or those with kids. This may reflect the fact that younger people tend to socialize more and visit bars and are more inclined to accept coupons or discounts for such activities
- Drivers who frequently visit cheap restaurants and have an income less than 50K tend to refuse the coupons more often. This indicates that there may be some dietary preferences or other behavioral characteristics among lower income driver because of which they would refuse a coupon/discount to a bar.

The data also shows that age, maritial status, frequency of bar visits, economic conditions play an important role in the likelyhood of accepting bar coupons.

## Carryout and Take away Coupon findings
- The data shows that widowed and single folks tend to accept carry out/take away coupons where as married and folks with partners would much rather eat at the restaurant.
- Folks having a more labour intensive work like cleaning, maintenance and construction have a higher probability of accepting take away coupons as compared to folks with more of a desk job and people generally tend to take take away on their way home
- Men are more likely to accept accept take away coupons as compared to women
- Weather and temperature also seem to influence wether drivers accept the take away coupons or not with a acceptance rate of over 72% on sunny days as compared to 69% on rainy days

## Recommended next steps
Based on the analysis of data below are some recommendations to improve the coupon acceptance rate

- Identify high response segments such as construction workers/Cleaning and maintenance workers and provide more personalized offers such as higher value coupons/ shorter expiry for more frequent customers.
- Bundle and sell coupons to increase perceived value
- Reward frequent visitors with coupons of increasing value to increase acceptance rate
- Use weather, temperature, time to trigger relevant coupons.