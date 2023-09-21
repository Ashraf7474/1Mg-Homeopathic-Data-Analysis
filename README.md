# 1Mg-Homeopathic-Data-Analysis
![image](https://github.com/Sudhansu352010/1Mg-Homeopathic-Data-Analysis/assets/131376814/6dd2a233-22ce-4678-b4dd-23a80c07bfcd)





# Technology & Tools  used
![image](https://github.com/Sudhansu352010/1Mg-Homeopathic-Data-Analysis/assets/131376814/1d4cac22-bcd3-4990-b918-d739138c9396)

# OUR APPROACH FOR THE PROJECT
![image](https://github.com/Sudhansu352010/1Mg-Homeopathic-Data-Analysis/assets/131376814/6df3e5be-7baa-40ee-b9c1-a66085e9b7fd)
Reference:
https://www.1mg.com/
https://www.1mg.com/categories/homeopathy-57

# Data Dictionary
![image](https://github.com/Sudhansu352010/1Mg-Homeopathic-Data-Analysis/assets/131376814/6d300e45-3c74-48e4-9ff9-62b925c92163)




# --Introduction-- 

Analyzed Tata 1mg's Homeopathic products using different user-specific factors. The Tata1mg Homeopathic project aimed to analyze product offerings, pricing, brand specialization, user ratings, and ingredients of homeopathic medicines. An interactive dashboard was created for efficient data visualization. Data was scraped from Tata 1mg Homeopathic using Python libraries BeautifulSoup and pandas. Excel was used for data cleaning, aggregations, and visualization. Power BI was used to create the final dashboard. Data analysis was performed on the extracted dataset.

# --Problem aimed to solve--

The main aim is to analyze the data of 1mg Homeopathic and extract valuable insights that can help us understand the product offerings, pricing, brand specialization, user ratings, and ingredients used in homeopathic medicines

These insights can be used to make informed decisions for opening a new homeopathic medicine store.

# --Data Description--
We possess two CSV files derived from scraping data from Tata 1mg, focusing on homeopathic medicines. These CSV files encompass crucial information such as medicine names, prices, ratings, number of ratings, brand details, ingredients, and key benefits.

# --Methodology--

Our approach involves utilizing BeautifulSoup and Selenium for web scraping Tata 1mg's homeopathic data. Following data extraction, we clean and preprocess using pandas. and create an interactive Power BI dashboard, enabling users to explore and make informed decisions.

# --Phases--

Web Scraping: Collect data from Tata 1MG homeopathic data with the help of a web scraping library BeautifulSoup and  Selenium.

Data Cleaning: Removing irrelevant data and correcting inconsistencies, such as missing values, incorrect data types, or duplicate entries.

Data Transformation: Converting data into a format that is suitable for analysis, such as aggregating or summarizing data, or transforming data into a standard format.

Data Integration: Combining data from multiple sources/files to create a single dataset for analysis.

Data Analysis and Visualization: Create visualizations to explore/analyze the data and identify patterns or trends, and use them finally to create a dynamic dashboard with the help of power bi.

PowerPoint Presentation: Compile the project's findings, methodologies, and dashboard visuals into a concise PowerPoint presentation. This presentation will serve as a medium to effectively communicate the project's results, insights, and potential business implications.







# Data Preparation

# Data Scrapping Code and Table(Snapshots)
![Capture51](https://github.com/Ashraf7474/1Mg-Homeopathic-Data-Analysis/assets/131772000/af763054-ec92-49c4-91fc-2dbdf7b63e77)
![Capture53](https://github.com/Ashraf7474/1Mg-Homeopathic-Data-Analysis/assets/131772000/148664cf-a5be-4568-bf19-645f4d7ab399)
![Capture54](https://github.com/Ashraf7474/1Mg-Homeopathic-Data-Analysis/assets/131772000/76cd244f-cf86-4e61-acf2-b57dd9c6a38a)






# Data Cleaning ( few code snippets )
![image](https://github.com/Sudhansu352010/1Mg-Homeopathic-Data-Analysis/assets/131376814/b3296b1f-0317-431d-8d3a-8247238ecd11)

# Aggregation on Different KPI’s
Number of medicine available for different benefit areas
![image](https://github.com/Sudhansu352010/1Mg-Homeopathic-Data-Analysis/assets/131376814/b397fd6a-a8fa-461a-8fb6-9e6ae0a604d9)
Price Range Varies from Rs.350.67 to Rs.99. Most Expensive Medicine cures Heart Diseases while least Expensive Medicine is for Ears.

----------------------------------------------------------------------------------------------------------------------------------
Average Price range of medicine for each benefit area
![image](https://github.com/Sudhansu352010/1Mg-Homeopathic-Data-Analysis/assets/131376814/08197868-7438-42e6-a0e3-89e63c64ad35)

Price Range Varies from Rs.350.67 to Rs.99. Most Expensive Medicine cures Heart Diseases while least Expensive Medicine is for Ears.

-----------------------------------------------------------------------------------------------------------------------------------
Brand specialization for each area (Key Benefits)
![image](https://github.com/Sudhansu352010/1Mg-Homeopathic-Data-Analysis/assets/131376814/afcf4c52-0fd8-4def-bb97-48dd2b8a6d89)

Dr. Bjain Pharmaceuticals Pvt Ltd, SBL Pvt Ltd and Dr Rechewg & Co. are the Brands which deals with the most 7 Benefit Areas.

-----------------------------------------------------------------------------------------------------------------------------------
Average price, min price , max price and Number of products for each brand
![image](https://github.com/Sudhansu352010/1Mg-Homeopathic-Data-Analysis/assets/131376814/d733ea72-d59b-4951-ab12-ec1a2c88de68)

-----------------------------------------------------------------------------------------------------------------------------------
Brands having most greater than 4 point review medicines
![image](https://github.com/Sudhansu352010/1Mg-Homeopathic-Data-Analysis/assets/131376814/a7f88d56-202b-40f9-93f0-eed99f341e86)
Adel Pekana Germany, Bhargava Phytolab, Fourrts India Laboratories P Ltd are the top rated Brand with 4.6 Stars out of 5 star .
------------------------------------------------------------------------------------------------------------------------------------


# Dashboard
![image](https://github.com/Sudhansu352010/1Mg-Homeopathic-Data-Analysis/assets/131376814/a0c3b4f2-6fbf-4d64-afc9-e0cd8a0db4bf)

# INSIGHTS
1. We are having a total of 1060 listed Homeopathic Products in our 1Mg Website, having an Average Price of Rs. 201.
2. The Price Range varies widely with a MIN Price of Rs.47 And MAX Price of Rs. 557.
3. Top Three brands in the homeopathic medicine space based on ratings are SBL, Dr. Reckeweg, and Schwabe.
4. Dr.Reckeweg is the brand with the most-high rated products ,with more than 40 products rated above 4 star.
5. The most expensive brand of homeopathic medicines is Dr. Reckeweg, while the cheapest brand is Baksons.
6. Nuphar letumen 2x is the most expensive ingredient and if there is a substitute of this then we can use that to reduce the cost of the medicine.
7. Most common benefit areas for homeopathic medicines are joint pain, hair care, skin care, and eye care. 
8. The most commonly used ingredient in homeopathic medicines is Arnica Montana, which is found in many Joint pain medicines.

# Future Scope 
1. Success of antibiotics in conquering bacterial infections, viral infections may become more prevalent in the future. Homeopathy has shown promise in treating viral infections and may be a valuable option in the years to come as we already seen during covid19.
2. Homeopathy has helped secondary infertility in high numbers.
3. Incorporating technology and expanding into new markets may also be important for staying competitive and reaching new customers. 
4. 1mg Homeopathic could explore expanding into new geographic markets or increasing their reach within existing markets. This could involve partnerships with local providers, marketing campaigns targeted towards specific demographics, or offering new services to attract new customers.



