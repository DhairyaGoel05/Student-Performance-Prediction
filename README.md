# Student Performance Prediction

## Overview
This is a Streamlit-based web application that predicts student performance based on various input factors such as study hours, previous scores, extracurricular activities, sleep hours, and sample question papers practiced. The app uses a machine learning model trained with Logistic Regression.

## Features
- **User-friendly Interface**: Built with Streamlit for an interactive experience.
- **Machine Learning Model**: Uses a pre-trained Logistic Regression model for predictions.
- **Preprocessing**: Data normalization and categorical encoding are applied before predictions.

## Installation
### Prerequisites
Ensure you have Python and the required libraries installed. You can install the dependencies using:
```bash
pip install -r requirements.txt
```

### Clone the Repository
```bash
git clone https://github.com/DhairyaGoel05/Student-Performance-Prediction.git
cd Student-Performance-Prediction
```

## Running the Application
```bash
streamlit run student_per.py
```

## Usage
1. Enter the required details such as study hours, previous scores, extracurricular activity participation, sleep hours, and the number of question papers solved.
2. Click on the **Predict Your Score** button.
3. The app will display the predicted student performance score.

## Screenshots
Below are screenshots of the Streamlit app:

![image](https://github.com/user-attachments/assets/a75597f8-6ec8-498d-88b9-19bf650a9200)

![image](https://github.com/user-attachments/assets/29ea3868-d32d-446d-a96b-3ebd10056a51)


## Project Structure
```
Student-Performance-Prediction/
│── student_per.py  # Main Streamlit application file
│── student_lr_model.pkl  # Pre-trained ML model
│── requirements.txt  # Required dependencies
│── screenshots/  # Folder containing app screenshots
└── README.md  # Project documentation
```

## Technologies Used
- **Python**
- **Streamlit**
- **Scikit-learn**
- **Pandas**
- **NumPy**

## Contributing
Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

## License
This project is licensed under the MIT License.

