# DataFix
DataFix – Autonomous Data Quality and Repair Engine

Detect. Diagnose. Repair. Validate. Trust.

DataFix is a Python-based data quality and repair application designed to automatically identify, analyse, and correct common errors in datasets. It helps users transform messy and inconsistent data into clean, reliable, and analysis-ready datasets.

📌 Problem Statement
Real-world datasets often contain errors that affect data analysis, reporting, and machine learning models.
Common data quality issues include:
- Missing values
- Duplicate records
- Incorrect data formats
- Inconsistent entries and spellings
- Invalid or unusual data values

These problems lead to unreliable results, poor decision-making, and increased manual data-cleaning effort.

💡 Our Solution
DataFix provides an automated solution for inspecting, detecting, and repairing data quality issues.
Users can upload CSV or Excel datasets, identify errors, apply automatic repairs, and validate the cleaned data through an interactive dashboard.

✨ Key Features
- 📂 Dataset Upload: Upload CSV and Excel files.
- 🔍 Error Detection: Automatically identify common data quality issues.
- 🛠️ Automatic Data Repair: Apply suitable repair techniques to detected errors.
- 🔄 Data Validation: Verify the dataset after repair.
- 📊 Quality Dashboard: Display dataset information and quality results.
- 📝 Explainability: Provide understandable information about detected issues and repairs.
- 📥 Report Generation: Generate downloadable reports for data quality analysis.

⚙️ Technology Stack
Technology| Purpose
Python| Core programming language
Pandas| Data processing and manipulation
Streamlit| Interactive web application
NumPy| Numerical operations
CSV / Excel| Dataset input and output

🔄 How DataFix Works
The application follows a step-by-step workflow:
1. Upload – Upload a CSV or Excel dataset.
2. Inspect – Analyse the uploaded dataset.
3. Detect – Identify missing values, duplicates, incorrect formats, and other issues.
4. Diagnose – Understand the detected data quality problems.
5. Repair – Automatically apply suitable corrections.
6. Validate – Check the dataset after repair.
7. Explain – Display information about the corrections.
8. Report – Generate downloadable data quality reports.

🏗️ Project Architecture

DataFix/
│
├── app.py
├── error_detection.py
├── data_repair.py
├── validation.py
├── explainability.py
├── report_generator.py
│
├── requirements.txt
├── README.md
│
└── sample_data/
    └── student_records.csv

Note: Adjust the folder structure above to match your actual GitHub repository files.

💻 Installation and Setup

Step 1: Clone the Repository

git clone https://github.com/YOUR-USERNAME/DataFix.git

Step 2: Navigate to the Project Folder

cd DataFix

Step 3: Install Required Libraries

pip install -r requirements.txt

Step 4: Run the Application

streamlit run app.py

Step 5: Open the Application

Open the local URL displayed in your terminal, usually:

http://localhost:8501

📊 Example: Before and After Data Cleaning

Before DataFix

student_id| name| age| city
1001| Alice| Missing| San Fransisco
1002| Bob| 19| NYC
1002| Bob| 19| New York
1003| Clara| twenty| Ldn

After DataFix

student_id| name| age| city
1001| Alice| 20| San Francisco
1002| Bob| 19| New York
1003| Clara| 20| London
Illustrative example of data repairs based on the project presentation.

Website link:
https://datafix-1.ai.studio/

🎯 Expected Impact
- Reduces manual data-cleaning effort.
- Improves dataset consistency.
- Helps produce reliable analytical results.
- Reduces errors in downstream machine learning workflows.
- Makes data corrections easier to understand and review.

🚀 Future Enhancements
- Support for larger datasets.
- Advanced anomaly detection.
- Improved data repair recommendations.
- Cloud database integration.
- Continuous data quality monitoring.
- More advanced reporting and audit features.

❤️ Acknowledgement
Developed as a hackathon project to address real-world data quality challenges through automated data inspection, diagnosis, repair, and validation.

⭐ Project Tagline
"Don't just clean data. Understand it, repair it and prove it."
