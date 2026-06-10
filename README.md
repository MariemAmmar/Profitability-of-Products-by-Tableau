# Profitability-of-Products-by-Tableau

Project Link  
https://public.tableau.com/app/profile/mariem.ammar/viz/DataAnalysisProject2_17590602087860/Story1

---

## Overview
This mini-project is a focused Tableau story (`Story1`) that highlights sales and profitability insights from a retail dataset. It demonstrates use of story points, captions, and annotations to communicate findings clearly.

---

## What’s included
- Tableau Public story: `Story1` (link above)  
- Visuals and dashboards used in the story:
  - Product quantity sold by category
  - Profit by category across years
  - Profit by product (top SKUs)
  - Customer segment and geographic dashboard for the top product

---

## How to view
1. Open the Tableau Public link above.  
2. Use the story navigation to move through each chapter.  
3. Interact with filters and tooltips to explore details.

---

## Story structure (chapter highlights)
1. Product Quantity Overview  
   - Count/quantity of items sold by category. Caption notes which category sells the most products.

2. Profitability by Category (over time)  
   - Line charts by year. Annotation highlights substantial profit growth in a specific category.

3. Profit by Product  
   - Bar chart of product-level profit. Annotation identifies the top contributing product and its share of total profit.

4. Customer segmentation & map for top product  
   - Dashboard showing buyer segments and geographic distribution for the top product. Notes on dominant customer segment and regional clusters.

---

## Key insights
- A specific category shows strong profit growth over the analyzed period despite not having the highest quantity sold.  
- A single product accounts for a large share of total profit, indicating concentration risk and opportunity.  
- The main buyer segment for the top product is `Individual` consumers, with geographic concentrations that can inform targeting.

---

## Business recommendations
- Review pricing, supply, and inventory strategy for the top-performing product due to profit concentration.  
- Explore marketing and product diversification to reduce concentration risk and grow other profitable items.  
- Use geographic demand signals to optimize promotions and inventory allocation.

---

## How this was built (high level)
- Prepared and filtered the retail dataset (order-level fields: product, category, sales, profit, dates, customer segment, region).  
- Created separate worksheets:
  - Quantity by category/product (`bar chart`, sorted)
  - Profit by category over years (`line chart`)
  - Profit by product (`ranked bar chart`)
  - Customer segment + map (`dashboard`)
- Assembled the worksheets into a Tableau story, added captions and annotations, and published to Tableau Public as `Story1`.


---


