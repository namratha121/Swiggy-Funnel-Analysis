# Swiggy-Funnel-Analysis

Swiggy is one of the largest food ecommerce platform in the country. Every day more
than 1 million users are transacting on the platform. I have generated insights on the comapany's performance in 2019.

You can find the details of the sheets below:

Session Details sheet has date wise session count. You can find listing sessions, menu
sessions, cart sessions, payment sessions and order sessions day over day

Channel wise traffic sheet has traffic (listing sessions) breakup at date level.

Supporting Data sheet has other information at date level. The description of the columns is written below :

Metric & Description :
Count of restaurants : Number of operating restaurants for the day
Average Discount : Average discount given to all the transacting customers
Out of stock Items per restaurant : Average out of stock items per restaurant (total out of stock items/total
restaurants)
Avg. Packaging charges : On an average what is the packaging charges paid by customer while placing
the order
Avg. Delivery Charges : On an average what is the delivery charges paid by customer while placing
the order
Avg Cost for two : Cost for two is approximate spent for creating meal for two.
Number of images per restaurant : Count of images listed per restaurant on menu page
Success Rate of payments : ratio of successful transactions and payment initiated


What I did : 
1. I identified the increase or decrease in the number of orders using Session Details sheet
o Filled all the remaining columns of Session details based on the definition
mentioned above the column names
o Identify date of highs and lows in the orders with respect to same day last
week

2. I Checked if there is change in traffic as compared to same day last week
o If there is change in traffic, identify the source of traffic change using Channel
wise traffic sheet

3. I Checked if there is change in Overall Conversion as compared to previous dates
o I Broke the overall conversion into smaller part in the following metrics.
§ L2M - List to Menu
§ M2C - Menu to Cart
§ C2P - Cart to Payment
§ P2O - Payment to Orders
