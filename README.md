### **1 - Introduction**

This comprehensive analysis aimed to identify key correlations between various features to enhance the business model of our food sharing platform. Despite the constraints of a limited dataset, which presented challenges in drawing definitive conclusions, several significant insights emerged. The analysis encompassed data preparation, exploratory data analysis (EDA), hypothesis testing, and the formulation of strategic recommendations.

### **2 - Table of Contents**

- [1 - Introduction](#1---introduction)
- [2 - Table of Contents](#2---table-of-contents)
- [3 - Usage](#3---usage)
- [4 - Project Structure](#4---project-structure)
- [5 - Data](#5---data)
- [6 - Analysis](#6---analysis)
- [7 - Results](#7---results)
- [8 - Visualizations](#8---visualizations)
- [9 - Conclusions](#9---conclusions)
- [10 - Acknowledgement](#10---acknowledgement)
- [11 - Contact](#11---contact)


### **3 - Usage**

 .ipynb:
Google Colab: Upload directly via the "File" menu or open from Google Drive<br>
Jupyter Notebook: Install Jupyter, start it via terminal, and open the .ipynb file through the interface<br>
Tableau: Open .twb file with [Tableau](https://www.tableau.com/community/public)

. python:<br>
	&emsp;- pandas<br>
	&emsp;- numpy<br>
	&emsp;- matplotlib<br>
	&emsp;- seaborn<br>
 	&emsp;- scipy.stats --> stats<br>
	&emsp;- statsmodels.stats.multicomp --> pairwise_tukeyhsd<br>


### **4 - Project Structure**
```
Diabetes_Features_Selection/
│
├── data/: # Reference to dataset
|   ├── food_orders_new_delhi.csv
|   └── food_orders_new_delhi.hyper
│
├── notebooks/: # Jupyter notebook
│   └── Food_Delivery_New_Dehli.ipynb
│
├── results/: # Output files, results, project report, .ppt presentation
│   ├── Tableau presentation_material
│       └── Food_delivery_New_Dehli.twb
│
│   ├── Count_order_by_discount_over_hour.png
│   ├── Count_order_per_day.png
│   ├── Count_order_per_delivery_time_bins.png
│   ├── Count_order_per_hour.png
│   ├── Count_order_per_weekday.png
│   ├── Heatmapt_Correlation_discounts:time_of_day.png
│   ├── Restaurant_revenue_per_day.png
│   ├── Restaurant_revenue_per_hour.png
│   └── Restaurant_revenue_per_weekday.png
│
└── README.md
```
### **5 - Data**
The dataset `food_orders_new_delhi.csv`<br>
	&emsp;- Order ID<br>
	&emsp;- Customer ID<br>
	&emsp;- Restaurant ID<br>
	&emsp;- Order Date and Time<br>
	&emsp;- Delivery Date and Time<br>
	&emsp;- Order Value<br>
  	&emsp;- Delivery Fee'<br>
  	&emsp;- Payment Method<br>
  	&emsp;- Discounts and Offers<br>
  	&emsp;- Commission Fee<br>
  	&emsp;- Payment Processing Fee<br>
  	&emsp;- Refunds/Chargebacks<br>


### **6 - Analysis**

We conducted ANOVA tests to determine significant differences in how various features affect total order value and commission received. The results indicated that the 'Discounts and Offers' feature, specifically the '15% New User' discount, has a statistically significant impact on revenue. However, this statistical significance does not translate into tangible revenue growth for participating restaurants.

### **7 - Results**

**Key Findings**<br>
- Customer Acquisition and Retention: The platform exhibits a suboptimal customer-to-restaurant ratio of 1.6, signaling potential issues in customer acquisition or retention strategies.<br>
<br>
- Order Frequency: Even top-performing restaurants demonstrate low order volumes, with a maximum of 6 orders, indicating significant room for improvement in customer engagement.<br>
<br>
- Delivery Efficiency: Average delivery times approaching 2 hours may be a critical factor deterring repeat orders and overall customer satisfaction.<br>
<br>
- Discount Efficacy: While the '15% New User' discount showed statistical significance in impacting revenue, further analysis revealed that it underperforms compared to other discount offers and non-discounted orders in terms of average order value.<br>
<br>
<br>
**Recommendations:**<br>
- Refund Process Optimization: Conduct a thorough review of the chargeback and refund processes to mitigate their impact on overall revenue.<br>
<br>
- Delivery Time Improvement: Implement strategies to reduce delivery times, thereby enhancing customer satisfaction and encouraging repeat orders.<br>
<br>
- Customer Base Expansion: Develop and execute targeted strategies to increase both the customer base and order frequency.<br>
<br>
- Data Collection Enhancement: Prioritize the collection of more comprehensive and representative data to enable more robust analysis and insights.<br>
<br>
- Advanced Statistical Analysis: Consider conducting further statistical analyses with an expanded dataset to identify significant factors affecting platform performance.<br>

### **8 - Visualizations**

Plots viz located in:
&emsp;`results/`<br>
Dashboard available [online](https://public.tableau.com/app/profile/bertrand.flanet/viz/Food_delivery_New_Dehli/Dashboard1?publish=yes).


### **9 - Conclusions**

While this analysis provides valuable insights into our food sharing platform's current performance, the limited dataset constrains our ability to draw definitive conclusions. Moving forward, it is imperative to address the identified concerns, particularly regarding customer acquisition, order frequency, and delivery efficiency. Additionally, a more comprehensive data collection strategy will be crucial for conducting more in-depth analyses and deriving actionable insights to drive the platform's growth and success.

### **10 - Acknowledgement**

Analysis conducted alongside and with the help of [Kajetan Hanausek](https://www.linkedin.com/in/kajetanhanausek/)

### **11 - Contact**

Bertrand Flanet<br>
E-mail: bertrand.flanet@gmail.com<br>
linkedIn: https://www.linkedin.com/in/bertrand-flanet-67b1b2299/
