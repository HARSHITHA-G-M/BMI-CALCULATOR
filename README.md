# ⚖️ BMI Calculator Web App (AngularJS + HTML)

![GitHub repo size](https://img.shields.io/github/repo-size/HARSHITHA-G-M/BMI-CALCULATOR)
![GitHub last commit](https://img.shields.io/github/last-commit/HARSHITHA-G-M/BMI-CALCULATOR)
![GitHub watchers](https://img.shields.io/github/watchers/HARSHITHA-G-M/BMI-CALCULATOR?style=social)
![GitHub stars](https://img.shields.io/github/stars/HARSHITHA-G-M/BMI-CALCULATOR?style=social)

---

## 📘 Overview

This is a simple web-based **BMI (Body Mass Index) Calculator** built using **HTML** and **AngularJS**.  
The application allows users to enter their **weight** and **height**, calculates their BMI, and displays the corresponding **BMI category**.

---

## 🧠 How It Works

📋 The form has two inputs:
- 🏋️ Weight (in kilograms)
- 📏 Height (in centimeters)

▶️ A button triggers the calculation. The AngularJS controller:
- Uses the formula:  
  \[
  \text{BMI} = \frac{\text{weight}}{(\text{height in meters})^2}
  \]
- Converts height to meters by dividing by 100.
- Categorizes the BMI as:
  - Underweight
  - Normal
  - Overweight
  - Obese

---

## 🛠️ Tech Stack

| Tool        | Description                   |
|-------------|-------------------------------|
| 🌐 HTML      | Structure of the web page      |
| 🎨 CSS       | (Optional) Styling (if added)  |
| ⚙️ AngularJS | Logic & two-way data binding  |



📁 BMI-CALCULATOR/
│
├── bmi.html # Main HTML + AngularJS logic
└── README.md # Project overview


---

## 🚀 How to Use

1. 📥 Clone the repository:
```bash
git clone https://github.com/HARSHITHA-G-M/BMI-CALCULATOR.git
