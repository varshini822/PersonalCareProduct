# PersonalCareProduct
https://www.kaggle.com/datasets/ashaychoudhary/indian-summer-personal-care-products
🌞 Indian Summer Beauty Products Analysis
This project explores and analyzes a dataset of 10,000 Indian summer beauty products, with features ranging from product type, pricing, SPF, ingredients, fragrance, to popularity across regions and genders.

📂 Dataset Overview
Filename: indian_summer_beauty_products.csv

Shape: (10000, 20)

Key Columns:

Product_ID, Product_Name, Category, Brand

Average_Price, SPF_Rating, Skin_Type, Hair_Type

Popularity_Rating, Summer_Essential_Score, Online_Availability

📊 Analysis Performed
🏆 Popular Products and Brands
Identified Top 5 most popular products by Popularity_Rating.

Ranked Top 5 brands with highest average popularity.

💰 Pricing Insights
Boxplot of Average Price by Category

Comparison of Organic vs Paraben-Free pricing.

☀️ SPF & Summer Relevance
Correlation between SPF Rating and Popularity

SPF Rating distribution histogram.

Summer Essential Score distribution across categories.

🧴 Product & Demographic Preferences
Product preference by Hair Type

Gender distribution of product use.

Usage Frequency vs Popularity.

🌸 Fragrance & Online Trends
Distribution of Fragrance Types

Most used Online Availability platforms

Regional brand preferences (Region_Usage vs Brand)

📈 Visualization Libraries Used
matplotlib

seaborn

pandas

⚠️ Warnings Encountered
Some FutureWarnings were raised by Seaborn:

"Passing palette without assigning hue is deprecated..."

This can be resolved in future versions by explicitly assigning hue or using legend=False.

📁 How to Run
Open the notebook in Google Colab.

Upload indian_summer_beauty_products.csv to the Colab environment.

Run the cells sequentially to visualize and explore the data.

📌 Future Improvements
Handle missing values in Hair_Type, Skin_Type.

Add recommendation system based on product scores.

Correlation heatmaps for numerical columns.

📬 Contact
For any suggestions or collaborations, feel free to connect!
