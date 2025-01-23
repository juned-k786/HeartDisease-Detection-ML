# Heart Disease Prediction 🫀

![Project Logo](Background.jpg)

A machine learning-based web application to predict the likelihood of heart disease based on user inputs such as age, chest pain type, and maximum heart rate achieved.

---

## Table of Contents 📚
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Live Demo](#live-demo)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction 🚀
This project is a web application that uses a machine learning model to predict the presence of heart disease. The model is trained on a dataset containing features like age, chest pain type, and maximum heart rate. The application is built using Flask for the backend, HTML/CSS for the frontend, and a pre-trained logistic regression model for predictions.

---

## Features ✨
- **User-friendly Interface**: Simple and intuitive form for inputting data.
- **Real-time Prediction**: Instantly predicts the likelihood of heart disease.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.
- **Error Handling**: Provides clear error messages for invalid inputs.

---

## Technologies Used 🛠️
- **Frontend**: HTML, CSS, JavaScript (jQuery)
- **Backend**: Flask (Python)
- **Machine Learning**: Scikit-learn (Logistic Regression)
- **Model Serialization**: Joblib
- **Deployment**: (Add deployment platform if applicable, e.g., Heroku, AWS, etc.)

---

## Installation 🛠️
To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/juned-k786/HeartDisease-Detection-ML.git
   cd heart-disease-prediction
Set up a virtual environment:

bash
Copy
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
pip install -r requirements.txt
Run the Flask application:

bash
Copy
python app.py
Open your browser and navigate to http://127.0.0.1:5000.

Usage 🖥️
Enter the required details:

Age: Your age in years.

Chest Pain Type: A value between 0 and 3 representing the type of chest pain.

Max Heart Rate Achieved: Your maximum heart rate during exercise.

Click the Predict button to see the result.

Live Demo 🌐
Live Demo 

Contributing 🤝
Contributions are welcome! If you'd like to contribute, please follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature/YourFeatureName).

Commit your changes (git commit -m 'Add some feature').

Push to the branch (git push origin feature/YourFeatureName).

Open a pull request.

License 📄
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments 🙏
Dataset: UCI Heart Disease Dataset

Flask Documentation: Flask

Scikit-learn Documentation: Scikit-learn

Made with ❤️ by Mohd Juned Khan
