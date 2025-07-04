# 🎓 EduSpend — Budget Planner (Deployment Repo)

This is the **Streamlit deployment repository** for the EduSpend project. It predicts a student's **Total Cost of Attendance (TCA)** and **Affordability Tier** for international education programs based on inputs like country, city, degree level, tuition, rent, and insurance.

---

## 🚀 Live App

🔗 [Click here to try the deployed app](https://cp30-deployment-aua6c32vdcaoenfdbqmkty.streamlit.app/)

---

## 💻 How to Run Locally

```bash
# Step 1: Clone the repository
git clone https://github.com/yadavLakshay/CP30-deployment.git
cd CP30-deployment

# Step 2: (Optional) Create virtual environment
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate

# Step 3: Install required packages
pip install -r requirements.txt

# Step 4: Run the app
streamlit run app.py
```

---

## 🗂 Folder Structure

```
CP30-deployment/
│
├── app.py                      # Main Streamlit app
├── requirements.txt            # Deployment dependencies
├── deployment_models/          # Trained regressor and classifier (.pkl)
├── preprocessing/              # Saved preprocessing pipeline (.pkl)
├── EDU_SPEND.ipynb             # Notebook with inference logic (optional)
└── README.md                   # You're here
```

---

## 📦 Source Project

This deployment is based on my original submission to the SDS-CP030 EduSpend Challenge.  
🔗 [Full submission with EDA, modeling, and MLflow tracking](https://github.com/yadavLakshay/SDS-CP030-edu-spend/tree/main/submissions/team-members/lakshay-yadav)

---
