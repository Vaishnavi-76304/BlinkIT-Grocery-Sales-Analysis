# 🛒 BlinkIT-Grocery-Sales-Analysis

# 📊 Project Overview
This project presents a comprehensive data analysis of BlinkIT, one of India's leading last-minute grocery delivery platforms. 
Using real-world-like sales and outlet data, the project explores sales performance, product types, store characteristics, and 
customer trends to uncover actionable insights for business strategy and marketing.

# 📁 Dataset Description
The dataset contains detailed information about grocery items sold through various BlinkIT outlets across India.

            | Column Name                 | Description                                           |
            | --------------------------- | ----------------------------------------------------- |
            | `Item Identifier`           | Unique ID for each grocery item                       |
            | `Item Type`                 | Category of item (e.g., Fruits, Soft Drinks, etc.)    |
            | `Item Fat Content`          | Nutritional label (Low Fat, Regular, etc.)            |
            | `Item Visibility`           | Shelf visibility percentage in the outlet             |
            | `Item Weight`               | Weight of the item in grams                           |
            | `Outlet Identifier`         | Unique code for each BlinkIT outlet                   |
            | `Outlet Size`               | Size of the store (Small, Medium, High)               |
            | `Outlet Location Type`      | Location category (Tier 1, 2, or 3)                   |
            | `Outlet Type`               | Store format (e.g., Supermarket Type1, Grocery Store) |
            | `Outlet Establishment Year` | Year when the outlet was opened                       |
            | `Sales`                     | Total sales value for the item                        |
            | `Rating`                    | Customer rating of the product (scale of 1–5)         |
            

# 🔍 Key Analyses Performed
  📦 Product Category Performance: Identified top-selling categories and compared average sales and ratings.
  
  🛍️ Outlet Type Insights: Analyzed sales trends across different store formats and locations.
  
  🧊 Impact of Item Weight and Visibility: Explored how product features like weight and shelf visibility affect sales.
  
  🗓️ Store Age vs. Revenue: Compared outlet performance based on establishment year.
  
  📈 Tier-wise Sales Performance: Studied how geographic tier (Tier 1/2/3) influences customer purchasing patterns.


# 🧠 Key Insights
  Fruits and Vegetables lead in both revenue and frequency, indicating strong preference for fresh items.
  
  Outlet Size and Type significantly impact sales — medium-sized Supermarkets show the best average sales.
  
  Visibility of items on shelves correlates positively with sales, particularly in high-traffic outlets.
  
  Newer outlets (2020+) tend to perform better in Tier 3 cities due to increased digital adoption post-COVID.
  
  Higher-rated products enjoy 30% more average sales than lower-rated ones.

# 📌 Tools & Technologies Used
  Python (Pandas, Matplotlib, Seaborn)
  
  Jupyter Notebook
  
  Excel
  
  Power BI / Tableau (optional for dashboard visualization)

# 📂 File Structure

       ├── BlinkIT Grocery Data.xlsx      # Raw dataset
       ├── BlinkIT_Dataset.ipynb          # Main analysis notebook
       ├── README.md                      # Project documentation

# ✅ How to Run
  1. Clone the repository:

  2. Open BlinkIT_Dataset.ipynb in Jupyter Notebook or VSCode.

  3. Install required libraries:

          pip install pandas matplotlib seaborn openpyxl

  4. Run the notebook cells sequentially.
 
# 📌 Future Improvements
   * Integrate a predictive sales model using regression.

   * Add clustering to segment store types or customer behavior.

   * Create a dashboard in Power BI or Streamlit for interactive use.

