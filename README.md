# DSA-Capstone-Amazon-Project
Starting my portfolio building on the Amazon Case Study Project Using Excel,  while taking my data analysis class with the incubator hub
This Project involves analysing product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement.
The dataset contains information scraped from Amazon product pages, including:
• Product details: name, category, price, discount, and ratings
• Customer engagement: user reviews, titles, and content
• Each row represents a unique product, with aggregated reviewer data stored as comma-separated values
Total Records: 1,465 rows
TotalFields: 16 columns

Before Working on the above Data, The Raw Data Sets was cleaned, duplicates were removed, and blank spaces was replaced with 0
some columns that were not needed for the review was deleted.
A column was created for Average Discount percentage, with the calculation =(Actual Price-Discount Price)/Actual Price *100
The Categories were splitted using delimiters (,|) 
To get product with 50% discount,calculate using =IF(Discount Percentage>=50%,"Yes","No")
Potential Revenue was calculate using = Actual Price * Rating Count
=IF(E2<200,"<200",IF(E2<=500,"200–500",">500"))

