Solar Challenge Week 1
This repository contains the code and analysis for the Week 1 tasks of the Solar Challenge, focusing on setting up a development environment, performing EDA on solar datasets, and comparing solar potential across countries.
Folder Structure
├── .vscode/
│ └── settings.json
├── .github/
│ └── workflows
│ ├── ci.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
├── notebooks/
│ ├── **init**.py
│ └── README.md
├── tests/
│ ├── **init**.py
└── scripts/
├── **init**.py
└── README.md

Environment Setup
To reproduce the development environment, follow these steps:

Clone the Repository:
git clone https://github.com/<your-username>/solar-challenge-week1.git
cd solar-challenge-week1

Create a Virtual Environment:
python -m venv venv
source venv/bin/activate # On Windows: venv\Scripts\activate

Install Dependencies:
pip install -r requirements.txt

Verify Setup:
python --version
pip list

Running the CI Pipeline
The GitHub Actions workflow (.github/workflows/ci.yml) automatically runs on every push to the main or setup-task branches. It:

Checks out the repository.
Sets up Python 3.8.
Installs dependencies from requirements.txt.

Contributing

Create a new branch: git checkout -b <branch-name>.
Make changes and commit: git commit -m "description".
Push to GitHub: git push origin <branch-name>.
Open a Pull Request to merge into main.
