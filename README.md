
#  Project Title:  
**Hyperparameter-Tuned SGD and Gradient Boosting for Mental Health Prediction**

###  Overview

This project aims to enhance the accuracy of mental health condition predictions using machine learning models like **Stochastic Gradient Descent (SGD)** and **Gradient Boosting (GB)**. The models are optimized with **hyperparameter tuning** and **Recursive Feature Elimination (RFE)** to improve decision-making in mental health support systems.

###  Technologies Used

- **Python** (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn)
- **Machine Learning Models:** SGDClassifier, GradientBoostingClassifier
- **Feature Selection:** Recursive Feature Elimination (RFE)
- **Model Tuning:** GridSearchCV
- **Web Framework:** Flask
- **Frontend:** HTML +CSS(optional)
- **Visualization:** Matplotlib, Seaborn

###  Project Structure
Final_year_project/
│
├── dataset/                      # Raw and cleaned datasets
├── model/                        # Saved ML models (pkl or joblib files)
├── templates/                    # HTML files for Flask (form and result)
├── static/                       # Static files (CSS, JS if any)
├── app.py                        # Flask web application
├── main.py                       # Model training script
├── requirements.txt              # Python packages
├── visuals/                      # Graphs and plots
└── README.md                     # Project documentation

###  How to Run the Project

1. Clone the repo:
   git clone https://github.com/thamilkumar/Final_year_project.git
   cd Final_year_project

2. Install dependencies:
   pip install -r requirements.txt

3. Train the model (if not already trained):
   python main.py  

4. Run the Flask web app:
   python app.py

5. Open the app in your browser:
   http://127.0.0.1:5000/


### Results
Accepts 15 categorical inputs via an HTML form
Uses a pre-trained ML model to predict mental health condition
Real-time prediction on local web interface
Feature selection with RFE
GridSearchCV used for tuning hyperparameters for better accuracy


###  Future Work
Deploy on cloud (e.g., Render, Heroku, AWS, or Azure)
Store user responses for analysis
Add user authentication and session tracking

### Author

**Thamilkumar**  
📧 [thamilkumar003@gmail.com](mailto:thamilkumar003@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/thamilkumar) | [GitHub](https://github.com/thamilkumar)
