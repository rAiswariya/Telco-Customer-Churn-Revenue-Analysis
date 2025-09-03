# Telco Customer Churn & Revenue Analysis
### Predicting Customer Churn and Identifying High-Value Customers for Telecommunications Companies

---

## **Introduction**
This project analyzes customer churn for a telecommunications company using the publicly available [WA_Fn-UseC_-Telco-Customer-Churn.csv](Data/WA_Fn-UseC_-Telco-Customer-Churn.csv) dataset. By understanding which customers are likely to leave and the factors influencing churn, businesses can make data-driven decisions to reduce churn, improve retention strategies, and maximize revenue from high-value customers.  

**Key highlights of the project:**  
- Predicting churn using **machine learning models** including Random Forest, Gradient Boosting, AdaBoost, and a Voting Ensemble.  
- Identifying **top features** driving churn using SHAP values.  
- Detailed **exploratory data analysis (EDA)** with visualizations for insights.  
- Revenue analysis to target **high lifetime value (LTV) customers**.  

**SEO Keywords:** customer churn prediction, telecom churn analysis, telco data analytics, machine learning for churn, retention strategy, predictive modeling, customer lifetime value, Random Forest, Gradient Boosting, SHAP analysis.

---

## **Visual Representations**

### **1. Contract Type vs Churn**
![Contract vs Churn](Images/Contract%20vs%20Churn.png)

### **2. Monthly Charges vs Churn**
![Monthly Charges vs Churn](Images/Monthly%20Charges%20vs%20Churn.png)

### **3. Tenure vs Churn**
![Tenure vs Churn](Images/Tenure%20vs%20Churn.png)

### **4. Top 10 Features Driving Churn**
![Top 10 Features driving Churn](Images/Top%2010%20Features%20driving%20Churn.png)

### **5. SHAP Value Impact on Churn**
![SHAP Value impact on Churn](Images/SHAP%20Value%20impact%20on%20Churn.png)

---

## **Project Structure**
```

Telco Customer Churn & Revenue Analysis/
│
├── Data/
│   └── WA\_Fn-UseC\_-Telco-Customer-Churn.csv
│
├── Images/
│   ├── Contract vs Churn.png
│   ├── Monthly Charges vs Churn.png
│   ├── SHAP Value impact on Churn.png
│   ├── Tenure vs Churn.png
│   └── Top 10 Features driving Churn.png
│
├── Customer Churn Prediction.ipynb
├── requirements.txt
└── README.md

````

---

## **Installation & Usage**

1. **Clone the repository**  
```bash
git clone https://github.com/rAiswariya/Telco-Customer-Churn-Revenue-Analysis.git
cd Telco-Customer-Churn-Revenue-Analysis
````

2. **Set up the environment**

```bash
pip install -r requirements.txt
```

3. **Open the Colab Notebook**

* Open `Customer Churn Prediction.ipynb` in [Google Colab](https://colab.research.google.com/) or locally in Jupyter Notebook.
* Ensure the `Data` and `Images` folders are in the same directory as the notebook.

4. **Run the Notebook**

* Execute all cells to perform EDA, modeling, feature importance analysis, and churn prediction.

---

## **Known Issues**

* **Imbalanced Dataset:** Churned customers form \~27% of the dataset. No oversampling or undersampling techniques have been applied yet.
* **High LTV Analysis:** Revenue insights are derived from LTV estimates, which may require further validation in real-world scenarios.
* **Missing Advanced Feature Engineering:** Some potential features (like service complaints, NPS, or network usage) are not included.

---

## **Contributing**

Contributions are welcome!

* If you find bugs, issues, or improvements, please submit them via the **Issues** tab.
* Pull requests are appreciated for adding features, improving visualizations, or enhancing modeling techniques.
* Ensure that added code is properly documented and reproducible.

> Let’s collaborate to make this churn prediction and revenue analysis project even better!

---

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


