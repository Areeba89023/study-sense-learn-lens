# Study Sense Learn Lens

## Student Habits Analysis

### Project Overview

Study Sense Learn Lens is a data analytics project that explores factors associated with university students' academic performance.

The project uses Python, Pandas, Matplotlib, Seaborn, and Jupyter Notebook to analyse relationships between student characteristics, study habits, educational background, examination preparation, and final grades.

The project demonstrates exploratory data analysis (EDA), data visualisation, interpretation of analytical findings, potential applications of Artificial Intelligence, and responsible data handling.

---

## Project Objectives

The main objectives of this project are to:

- Explore and understand the student dataset.
- Perform exploratory data analysis (EDA).
- Identify patterns and relationships associated with academic performance.
- Create meaningful data visualisations.
- Develop data-driven insights.
- Identify potential opportunities for Artificial Intelligence.
- Evaluate the strengths and limitations of the analytical approach.
- Explain data collection, cleaning, storage, and processing practices.
- Apply appropriate data governance and compliance principles.

---

## Dataset

The dataset contains information about **145 university students** with **33 attributes** relating to demographics, educational background, study habits, examination preparation, and academic performance.

Important variables include:

- Student Age
- Gender
- Scholarship Type
- Weekly Study Hours
- Reading Frequency
- Midterm Exam Preparation
- Parents' Education
- Final Grade

The dataset is stored in the `data/` directory.

---

## Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Git
- GitHub
- Generative AI / ChatGPT for supported ideation and data storytelling

---

## Project Structure

```text
study-sense-learn-lens/
│
├── analysis.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── data/
    └── StudentsPerformance_with_headers.csv
Data Analysis

The analysis notebook performs exploratory analysis of the student dataset.

The analysis includes:

Dataset inspection
Data type and structure checks
Missing-value assessment
Descriptive statistics
Categorical variable analysis
Numerical variable analysis
Relationship analysis
Data visualisation
Interpretation of analytical findings

The visualisations are used to communicate patterns and relationships in an accessible way.

Potential AI Solution

The analysis identifies an opportunity for Artificial Intelligence to support educational decision-making.

A potential AI application would be a student success prediction and early-warning system.

A machine learning model could use relevant student characteristics, study habits, examination preparation, and previous academic indicators to estimate the likelihood of a student achieving a particular level of academic performance.

Such a system could help educators identify students who may require additional academic support.

However, predictions should be treated as decision-support information rather than definitive judgements about individual students. Human review would remain important.

Generative AI Use

Generative AI was used to support ideation and data storytelling during the project.

Generative AI tool used: ChatGPT by OpenAI.

ChatGPT was used to help:

Generate ideas for presenting analytical findings.
Develop possible data-storytelling narratives.
Identify potential AI applications for the dataset.
Structure explanations of analytical approaches.
Consider limitations and responsible data practices.

The final analysis, interpretation of the dataset, visualisations, and project decisions remain based on the project work and dataset rather than being accepted blindly from generated content.

Evaluation of the Analytical Approach

Exploratory Data Analysis and visualisation were selected because the project aims to understand patterns and relationships within the dataset before considering predictive modelling.

Why EDA and visualisation were appropriate
EDA helps understand the structure and characteristics of the dataset.
Descriptive statistics provide an initial understanding of the variables.
Visualisations make patterns and comparisons easier to communicate.
The approach is suitable for identifying potential relationships that could later be investigated using statistical or machine learning techniques.
Alternative approaches

Other approaches could include:

Statistical hypothesis testing
Correlation analysis
Regression analysis
Classification models
Clustering techniques

Machine learning could be considered if the objective were to build a predictive system rather than primarily explore and communicate patterns.

Limitations

The dataset is relatively small, containing 145 students.

Therefore:

Findings may not generalise to all university students.
Relationships observed in the data should not automatically be interpreted as causal relationships.
Some potentially important factors may not be represented in the dataset.
A larger and more diverse dataset would be required for a reliable production-level predictive model.
Any future AI system would require additional validation, fairness assessment, and monitoring.
Data Collection, Cleaning, Storage and Processing

The dataset was provided as a structured CSV file and imported into Python for analysis.

The data workflow involved:

Loading the dataset into Pandas.
Inspecting the dataset structure and variables.
Checking data types and data quality.
Assessing missing or inconsistent values.
Preparing the data for analysis and visualisation.
Processing the data using Python and Pandas.
Generating analytical outputs and visualisations in Jupyter Notebook.

The CSV format provides a simple and portable way to store tabular data, while Pandas provides suitable tools for cleaning, transforming, and analysing the dataset.

For a production environment, additional controls such as access restrictions, audit trails, secure storage, and formal data-retention policies would be appropriate.

Data Governance and Compliance

Responsible data handling is important when analysing information relating to students.

Good data governance practices include:

Collecting only data that is relevant to the analytical purpose.
Avoiding unnecessary personal or sensitive information.
Maintaining data accuracy and quality.
Restricting access to authorised users.
Protecting stored data from unauthorised access.
Documenting how data is collected, processed, and used.
Applying appropriate retention and deletion policies.
Using anonymised or pseudonymised data where appropriate.
Considering privacy and ethical implications before using data for AI or automated decision-making.

Any future implementation involving identifiable student information should comply with applicable privacy, institutional, and data-protection requirements.

Responsible AI Considerations

If an AI system were developed from this dataset, its predictions should be used carefully.

Important considerations include:

Bias and fairness
Data quality
Model accuracy
Transparency
Explainability
Privacy
Human oversight
Appropriate use of predictions

AI predictions should support educators rather than automatically determine educational outcomes for students.

Conclusion

This project demonstrates how data analytics can be used to explore student habits and academic performance.

Through exploratory data analysis and visualisation, the project provides a structured approach for identifying patterns in the dataset.

The analysis also identifies a potential opportunity for Artificial Intelligence through student success prediction and early-warning support.

The project considers not only the analytical techniques used but also their limitations, data-handling practices, governance requirements, and responsible use of AI.

How to Run the Project

Clone the repository:

git clone https://github.com/Areeba89023/study-sense-learn-lens.git

Move into the project directory:

cd study-sense-learn-lens

Create a virtual environment:

python -m venv venv

Activate the virtual environment in Windows PowerShell:

.\venv\Scripts\Activate.ps1

Install the required packages:

pip install -r requirements.txt

Start Jupyter Notebook:

jupyter notebook

Open:

analysis.ipynb
Author

Areeba Ashraf
