# 🧠 Project Title: Customer Spending Score Prediction using Min-Max Scaling
________________________________________
🎯 Objective

The goal of this project is to analyze customer behavior data and predict or cluster customers based on their spending patterns.

The focus is to apply Min-Max Scaling to normalize features into a uniform range (0–1) so that every feature contributes equally to the model or clustering algorithm.
________________________________________
📊 Dataset
Use the Mall Customer Segmentation Dataset (Kaggle link):

👉 https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

Sample Features:

Feature	Description

CustomerID	Unique customer ID

Gender	Male/Female

Age	Age of the customer

Annual Income (k$)	Annual income in thousand dollars

Spending Score (1–100)	Score assigned based on spending behavior
________________________________________
⚙️ Tasks to Perform

1. Import and Inspect Data

•	Load the dataset using pandas

•	Display shape, data types, and missing values

2. Data Cleaning

•	Drop irrelevant columns like CustomerID

•	Handle missing values if any

•	Encode gender to numeric form (e.g., Male = 1, Female = 0)


3. Apply Min-Max Scaling

•	Scale numerical columns like:

o	Age

o	Annual Income (k$)

o	Spending Score (1–100)

•	Use MinMaxScaler from sklearn.preprocessing


Formula:

  Xscaled=X−XminXmax−XminX_{scaled} = \frac{X - X_{min}}{X_{max} - X_{min}}Xscaled=Xmax−XminX−Xmin 


4. Model / Analysis

Choose any one:
•	K-Means Clustering: Group customers based on similar spending and income
•	Regression Task: Predict Spending Score based on age and income
•	Visualization Task: Plot scaled vs. unscaled distributions

5. Compare Results
•	Compare results before and after scaling:
o	For clustering: visualize how scaled data affects cluster boundaries
o	For regression: check if training is faster or more stable
________________________________________

📈 Expected Outcome

•	All numerical features will lie between 0 and 1.

•	Algorithms sensitive to magnitude differences (e.g., K-Means, KNN) will perform more accurately.

•	You’ll visually notice more balanced and evenly spaced data points after scaling.

________________________________________

📄 Deliverables

•	Python Notebook (.ipynb) showing all steps

•	Scaled dataset (.csv file)

•	Graphs showing before vs. after scaling

•	Short summary: “Min-Max Scaling helped normalize income and spending features, improving clustering and visualization.”

