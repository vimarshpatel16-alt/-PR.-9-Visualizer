📊 DATA ANALYSIS & VISUALIZATION PROGRAM
🐍 A Python Project Using Pandas, NumPy, Matplotlib & Seaborn
<p>
  <img src="https://img.shields.io/badge/Python-Programming-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge" alt="Matplotlib">
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Charts-4C72B0?style=for-the-badge" alt="Seaborn">
</p>

An interactive, menu-driven application for loading, exploring, cleaning, analyzing, and visualizing data using Python.
</div>

📑 Table of Contents
- 🌟 Project Overview
- 🎯 Project Objectives
- 🛠️ Technologies Used
- ✨ Key Features
- 📂 Project Structure
- ⚙️ Installation and Setup
- 🚀 How to Run the Project
- 📊 How the Program Works
- 📁 Dataset Requirements
- 🧪 Example Workflow
- 🛡️ Error Handling and Limitations
- 🎓 Learning Outcomes
- 🔮 Future Enhancements
- 🏁 Conclusion
- 👨‍🎓 Project Information
🌟 Project Overview
The Data Analysis & Visualization Program is a Python-based project designed to make common data-analysis tasks easier through a simple menu-driven interface. It brings together popular Python libraries to help users load a dataset, understand its structure, handle missing values, calculate statistics, perform numerical operations, and create meaningful visualizations.

The program is implemented using a Python class named StudentSalesAnalyze. The user selects an operation from the menu and follows the prompts to perform the required task.

This project is useful for students who want practical experience with Python programming, data manipulation, numerical computing, statistics, and data visualization.
💡 Why is this project useful?
- 📥 Makes it easier to load and inspect tabular datasets.
- 🧹 Provides options to identify and handle missing values.
- 📈 Calculates useful descriptive statistics.
- 🔢 Uses NumPy for numerical analysis.
- 📊 Creates charts that help communicate patterns in data.
- 💾 Allows the latest visualization to be saved for later use.
🎯 Project Objectives
The main objectives of this project are:
1. 📂 To load data from a CSV file using Pandas.
2. 🔍 To inspect rows, columns, and data types.
3. 🧹 To identify and manage missing values.
4. 📐 To calculate descriptive statistics for numerical data.
5. 🔢 To use NumPy for array-based calculations.
6. 🔗 To combine or split datasets where required.
7. 📊 To create different types of charts and visualizations.
8. 💾 To save the generated visualization in a selected format.
9. 🧠 To apply Python programming concepts in a practical project.
10. 🎓 To build confidence in data analysis using commonly used Python libraries.
🛠️ Technologies Used
🧰 Technology	🎯 Purpose
🐍 Python	Main programming language used to build the application
🐼 Pandas	Loading, exploring, cleaning, and manipulating tabular data
🔢 NumPy	Numerical calculations and array operations
📉 Matplotlib	Creating and saving charts
🌊 Seaborn	Creating statistical visualizations such as a correlation heatmap
📓 Jupyter Notebook	Running the project interactively, cell by cell


✨ Key Features
1. 📥 Load Dataset
- Loads a dataset from a CSV file path entered by the user.
- Reads the file into a Pandas DataFrame.
- Displays the first five rows to help the user confirm that the data loaded correctly.
2. 🔍 Explore Dataset
Provides options to inspect the dataset, including:
- head() — displays the first rows.
- tail() — displays the last rows.
- Column names — shows the available fields.
- Data types — identifies the type of each column.
- Dataset information — provides a general overview of the DataFrame.
3. 🔗 Combine and Split Data
- Combines the rows of the current dataset with another CSV dataset.
- Splits a dataset into two parts for inspection.
- Can save the combined data as merged_dataset.csv.
Note: The merge operation uses row-wise concatenation with pd.concat(). It does not match records using a common key.

