# Burger King Sales Performance Dashboard 🍔📊
A deep dive into Burger King's sales data. This project uses Power BI to showcase key insights into revenue, order volume, and category-wise performance.


## 📌 Project Overview
Yeh project Burger King ke Jaipur outlet ka sales performance review karta hai taaki store manager aasani se revenue trends aur top-selling items ko track kar sake[cite: 1]. Is data analysis project mein ek interactive Power BI dashboard banaya gaya hai jo 2026 ke sales data ka deep dive provide karta hai[cite: 1]. Is dashboard ko business decision-making aur agle quarter ki promotions plan karne ke liye design kiya gaya hai[cite: 1].

## 🎯 Problem Statement
Store management ko ek aise simple aur effective dashboard ki jarurat thi jo in sawalo ke jawab de sake[cite: 1]:
* Overall revenue, total orders, aur total items sold kitne hain?[cite: 1]
* Month-by-month sales me kya changes aa rahe hain?[cite: 1]
* Revenue ke hisaab se top 5 menu items kaunse hain?[cite: 1]
* Kaunsi menu categories sabse zyada sales drive kar rahi hain?[cite: 1]

## 📂 Dataset Used
Data do primary CSV files se extract kiya gaya hai[cite: 1]:
* `menu.csv`: Isme menu item ID, item name, category, aur price ki details hain[cite: 1].
* `order_details.csv`: Isme order ID, order date, order time, aur item ID shamil hain[cite: 1].

## 💡 Key Insights & KPIs
Dashboard ke analysis se ye major insights nikalkar aayi hain:
* **Total Revenue:** ₹ 1.75M[cite: 2]
* **Total Orders Placed:** 5.37K[cite: 2]
* **Total Items Sold:** 12.234K[cite: 2]
* **Top Selling Item:** 'Chicken Whopper Meal' sabse zyada revenue generate karne wala item hai, jiske baad 'BK Classic Veg Burger' ka number aata hai[cite: 2].
* **Category Performance:** 'Meals' category total sales ka sabse bada hissa (28.19%) drive karti hai, aur uske baad 'Veg Burger' (22.55%) ka contribution hai[cite: 2].
* **Sales Trend:** Monthly revenue progression ek U-shape trend dikhata hai, jisme January se February tak dip aaya aur March me wapas growth dekhne ko mili[cite: 2].

## 🛠️ Tools & Technologies
* **Data Visualization:** Power BI[cite: 1]
* **Data Manipulation:** Power Query / DAX
* **Database Management:** SQL (Data extraction and initial exploration)

## 🚀 How to Use
1. Is repository ko clone karo:
   `git clone <your-repo-link-here>`
2. Repository ke folder me ja kar `order_details.csv` aur `menu.csv` files ko check karo[cite: 1].
3. Dashboard explore karne ke liye `.pbix` (Power BI) file ko Power BI Desktop me open karo.
