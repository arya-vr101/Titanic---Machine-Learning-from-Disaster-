#  Titanic Survival Prediction Project
### 🧠 Machine Learning + Tkinter GUI Deployment

---

##  Project Overview
This project predicts whether a passenger survived the Titanic disaster using machine learning.  
The model is built with **Logistic Regression** and deployed as a **Tkinter GUI desktop app**.  
It demonstrates an end-to-end data science pipeline — from preprocessing to deployment.

---

##  Objective
Build and deploy a machine learning model that predicts the survival of Titanic passengers  
based on their personal and ticket details.

---

##  Workflow

### 1️⃣ Data Collection
Dataset: `titanic.csv`  
Contains fields such as:

Pclass, Sex, Age, SibSp, Parch, Fare, Embarked, Survived




---

### 2️⃣ Data Preprocessing
- Handle missing values (`Age`, `Embarked`)
- Convert categorical data to numeric (`Sex`, `Embarked`)
- Select useful features for training
- Normalize numeric data if necessary

---

### 3️⃣ Model Training
Algorithm used: **Logistic Regression**

Steps performed:

• Load dataset  
• Clean and encode data  
• Split into train-test sets  
• Train Logistic Regression model  
• Evaluate accuracy  
• Save model as titanic_model.pkl

---

### 4️⃣ GUI Deployment (Tkinter)
Interface: **Tkinter Desktop App**

User inputs:

• Passenger Class (1 / 2 / 3)  
• Sex (Male / Female)  
• Age  
• Siblings/Spouses (SibSp)  
• Parents/Children (Parch)  
• Fare  
• Embarked Port (S / C / Q)

Output:

✅ Passenger Survived
❌ Passenger Did Not Survive
(Survival Probability: 0.85)

