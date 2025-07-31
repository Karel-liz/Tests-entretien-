TEST

Based on the attached dataset and lookup tables, answer the questions below IN ENGLISH as best as you can. You may use this Excel file (create new sheets) or any combination of the following Microsoft support tools you'd like to provide your answers : MS Excel, MS Word, MS PowerPoint, PowerBI.
The "sales" sheet represents the data table detailing transactions over parts of 2023 and 2024. This tables references the "products" and "countries" lookups for more detail about the items being transacted and the markets they are sold in.
The columns of the "sales" table indicate the following:
- TRANSACTION_ID = a unique reference for each transaction.
- PRODUCT_ID = a unique reference for each product.
- RETAILER_REF = a reference to the distributor through which the product is sold (video game market platforms).
- COUNTRY_CODE = a two-letter code referencing an individual country from which the transaction was made. 
- WEEK = the week number of the year in which the transaction occured
- YEAR = the year in which the transaction occured
- UNITS = the total number of units sold in a given transaction
- TOTAL_VALUE_EUR = the value in Euro of the transaction net of refunds, VAT and retailer commission. 

The columns of the "products" lookup indicate the following:
- PRODUCT_ID = a unique reference for each product.
- SKU_NAME = the name of a specific item / product at the SKU level
- TITLE_NAME = the name of the game at the title level. A title contains multiple products (or SKUs)
- PLATFORM_NAME = the name of the device on which the product can be played
- GENRE = the genre of the title
- SUB_GENRE = a subcategory of the genre in question
- RELEASE_DATE = the official release date of the product . It may differ from platform to platform.
- PRODUCT_TYPE = the type of content, which in this exercise can be a Base Game, a Special Edition, or a DLC (Downloadable Content).


Questions
Question
1. Calculate the total Revenue and Units Sold in 2023 and then in 2024. How does 2024 results compare to 2023 ? Does this comparison make sense to you ? Elaborate
2. Identify top-selling retailer in terms of Revenue and Units Sold in 2023. Which retailer sells our titles at the highest price ?
4. How many Units did Operation: Sledgehammer sell in Week 15 of 2023 ? What about in Week 18 of 2023 ? What could explain the difference in your opinion ?
5. Breakdown the LTD performance of the entire portfolio by Product Type (in percentage of total). Do so by Revenue first and then by Units Sold. How do you explain the different results between the two breakdowns (specifically between Special Editions and DLCs).
6. Analyze the performance of Genres by Platform in terms of Units Sold. How would you present the results of this analysis in a visual ? Can you explain the reason behind those results ?
7. Calculate the Cumulative Revenue of the entire portfolio in the United States and France at Week 15 and Week 20 of 2023. In which country has our portfolio experienced the fastest growth ?
8. Analyze the performance of RING CHAMPION VI - DELUXE EDITION on PLAYSTATION NETWORK during Weeks 38, 39, and 40 of 2023. Compare it the three previous weeks. What can you deduce from your analysis ?
9. Compare the performance of FURY CELL and DARKSWORD on PLAYSTATION NETWORK around their release period, up to 5 weeks since release. Which title has performed better at release in terms of Units Sold? What can you say about the launch of each title ?
10. Can you identify missing data in the dataset ? How would you handle those ? Demonstrate in one identified case.
11. How would you identify outliers in this dataset ? What data-driven approach would you use to eliminate them ? Demonstrate.
