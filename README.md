Python, Jupyter Notebook
# Hotel Booking Cancelation Analysis and Prediction

## Project Overview

This project analyzes a hotel booking dataset consisting of two hotel types: Resort Hotel (H1) and City Hotel (H2). The primary goal is to predict booking cancellations (`is_canceled`) based on various features such as booking details, customer demographics, and hotel attributes. The analysis includes Exploratory Data Analysis (EDA), predictive modeling, and visualization of insights to better understand the factors influencing cancellations.

---

## Workflow and Methodology

### 1. **Dataset Description**
The dataset contains the following key variables:
- **Hotel**: Type of hotel (H1 = Resort Hotel, H2 = City Hotel).
- **is_canceled**: Target variable indicating if the booking was canceled (1 = Yes, 0 = No).
- **Lead_time**: Days between booking and arrival date.
- **Arrival details**: Year, month, week number, and day of arrival.
- **Stay details**: Number of weekend and weekday nights stayed.
- **Guests**: Number of adults, children, and babies.
- **Meal**: Type of meal plan booked.
- **Market segment & distribution channel**: Booking origin and method.
- **Customer history**: Repeated guest status, previous cancellations, and previous non-cancelled bookings.
- **Room details**: Reserved and assigned room types.
- **Booking changes**: Amendments made to bookings.
- **Deposit type**: Categories include no deposit, non-refundable, or refundable deposits.
- **Other features**: Days in the waiting list, car parking spaces, special requests, customer type, and average daily rate (ADR).

---

### 2. **Exploratory Data Analysis (EDA)**
- Explored and visualized distributions of key variables.
- Analyzed trends such as cancellation rates by hotel type, lead time, and special requests.
- Performed feature importance analysis to identify key predictors for cancellations.
- Visualized relationships using charts and plots (e.g., cancellation trends by month, ADR vs. cancellation).

---

### 3. **Modeling Approaches**
Several machine learning models were implemented to predict booking cancellations:
- **Logistic Regression**: Baseline model to establish relationships between variables.
- **Decision Tree**: Interpretable model for understanding feature splits.
- **Random Forest**: Robust ensemble method for handling non-linear relationships.
- **Gradient Boosting**: High-performance model leveraging boosting for better accuracy.

**Key Findings**:  
The **Decision Tree** model outperformed others in terms of predictive accuracy and interpretability.

---

### 4. **Feature Importance**
Identified the most important factors contributing to cancellations, such as:
- Lead time
- Deposit type
- Special requests
- Customer type
- Days in the waiting list

---

## Repository Structure

- **hotel_bookings.csv**: The dataset used for analysis and modeling.
- **Hotel_cancelation_analysis**: Jupyter notebooks containing code for EDA, modeling, and visualization and also Key charts and plots summarizing insights.
- **README.md**: This file provides an overview of the project.

---

## Tools and Technologies Used

- **Data Analysis**: Python (pandas, numpy, matplotlib, seaborn).
- **Modeling**: scikit-learn for logistic regression, decision tree, random forest, and gradient boosting.
- **Visualization**: Matplotlib and seaborn for trend analysis and feature importance.

---

## Key Outcomes

- Built a predictive framework to identify high-risk cancellations.
- Gained insights into customer booking behavior and hotel management strategies.
- Highlighted key features influencing cancellations to guide business decisions.

---

