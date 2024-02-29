Poetry code to install poetry.lock and pyproject.toml files
$ poetry new poetry-tutorial-project
Then clean out the directory to fit your preferred format. Example below

Below is an example of a structured Python project directory for a data analysis project:

```
data-analysis-project/
│
├── data/                # Folder to store datasets
│   ├── customer_data.csv      # Sample dataset containing customer information
│   └── sales_data.csv         # Sample dataset containing sales information
│
├── notebooks/           # Folder to store Jupyter notebooks
│   ├── exploratory_analysis.ipynb    # Notebook for exploratory data analysis
│   └── data_preprocessing.ipynb       # Notebook for data preprocessing
│
├── scripts/             # Folder to store Python scripts
│   ├── data_loader.py          # Script to load datasets
│   ├── data_preprocessing.py   # Script for data preprocessing
│   └── analysis_utils.py       # Script containing utility functions for analysis
│
├── visualizations/      # Folder to store visualizations
│   ├── customer_segmentation.png    # Visualization of customer segmentation
│   └── sales_trend.png              # Visualization of sales trend over time
│
├── reports/             # Folder to store project reports
│   ├── project_summary.pdf          # Summary report of the project
│   └── analysis_findings.docx       # Detailed findings and analysis report
│
├── requirements.txt     # File listing all the Python dependencies for the project
├── README.md            # Markdown file explaining the project overview, setup, and usage
└── .gitignore           # File to specify which files and directories to ignore in version control
```

Explanation of each folder and file:

- **data/**: This folder contains datasets used for analysis.
- **notebooks/**: Contains Jupyter notebooks used for exploratory data analysis, data preprocessing, and any other analysis tasks.
- **scripts/**: Contains Python scripts for various tasks such as loading data, preprocessing, and utility functions.
- **visualizations/**: Stores visualizations generated during the analysis process.
- **reports/**: Contains project reports summarizing findings, insights, and analysis.
- **requirements.txt**: File listing all the Python dependencies required to run the project.
- **README.md**: Markdown file providing an overview of the project, setup instructions, and usage guidelines.
- **.gitignore**: Specifies which files and directories should be ignored in version control (e.g., temporary files, data files).

This directory structure helps organize different aspects of the project, making it easy to navigate, collaborate, and maintain.
