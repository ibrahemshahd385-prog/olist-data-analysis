Olist Business & Data Research — HVIA Task 01

A data analysis project on Olist's public Brazilian e-commerce dataset (2016–2018), completed as part of the HVIA Data Analysis Internship — Task 01.

📌 Overview

This project follows a full research-to-solution flow:

Research → Understand → Analyze → Think → Propose → Communicate

Rather than jumping straight into charts, the goal was to first understand Olist as a business (its 2016–2018 model specifically, since that is the period the dataset covers), then explore the raw data, extract real findings, interpret them from a business perspective, and propose a concrete data solution.

📂 Contents
File	Description
Olist_Research_Complete.pdf	Full write-up: company research, dataset understanding, findings, business interpretation, proposed solution, and outreach message
code.ipynb	Jupyter notebook with all analysis code (Python / Pandas), each step explained
🏢 Company Research

Olist is a Brazilian company that connects small and medium sellers to major marketplaces (Mercado Livre, Americanas, Amazon, etc.) through a single contract, instead of each seller managing every marketplace separately. The real customer is the seller — the end shopper buys from the marketplace itself and rarely interacts with Olist directly.

🗂️ Dataset

The public Olist Brazilian E-Commerce Dataset (Kaggle), covering ~99,000 real orders from 2016–2018 across 9 related tables: customers, orders, order items, payments, reviews, products, sellers, geolocation, and category translation.

🔍 Key Findings
Finding	Result
Repeat purchase rate	3.12%
Orders delivered late	6.77%
Review score — on-time vs. late	4.28 → 2.26
Revenue from top 10% of sellers	67.5%
Customers based in São Paulo state	42%
Average freight cost vs. product price	16.6%
Items where freight costs more than the product	4,124

Full explanation and business interpretation for each finding is in the PDF report.

💡 Proposed Solution

Predictive Delivery Risk Model — a lightweight model that estimates, at the moment an order is placed, how likely it is to arrive late, using data Olist already collects. High-risk orders can then be handled proactively (nudging the seller, upgrading shipping, or notifying the customer) before the delay happens and damages the platform's shared "Olist Store" rating.

🛠️ Tools Used
Python (Pandas) for data exploration and analysis
Jupyter Notebook
Manual research from dated, verifiable sources (Kaggle dataset description, press interviews, funding databases)
🙋 About This Project

Completed as a training task for HVIA — Data & AI Solutions.
