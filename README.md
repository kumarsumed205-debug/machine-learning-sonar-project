
# Sonar Rock Mine Prediction

## Project Overview
This project  uses machine   lerning to classify sonar signals as rock or mine. The model is built using logistic regression and trained on a real world dataset.

---

## Dataset
The dataset contains 60 numerical features representing sonar signal frequencies and one output label.

Output values:
- R means Rock
- M means Mine

---

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit learn

---

## Model Used
- Logistic Regression
- Supervsed Learning
- Binary Classification

---

## Project Workflow
1 Data Collection  
2 Data Analysis  
3 Data Preprocessing  
4 Train Test Split  
5 Model  Training  
6 Model Evaluation  
7 Prediction System  

---

## How to Run

### Install Dependencies
```bash
pip install numpy pandas scikit-learn
```

### Run the Program
```bash
python sonar_prediction.py
```

---

## Model Performance
- Training Accuracy approximately 80 to 90 percent  
- Testing Accuracy approximately 70 to 85 percent  

---

## Example Prediction
```python
prediction = model.predict(input_data_reshaped)

if prediction[0] == 'R':
    print("The object is a Rock")
else:
    print("The object is a Mine")
```

---

## Project Structure
```
sonar project
 sonar_prediction.py
 sonar_data.csv
 README.md
```

---

## Features
- Simple and   beginner friendly  
- Real  world datasat  
- Easy to  understand workflow  
- Extendable project  

---

## Future Improvements
- Add graphical user interface  
- Deploy as web application  
- Use advanced machine learning models  
