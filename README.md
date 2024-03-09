# ML-supervised-learning
The project aims to develop predictive models using supervised machine learning algorithms.

About the dataset:
This dataset contains information about delivery transactions and various factors associated with them. Here's a brief description:

* ID: Unique identifier for each delivery transaction.
* Delivery_person_ID: Identifier for the delivery person.
* Delivery_person_Age: Age of the delivery person.
* Delivery_person_Ratings: Ratings of the delivery person.
* Restaurant_latitude: Latitude of the restaurant from which the delivery originated.
* Restaurant_longitude: Longitude of the restaurant from which the delivery originated.
* Delivery_location_latitude: Latitude of the delivery location.
* Delivery_location_longitude: Longitude of the delivery location.
* Order_Date: Date when the order was placed.
* Time_Orderd: Time when the order was placed.
* Time_Order_picked: Time when the order was picked up by the delivery person.
* Weatherconditions: Weather conditions at the time of delivery.
* Road_traffic_density: Density of road traffic during delivery.
* Vehicle_condition: Condition of the delivery vehicle.
* Type_of_order: Type of order (e.g., food delivery, parcel delivery).
* Type_of_vehicle: Type of vehicle used for delivery.
* multiple_deliveries: Indicator of whether multiple deliveries were made during the trip.
* Festival: Indicator of whether the delivery occurred during a festival.
* City: City where the delivery took place.
* Time_taken(min): Time taken for the delivery, in minutes.

     This dataset provides valuable insights into the factors influencing delivery times and can be used to build predictive models for estimating delivery durations, optimizing delivery routes, and improving overall efficiency in delivery operations.

  Tasks:

1. Data Preprocessing: Clean and preprocess the dataset by handling missing values, encoding categorical variables, scaling numerical features, and performing any necessary transformations.
2. Exploratory Data Analysis (EDA): Explore the dataset to gain insights into the distribution of features, relationships between variables, and identify patterns that may inform the modeling process.
3. Model Selection: Supervised learning algorithms such as linear regression, decision trees, random forests regressor, and gradient boosting methods such as XGBoost had been used.
4. Model Training: Trained multiple models using the chosen algorithms on the training data, optimizing hyperparameters as needed to improve model performance.
5. Model Evaluation: Evaluated the trained models using appropriate evaluation metrics such as mean absolute error (MAE), mean squared error (MSE), root mean squared error (RMSE), R-squared (R2) score.
6. Model Comparison: Compared the performance of different models based on evaluation metrics to identify the best-performing model for the task.
7. Hyperparameter Tuning: Fine-tune the hyperparameters of selected models to further improve performance.
8. Model Interpretation: Interpret the trained models to understand the importance of features, identify key factors driving predictions, and gain actionable insights from the results.

  Outcome:
  
In conclusion, the food delivery prediction model was developed using XGBoost, achieving an impressive R2 score of 0.82. Moving forward, potential enhancements include identifying the best features, conducting additional feature engineering, and exploring other optimization techniques to further improve the model's performance and accuracy. These steps will contribute to fine-tuning the model and unlocking its full potential in predicting food delivery timings accurately.
