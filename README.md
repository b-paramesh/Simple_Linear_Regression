 💵 Tip Amount Prediction using Linear Regression

## 📌 Project Overview
This project demonstrates a **Linear Regression model** to predict the **tip amount** based on the **total bill** using the popular **Tips dataset**.

An interactive **Streamlit web application** is built with:
- Model training
- Performance evaluation
- Data visualization
- Real-time prediction
- Custom CSS-based UI styling

---

## 🧠 Business Problem
Restaurants often want to understand:
- How tip amounts vary with bill size
- Expected tip value for different customer bills
- Customer tipping behavior patterns

👉 **Objective:**  
Build a machine learning model that predicts the **tip amount** given the **total bill**, and present it through an interactive dashboard.

---

## 📊 Dataset Information
- **Dataset Name:** Tips Dataset  
- **Source:** Seaborn built-in dataset  

### Features Used
| Feature | Description |
|------|------------|
| total_bill | Total bill amount paid by customer |
| tip | Tip given by customer (target variable) |

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Seaborn**
- **Matplotlib**
- **Scikit-learn**
- **Streamlit**
- **HTML & CSS (UI Styling)**

---

## 🔍 Project Workflow
1. Load dataset using Seaborn
2. Perform basic data exploration
3. Select relevant features
4. Split data into training and testing sets
5. Apply feature scaling
6. Train Linear Regression model
7. Evaluate model using regression metrics
8. Visualize regression line and data points
9. Predict tip amount using user input
10. Display results in a styled Streamlit interface

---

## 🤖 Machine Learning Model
- **Algorithm:** Linear Regression
- **Scaling:** StandardScaler
- **Train-Test Split:** 80% / 20%

---

## 📈 Model Evaluation Metrics
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**
- **R² Score**
- **Adjusted R² Score**

These metrics help assess the accuracy and reliability of the regression model.

---

## 📊 Visualizations
- Scatter plot of **Total Bill vs Tip**
- Regression line overlay
- Styled metric cards for performance values

---

## 🎨 User Interface
- Gradient background
- Card-based layout
- Styled metric containers
- Interactive slider for prediction
- Custom CSS integration

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
2️⃣ Create and activate virtual environment
python -m venv venv
venv\Scripts\activate
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Run Streamlit app
streamlit run app.py
📂 Project Structure
├── app.py
├── style.css
├── requirements.txt
└── README.md
⚠️ Model Limitations
Assumes a linear relationship between bill and tip

Does not account for factors like service quality or party size

Limited to a single input feature

🔮 Future Enhancements
Multiple Linear Regression (add size, day, time)

Non-linear regression models

Confidence interval visualization

Deployment on Streamlit Cloud

👨‍💻 Author
Paramesh B
Machine Learning & Data Science Enthusiast

🔗 GitHub: https://github.com/b-paramesh

⭐ Support
If you find this project useful, please give it a ⭐ on GitHub!


---

## ✅ How to add this README to your repo

```bash
notepad README.md
Paste → Save → then:

git add README.md
git commit -m "Add README for Tip Prediction Linear Regression app"
git push
