# CareerCompass-AI

AI-powered Career Guidance Platform with Resume Analysis, ATS Score, Skill Gap Detection, Job Matching, Interview Preparation, and Personalized Learning Roadmap.

# Architecture
CareerCompassAI/
│
├── app/
│   ├── pages/
│   │   ├── 1_Dashboard.py
│   │   ├── 2_Resume_Analyzer.py
│   │   ├── 3_ATS_Score.py
│   │   ├── 4_Skill_Gap.py
│   │   ├── 5_Job_Matcher.py
│   │   ├── 6_Interview.py
│   │   ├── 7_Learning_Roadmap.py
│   │   └── 8_Profile.py
│   │
│   ├── Home.py
│   ├── config.py
│   └── utils.py
│
├── backend/
│   ├── resume_parser/
│   ├── ats_engine/
│   ├── recommendation/
│   ├── llm/
│   ├── ml/
│   ├── interview/
│   └── database/
│
├── datasets/
│   ├── skills.csv
│   ├── jobs.csv
│   ├── courses.csv
│   ├── interview_questions.csv
│   └── salary.csv
│
├── models/
│   ├── resume_classifier.pkl
│   ├── salary_predictor.pkl
│   └── skill_model.pkl
│
├── uploads/
│
├── reports/
│
├── notebooks/
│
├── tests/
│
├── assets/
│   ├── logo.png
│   ├── banner.png
│   └── icons/
│
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
