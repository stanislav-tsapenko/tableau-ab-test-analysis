# AB Test Analysis & Statistical Evaluation

## 📋 Project Overview
This project focuses on evaluating the results of A/B tests to optimize e-commerce user conversion funnels. By combining statistical rigor with interactive data visualization, I identified which test variations led to statistically significant improvements in user behavior and identified "noise" in the data.

## 🛠 Tech Stack
- **Data Extraction & SQL:** Google BigQuery (analyzing large-scale e-commerce behavioral logs).
- **Data Processing & Statistics:** Python (Pandas for data transformation, Statsmodels for Z-test calculations).
- **Visualization:** Tableau Public (interactive dashboard for business stakeholders).

## 🔍 Analytical Approach
1. **Data Extraction:** Connected to BigQuery via Python API to retrieve and join user session logs with A/B test metadata.
2. **Statistical Testing:** Implemented Z-tests for proportions to compare conversion rates between Control (A) and Treatment (B) groups for four core metrics: `add_payment_info`, `add_shipping_info`, `begin_checkout`, and `new_account`.
3. **Significance Evaluation:** Applied a p-value threshold (p < 0.05) to distinguish between meaningful performance impacts and statistical fluctuations.
4. **Visualization:** Developed a multi-layered Tableau dashboard, allowing for detailed segmentation by device, channel, and geographic region.

## 📊 Key Insights
- **Statistical Filtering:** Created a robust framework that automatically flags statistically significant results, ensuring that only reliable data-driven decisions are prioritized.
- **Conversion Optimization:** Identified specific test iterations where changes in the UI/UX led to a measurable increase in `begin_checkout` and `add_payment_info` rates.
- **Actionable Reporting:** The dashboard allows stakeholders to instantly visualize "Lift" and filter through complex test results.

## 🔗 Project Links
- [View Interactive Tableau Dashboard](https://public.tableau.com/views/ABTestAnalysis_17504420018160/ABtest?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- [Jupyter Notebook with Statistical Analysis](https://colab.research.google.com/drive/1iGhDSElmrQtuGEKYiJduTmhTlnjSkKnA?usp=sharing)

## 📸 Visualization
*<img width="625" height="866" alt="image" src="https://github.com/user-attachments/assets/9a882c91-7e17-4cfd-9c49-5d70f8beb1ee" />

