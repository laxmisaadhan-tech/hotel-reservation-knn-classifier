# Hotel Reservation System using KNN Classifier

## Introduction
In this project, I developed a machine learning model to predict whether a hotel booking will be canceled or not. The main objective was to understand customer booking behavior and build a reliable prediction system.

As required, I used the K-Nearest Neighbors (KNN) algorithm as the primary model. In addition to this, I also implemented Logistic Regression to compare performance and gain better insights.

---

## Dataset
The dataset used in this project is the **Hotel Reservations Dataset**, which contains information about hotel bookings such as number of guests, room type, meal plan, lead time, and booking status.

- Source: Kaggle  
- The dataset is real-world and widely used for machine learning tasks

---

## Approach

### 1. Data Preprocessing
- Removed unnecessary columns such as Booking_ID  
- Created a new feature `total_nights` by combining weekday and weekend stays  
- Converted categorical variables into numerical format using one-hot encoding  

### 2. Feature Scaling
- Applied StandardScaler to normalize the data  
- This is important for KNN since it is a distance-based algorithm  

### 3. Model Building

#### K-Nearest Neighbors (KNN)
- Used as the main model as per project requirement  
- Tested multiple values of K to find the best performance  

#### Logistic Regression
- Used as an additional model for comparison  
- Helps understand linear relationships in the data  

---

## Results

- KNN model achieved good accuracy in predicting booking cancellations  
- Logistic Regression performed slightly better in comparison  
- The comparison shows that different models can capture patterns differently  

---

## Visualizations

The following visualizations were used in the project:
- Booking status distribution  
- Lead time vs booking status  
- Accuracy vs K value  
- Confusion matrix  
- Model comparison graph  

These graphs help in better understanding the dataset and model performance.

---

## Conclusion

In this project, I successfully implemented KNN to predict hotel reservation cancellations. The model performed well and provided meaningful results.

By comparing it with Logistic Regression, I observed that Logistic Regression slightly outperformed KNN. This highlights the importance of testing multiple models before finalizing a solution.

Overall, this project demonstrates how machine learning can be applied to solve real-world problems in the hospitality industry.

---

## Tools and Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## Source
Dataset: Hotel Reservations Dataset  
Platform: Kaggle  
