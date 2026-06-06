# Car Price Prediction Using Linear Regression From Scratch

This project implements Linear Regression from scratch using NumPy to predict used car prices based on vehicle features such as age, mileage, and other available attributes.

The objective of this project was to understand the mathematics behind machine learning algorithms rather than rely on pre-built libraries. The model was trained using Gradient Descent, and the cost function was implemented manually.

Key concepts demonstrated:

* Data preprocessing using Pandas
* Feature scaling
* Linear Regression from scratch
* Gradient Descent optimization
* Model evaluation and visualization

The model showed relatively high prediction error because used car prices depend on many factors that were not available in the dataset, such as vehicle condition, accident history, service records, location, and market demand. Despite this limitation, the project successfully demonstrates the complete implementation of a machine learning model from first principles.

Technologies Used:

* Python
* NumPy
* Pandas
* Matplotlib

This project was built as part of my machine learning learning journey to gain a deeper understanding of how regression models work internally.


To keep the focus on understanding and implementing Linear Regression from scratch, only a small set of numerical features (year, odometer reading, and car age) was used in this project. Many additional features available in the dataset, such as manufacturer, model, fuel type, transmission, and vehicle condition, were intentionally excluded to avoid introducing categorical feature encoding and additional preprocessing complexity. The primary objective of this project was to learn the fundamentals of feature scaling, gradient descent, cost optimization, and model evaluation rather than maximize predictive performance.
