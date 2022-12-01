# CASE-Insider
 
![GitHub top language](https://img.shields.io/github/languages/top/hbatistuzzo/CASE-Insider)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/hbatistuzzo/CASE-Insider)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/hbatistuzzo/CASE-Insider)
![GitHub last commit](https://img.shields.io/github/last-commit/hbatistuzzo/CASE-Insider)

Project status: In Progress

## Technologies

- Python 3.8.13
	- Seaborn 0.11.2
	- Matplotlib 3.5.3
	- Pandas 1.4.4
	- Numpy 1.21.5
	- Pycaret 2.3.10
	- Scikit-learn 1.1
- Tableau 2022.3

---

Insider Store is a retail apparel and fashion company.<\br>
This project is based on their 2022 case challenge for a Business Analytics position.

<img src="images/logo2.png" width="100%"/>

---

## Project Objectives

The challenge sets 4 objectives:

1) Create meaningful graphs, simulating a result dashboard according to the analyzed data from different sources.

2) Identify clients' unique profiles.

3) According to the clients' profiles identified earlier, choose the top 3 profiles in order for the company to create an action plan, focused on increasing monthly revenue.
Explain the motives for choosing them. Show how this action plan would be structured, including a logical step-by-step and the expected results.

4) Provide opinions on the company's website layout. What insights can I offer?

---
Client Base Dataset

**Insights:**
- 297 unique clients, 189 male (63.6%), 85 female (28.6%) and 23 undeclared (7.7%)
- 40% of all clients from SP, followed by ~10% each from RJ, MG. Overall, the SE region accounts for ~60% of clients.

Item Base Dataset

**Insights:**
- 15% of orders made with Coupons
- There are repeated Order ID's. Implying..?
- Some clients ordered only once, others ordered items over 15 times each. Keep those in mind.

Dim_product Dataset

**Insights:**
- 13 Insider unique products
- 8 for women, 4 for men, 1 neutral (socks)
- Types: 5 sports, 5 casual, 3 underwear


---
To do:

- brazil map of client distribution (state, city).