4. 🧹 Handle Missing Values
The program provides options to work with missing data:
- 🔎 Display rows containing missing values.
- 📊 Fill missing numeric values using column means.
- 🗑️ Remove rows containing missing values.
- ✍️ Replace missing values with a value supplied by the user.
Why is this important? Missing data can affect calculations and visualizations. Checking it before analysis helps users understand the quality of their dataset.
5. 📐 Descriptive Statistics
For numeric columns, the program can display statistical information such as:
- 📌 Mean and other summary statistics.
- 📏 Standard deviation.
- 📊 Variance.
- 🔢 Other descriptive measures supported by Pandas.
These values help users understand the distribution and spread of numeric data.
6. 📊 Data Visualization
The program supports several visualization options:
📈 Chart Type	💡 Typical Use
📊 Bar chart	Comparing values across categories
📉 Line chart	Showing changes across an ordered sequence
🔵 Scatter plot	Exploring the relationship between two numeric variables
🥧 Pie chart	Showing proportions of categories
🌡️ Correlation heatmap	Viewing correlations between numeric variables
📶 Histogram	Understanding the distribution of numeric values
📚 Stack plot	Displaying how multiple series contribute to a total


Choose columns that exist in the dataset and are suitable for the selected chart type.
7. 💾 Save Visualization
- Saves the most recently created chart.
- Supports PNG, JPG/JPEG, and PDF formats.
- Helps include charts in reports, presentations, or project demonstrations.
8. 🔢 NumPy Numeric Analysis
For a selected numeric column, the program can show:
- Array values.
- Total or sum.
- Average or mean.
- Maximum value.
- Minimum value.
This feature demonstrates how NumPy can support numerical work alongside Pandas.
📂 Project Structure
A suggested folder layout is:
Data-Analysis-Visualization/
│
├── 📓 pr 9.ipynb             # Main Jupyter Notebook
├── 📄 README.md              # Project documentation
├── 📊 sample_data.csv        # Dataset (CSV format)
├── 📈 charts/                # Optional folder for saved charts
└── 📄 merged_dataset.csv     # Optional output from combining datasets
File names shown above are examples. Keep the names and locations that match your actual project files.

⚙️ Installation and Setup
✅ Step 1: Install Python
Install a compatible version of Python on your computer. On Windows, enable “Add Python to PATH” during installation if that option is shown.

Verify the installation in Command Prompt:
python --version
✅ Step 2: Install Required Libraries
Run this command in Command Prompt or your terminal:
python -m pip install pandas numpy matplotlib seaborn notebook
✅ Step 3: Check Jupyter Notebook
Start Jupyter Notebook using:
jupyter notebook
If the command is not recognized, try:
python -m notebook
🚀 How to Run the Project
1. 📁 Place the notebook and dataset in an easy-to-find folder.
2. 💻 Open Command Prompt or a terminal in that folder.
3. ▶️ Start Jupyter Notebook.
4. 📓 Open pr 9.ipynb.
5. 🧩 Run the code cell.
6. 🔢 Select the required menu option.
7. 📂 Enter the correct CSV file path when requested.
8. 📊 Review the output, statistics, or generated chart.
9. 💾 Save the visualization if needed.
10. 🚪 Select the exit option when finished.
🪟 Example file path on Windows
C:\Users\YourName\Documents\sample_data.csv
Replace YourName and the file name with your own details. The example path is only for guidance.
📊 How the Program Works
The general workflow is:
        🚀 Start Program
               |
               v
        📥 Load CSV Dataset
               |
               v
        🔍 Explore the Data
               |
               v
       🧹 Clean Missing Values
               |
               v
      📐 Calculate Statistics
               |
               v
       🔢 Perform NumPy Analysis
               |
               v
        📊 Create a Visualization
               |
               v
         💾 Save the Chart
               |
               v
          🏁 Exit Program
