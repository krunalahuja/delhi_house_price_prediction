This project focuses on predicting house prices in Delhi using various features like area, number of bedrooms (BHK), bathrooms, furnishing status, locality, parking, property status (ready to move or under construction), transaction type (new or resale), and property type.

Objective
The primary aim is to build a machine learning model capable of accurately predicting house prices while extracting insights from data about Delhi’s housing market.

Data Description
The dataset contains the following columns:

Area: Area of the house in square feet.
BHK: Number of bedrooms.
Bathroom: Number of bathrooms.
Furnishing: Furnishing status of the house (Furnished/Unfurnished).
Locality: The location of the house in Delhi.
Parking: Number of parking spaces available.
Price: Price of the house in INR.
Status: Indicates whether the property is ready to move or under construction.
Transaction: Specifies if the property is new or being resold.
Type: Type of property (e.g., builder floor, apartment).
Per_Sqft: Price per square foot.
Steps Involved
Data Cleaning and Preprocessing:

Missing values were handled.
Categorical features like locality and furnishing were label-encoded for modeling.
Exploratory Data Analysis (EDA):

Insights were derived from visualizations showing the relationship between features (like area, locality, and BHK) and price.
It was observed that posh localities such as Punjabi Bagh, Lajpat Nagar, and Vasant Kunj had higher house prices.
Feature Scaling:

MinMaxScaler was applied to scale features like area and price for better model performance.
Model Building:

Two regression models were trained: Decision Tree Regressor and Random Forest Regressor.
Hyperparameter tuning was performed using GridSearchCV for optimal model parameters.
Model Evaluation:

The Random Forest Regressor outperformed the Decision Tree Regressor in terms of R² Score, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
Results
Random Forest achieved better accuracy (R²: 0.846) compared to Decision Tree (R²: 0.829).
Features like area, BHK, and locality played significant roles in determining house prices.
Conclusion
The project highlights the importance of locality and buyer preferences, such as the preference for new builder floor properties over apartments due to privacy and customization. The Random Forest model provided the most reliable predictions.

Future Scope
Enhancements could include:

Incorporating additional features like amenities and proximity to facilities.
Using geospatial analysis for improved locality-based insights.
Exploring ensemble methods for better accuracy.
This project demonstrates the practical application of machine learning in the real estate domain, providing actionable insights and reliable predictions.
