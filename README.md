# Marketing Mix Data Processing and Modeling 

## The Marketing Mix
We use __marketing mix__ elements to break down our products and services into components so that we can better understand how to strengthen a brand and make better products for our target markets. There have been a few different iterations of the [Marketing Mix](https://marketingmix.co.uk/definition-marketing-mix/) as people became more in-tune with business-consumer relationships, needs, and wants (known as the 4 P's, 7 P's, and 4 C's), which break down into these (somewhat overlapping) main ideas:

 - __Product__: What makes the product "the product"--features, benefits, intended use, actual use, "genre" of product, competitors's products
 - __Price__: Price to the consumer, price to the business, perceived value, profit, market share, market penetration, competitor prices
 - __Place__: Physical placement in a brick and mortar store, where the product is sold (e.g. in person vs. online, or both), how and where the product is distributed 
 - __Promotion__: Advertisement content and medium (e.g. online, paper ads, billboards, influencers, etc.), product promotions, public relations, sales organization and strategy
 - __People__: The staff and employees of the business, salespeople/customer point-of-contact, business culture
 - __Process__: How the products get to the end-consumer and related support, efficiencies/bottlenecks in the process, research and development, design
 - __Physical Evidence__: Customer experience with the brand, public perception, product packaging, online/social media presence
 - __Cost__: Cost of the product and the opportunity cost to the consumer and business
 - __Consumer Wants and Needs__: Consumer needs and wants and how these relate to other products on the market and future shifts
 - __Communication__: How the organization has an "open dialogue" with consumers to inform product development
 - __Convenience__: Product's availability and convenience for consumers regarding access, use, and sharing
 
 ## Marketing Mix Modeling
 Most of the marketing mix elements are qualitative elements because we need to figure out what the elements are that make our product different (at least in the eyes of consumers) that other products or services (e.g. if one of the features of our *product* is the color, we need to identify the colors that best suit our needs). However, simply knowing the qualitative elements doesn't give us much evidence or support to figure out why these elements are important or which elements are more important or lagging because of our business's operations. For this, we'll perform __marketing mix modeling__ analysis, in which, we essentially "define" a numerical value for each of our marketing mix inputs and then run a regression analysis to figure out which elements (independent variables) are most significant to a specified output (dependent variable), and how they relate to each other. 

For example, we may want to understand how the __product, price, place,__ and __promotion__ of a product affected sales over a 6-month period, we may set up our data to include: 
 - *sales per week* as our *dependent variable*  
 - the number of products for each product sold each week as our *product independent variables*
 - the price of each product as our *price independent variable*
 - dummy variable for an online or in-store purchase as our *place independent variable*
 - percentage discount as our *promotion independent variable*
 
Then, run a regression analysis to see which of these variables (if any) were significant in driving or deterring sales for our 6-month period. 

## Marketing Mix Modeling with Baltimore City Employee Turnover
To continue our Baltimore City government employee churn analysis, we'll use marketing mix elements to help determine why some departments experience churn, and what factors might keep employees in city government jobs. Similar to how we imagined the Baltimore City government employees as "customers," we'll imagine their overtime earnings (*cost*), salary increases (*price*), salary before they left city government (*price*),job changes (*place*), and number of people in their department (*physical evidence*) to see what may have a significant impact on employee churn or retention. 
