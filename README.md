# AI Recruitment Agent

AI Recruitment Agent is an intelligent platform designed to automate and optimize the hiring process. It parses resumes in PDF and DOCX formats, extracts key candidate information, and evaluates applicants against job descriptions using AI and LLM-powered analysis. The platform reduces manual screening effort, improves recruitment efficiency, and helps HR teams make data-driven hiring decisions.

## Features

### Resume Parsing & Evaluation
Automatically extracts candidate information (skills, experience, education) from PDF and DOCX resumes.
Compares candidate profiles against job descriptions to identify top matches.
Uses LLM agents for intelligent text analysis and insights.

### HR Dashboard
Interactive dashboard to track candidate batches and evaluation status.
Filter, sort, and export candidate data for reporting or further analysis.
Secure authentication to protect sensitive recruitment data.

### Automation & Analytics
Reduces manual resume screening effort by 50%.
Provides data-driven insights to improve hiring decisions.
Batch processing to handle multiple resumes efficiently.

## Technology Stack
Backend: Python, FastAPI, PostgreSQL
Frontend: Streamlit for dashboard interface
AI & Automation: Large Language Model (LLM) integration, automated resume parsing
Data Processing: Pandas for data handling and analysis

## Installation & Setup
Prerequisites
Python 3.8+
pip package manager
Virtual environment (recommended)

## Setup
1- Clone the repository:
git clone https://github.com/YourUsername/ai-recruitment-agent.git
cd ai-recruitment-agent

2- Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

3- Install dependencies:
pip install -r requirements.txt

4- Set up environment variables by creating a .env file (if required for AI agents or database credentials):
DATABASE_URL=your_database_url
LLM_API_KEY=your_api_key
JWT_SECRET_KEY=your_secret_key

## Usage
1- Start the FastAPI backend:
uvicorn app:app --reload

2- In a separate terminal, run the Streamlit dashboard:
streamlit run streamlit.py

3- Open your browser and navigate to http://localhost:8501 to access the dashboard.
4- Upload resumes, evaluate candidates, and explore the dashboard features.

## Impact
Reduces manual HR screening workload by 50%.
Improves accuracy and efficiency in candidate evaluation.
Scalable solution for multiple job roles and departments.

## Future Enhancements
Integration with external ATS/job boards for automated candidate imports.
Advanced candidate ranking and scoring using ML models.
AI-driven interview question suggestions and candidate feedback generation.
Real-time analytics dashboards and reporting.

## License

This project is licensed under the MIT License.
