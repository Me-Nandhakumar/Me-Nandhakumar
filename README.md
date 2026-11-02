#!/usr/bin/env python3
# ─────────────────────────────────────────────────────────
#  nandhakumar.py  |  AI & ML Engineer Profile
# ─────────────────────────────────────────────────────────

class MLEngineer:

    def __init__(self):
        self.name        = "Nandhakumar S"
        self.role        = ["Python Developer", "ML Engineer", "Data Science Enthusiast"]
        self.location    = "📍 Bangalore, Karnataka, India"
        self.education   = "B.Tech — AI & Data Science | Mahendra College, Salem (CGPA: 7.20)"
        self.email       = "nandhakumar.s.jnandhu@gmail.com"
        self.portfolio   = "https://me-nandhakumar.github.io/MY_PORTFOLIO/"
        self.status      = "🟢 Open to Work — ML Engineer | Python Developer | Data Analyst"

    def skills(self):
        return {
            "Languages"   : ["Python", "SQL", "HTML", "CSS"],
            "ML / AI"     : ["Supervised Learning", "Unsupervised Learning",
                             "Classification", "Regression", "Predictive Analytics"],
            "Libraries"   : ["Pandas", "NumPy", "Matplotlib", "Scikit-learn", "XGBoost"],
            "Tools"       : ["Jupyter", "Google Colab", "VS Code", "PyCharm",
                             "MySQL Workbench", "GitHub", "Git", "Excel", "Flask"],
            "Concepts"    : ["Data Preprocessing", "Feature Engineering",
                             "Model Evaluation", "EDA", "Data Cleaning", "ETL"],
        }

    def projects(self):
        return [
            {"name": "NammaPred — Bengaluru Metro Intelligence", "metric": "R² score = 0.96"},
            {"name": "Fake Profile Detection",    "metric": "94.9% accuracy"},
            {"name": "CareHub Hospital System",   "metric": "~80% manual effort saved"},
            {"name": "Gold Price Prediction",     "metric": "R² score = 0.84"},
            {"name": "Customer Care Chatbot",     "metric": "Flask + Python"},
        ]

    def fun_fact(self):
        return "I debug with print() and I'm proud of it 😄"

me = MLEngineer()
print(f"👋 Hi! I'm {me.name} — {me.status}")