The user can choose operations from the menu as needed; this diagram represents a suggested analysis workflow, not a requirement to perform every step in this exact order.
📁 Dataset Requirements
The project uses pd.read_csv(), so it expects a CSV file as input.
📌 Important: Excel .xls files
If your dataset is named sample_data.xls, convert it before loading:
1. Open the file in Microsoft Excel.
2. Select File → Save As.
3. Choose CSV (Comma delimited) (*.csv).
4. Save the converted file.
5. Enter the new .csv path in the program.
✅ Recommended dataset format
- The first row should contain column headings.
- Numeric columns should contain values suitable for mathematical calculations.
- Use valid column names when prompted.
- Check for missing values before calculating statistics.
- Select chart types appropriate to the columns being analyzed.
🧪 Example Workflow
A typical demonstration of the project can follow these steps:
1. 📥 Load a CSV dataset.
2. 🔍 Display the first and last rows.
3. 🧾 Review the column names and data types.
4. 🧹 Check for missing values.
5. 🛠️ Fill or remove missing values if appropriate.
6. 📐 Display descriptive statistics.
7. 🔢 Select a numeric column for NumPy analysis.
8. 📊 Create a suitable chart.
9. 💾 Save the chart in PNG, JPG, or PDF format.
10. 🏁 Exit the program.
This sequence is suitable for demonstrating the major data-analysis stages during a practical exam or project presentation.
🛡️ Error Handling and Limitations
The program is designed to provide messages for common issues, but the user should still enter valid inputs.
- ⚠️ Dataset not loaded: Load a dataset before selecting operations that require one.
- 📂 Incorrect file path: Check the spelling and location of the CSV file.
- 🧾 Invalid column name: Enter a column name that exists in the loaded dataset.
- 🔢 Non-numeric column: Numerical calculations require suitable numeric data.
- 🧹 Missing values: Check whether the selected column contains missing or empty values.
- 📊 Chart errors: Some charts require particular column types or multiple data series.
- 📚 Jupyter requirement: The notebook uses IPython's display() functionality and is intended to run in Jupyter Notebook or a compatible IPython environment.
- 🔗 Concatenation limitation: Combining datasets with pd.concat() appends rows; it does not perform a key-based database join.
- 📚 Stack plot limitation: A stack plot is generally most useful with multiple series, while plotting only one column limits its usefulness.
🎓 Learning Outcomes
After completing this project, a student can demonstrate an understanding of:
- 🐍 Python syntax, functions, classes, and objects.
- ⌨️ User input and menu-driven programming.
- 🐼 Pandas Series and DataFrames.
- 🔢 NumPy arrays and numerical calculations.
- 🧹 Missing-data identification and handling.
- 📐 Descriptive statistics.
- 📊 Data visualization and chart selection.
- 🛡️ Basic exception handling and debugging.
- 💾 Saving charts and output files.
- 🧩 Combining multiple Python libraries in one project.
🔮 Future Enhancements
The project could be improved further by adding:
1. 📗 Excel support using pd.read_excel().
2. 🧠 Automatic data insights that summarize key patterns.
3. 📤 Export cleaned data to a new CSV file.
4. 🎨 Custom chart options for titles, labels, and formatting.
5. 🔎 Advanced filtering based on multiple conditions.
6. 📑 Automatic report generation with statistics and charts.
7. 🧪 More input validation for invalid choices and data types.
8. 🖥️ A graphical user interface (GUI) for easier use.
9. 📊 More statistical analysis and comparisons between columns.
10. 📂 Support for additional data formats where appropriate.
These are proposed enhancements and are not claimed to be implemented in the current version.
🏁 Conclusion
The Data Analysis & Visualization Program demonstrates how Python can be used to perform practical data-analysis tasks in a structured, interactive way. By combining Pandas, NumPy, Matplotlib, and Seaborn, the project brings together data loading, exploration, cleaning, numerical calculations, descriptive statistics, and visualization.

The project also helps students develop practical programming skills and understand how data can be transformed into useful information. It provides a strong foundation for more advanced work in data science and analytics.
👨‍🎓 Project Information
Field	Details
🎓 Project Title	Data Analysis & Visualization Program
👨‍💻 Student Name	[Write Your Name]
🏫 College / Institute	[Write Your College Name]
📚 Course / Class	[Write Your Course or Class]
📘 Subject	Python Programming / Data Analysis
👨‍🏫 Submitted To	[Teacher / Faculty Name]
📅 Academic Year	[Write Academic Year]


<div align="center">

⭐ Thank You for Reviewing This Project! ⭐


"*i am not able to make video because from 1 week  throat is happen so i  am not in conditon to speak*"

