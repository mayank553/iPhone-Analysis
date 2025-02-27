# iPhone Data Analysis

This project analyzes an iPhone dataset using **Pandas** to extract insights related to pricing, storage, discounts, and reviews.

## Data Preprocessing

1. **Renaming Columns**
   - The dataset contains column names with spaces. These were replaced with underscores (`_`) for easier access.

2. **Handling Missing Ratings**
   - Missing `Star_Rating` values were initially filled with the **average rating of all models**.
   - Later, missing ratings were filled with the **average rating of models with the same RAM configuration**.

## Data Analysis

3. **Calculating Discounts**
   - A new column `Discount_Percentage` was created based on `MRP` and `Sale_Value`.

4. **Identifying the Highest Discount Model**
   - The iPhone model with the highest **discount percentage** was determined.

5. **Counting Models by Storage**
   - The total number of models available for each **storage configuration** (e.g., 128 GB, 64 GB) was computed.

6. **Counting Models by Color**
   - The total number of models available for each **color** was identified.

7. **Counting Models by iPhone Version**
   - The total number of models for each **iPhone version** (e.g., iPhone 8, iPhone XR) was extracted.

8. **Top 5 Models by Reviews**
   - The **top 5 models** with the highest number of reviews were listed.

9. **Price Difference Analysis**
   - The **price difference** between the highest and lowest-priced iPhone models (based on MRP) was calculated.

10. **Total Reviews for iPhone 11 & 12**
    - The total number of reviews was aggregated separately for **iPhone 11 and iPhone 12**.

11. **Finding the 3rd Highest MRP iPhone**
    - The iPhone with the **third highest MRP** was identified.

12. **Average MRP of Expensive iPhones**
    - The average MRP of iPhones priced **above 100,000** was calculated.

13. **Best 128 GB iPhone by Ratings-to-Reviews Ratio**
    - Among **128 GB storage iPhones**, the model with the **highest ratings-to-reviews ratio** was determined.

## Technologies Used
- Python
- Pandas
- Jupyter Notebook 

## Dataset
- `iphone.csv`: Contains information about various iPhone models, including price, storage, color, ratings, and reviews.

---
This project provides valuable insights into iPhone pricing, storage preferences, and customer reviews, leveraging **data analysis with Pandas**. 🚀

