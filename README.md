# Analisis-Data-E-commerce
# 🛒 E-Commerce Analysis (Brazilian E-Commerce Dataset)

## 📌 Project Overview
This project analyzes a Brazilian e-commerce dataset to uncover customer behavior, sales performance, product trends, and operational efficiency. The goal is to generate insights that can help improve **customer satisfaction, marketing strategy, and logistics performance**.

## 📊 Key Business Questions
1. How is the sales and revenue performance in the last few months?
2. Which products are the most and least sold?
3. What is the demographic distribution of customers?
4. When was the last customer transaction (recency)?
5. How much money do customers spend in the last 6 months?
6. How do customer consumption patterns change over time, and which categories show the highest growth?
7. How accurate is the estimated delivery compared to actual delivery, and how does it affect customer satisfaction (review score)?
8. What is the relationship between product price and freight cost, and which categories are the most sensitive?
9. What are the most common payment methods, and do installments significantly affect transaction value?

---

## 🔍 Insights & Findings
- **Sales & Revenue**  
  - Strong growth during 2017, peaking in November–December (holiday season).  
  - After early 2018, sales stabilized with slight decline.

- **Top Products**  
  - Bestsellers: `cama_mesa_banho`, `beleza_saude`, `informatica_acessorios`.  
  - Least sold: `flores`, `cds_dvds_musicais`.  

- **Customer Demographics**  
  - Majority from metropolitan cities: São Paulo, Rio de Janeiro, Belo Horizonte.  
  - Opportunity: expand to secondary cities.  

- **Customer Spending (Last 6 Months)**  
  - Median spending ~ **R$112.90**.  
  - Most customers are **low spenders**, but there are **high-value customers (big spenders)** up to R$30,000.  

- **Product Category Trends**  
  - Highest growth categories (CAGR):  
    - `construcao_ferramentas_iluminacao` (+37.9%/month)  
    - `construcao_ferramentas_seguranca` (+30.7%/month)  
    - `beleza_saude` (+27.9%/month)  
  - Popular ≠ Fastest Growth → niche categories show great potential.

- **Delivery Accuracy & Customer Satisfaction**  
  - Correlation between delivery delay and review score = **-0.23**.  
  - Late deliveries → lower customer satisfaction.  

- **Price vs Freight Sensitivity**  
  - Some categories highly sensitive (e.g., `flores`, `pc_gamer`).  
  - Others strongly correlated with freight cost (`seguros_e_servicos`, correlation = 1.0).  

- **Payment Methods & Installments**  
  - Dominated by **credit card**, followed by boleto.  
  - More installments = higher average transaction value.  

---

## 📈 Visualizations
- Sales & revenue trends over time  
- Top & bottom product categories  
- Customer demographics by state (bar chart)  
- RFM Analysis segmentation  
- Customer spending distribution (histogram & boxplot)  
- Product category growth trends  
- Delivery accuracy vs review score  
- Payment method distribution  

---

## 🛠 Tech Stack
- **Python**: pandas, numpy, matplotlib, seaborn  
- **Jupyter Notebook**  
- **GitHub** for version control & portfolio  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ecommerce-analysis.git
