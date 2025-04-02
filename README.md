# Individual-Project
This repository contains a single Python script 
# Video Game Sales Analysis

## Short Description

This repository contains two Python scripts (`analyze_sales.py` and `categorize_years.py`) used to analyze a video game sales dataset. The first script calculates and compares the average global sales before and after the year 2005. The second script adds a new column to the dataset, categorizing each sales record based on whether the release year was before or after 2005.

## Getting Started

### Prerequisites

* Python 3.x
* Pandas library (`pip install pandas`)

### Installing

1.  Clone the repository:
    ```bash
    git clone [repository URL]
    ```
    (Replace `[repository URL]` with the actual URL of your GitHub repository)
2.  Navigate to the repository directory:
    ```bash
    cd [repository name]
    ```

## Running the Scripts

### Analyzing Average Sales

1.  Ensure the `vgsales1.csv` file is in the same directory as the `analyze_sales.py` script.
2.  Run the script:
    ```bash
    python analyze_sales.py
    ```
3.  The script will output the average global sales for the periods before and after 2005, and a statement indicating which period had higher average sales.

### Categorizing Years

1.  Ensure the `vgsales1.csv` file is in the same directory as the `categorize_years.py` script.
2.  Run the script:
    ```bash
    python categorize_years.py
    ```
3.  The script will:
    * Add a new column named `Year_Category` to the DataFrame.
    * Save the updated DataFrame to a new CSV file named `vgsales_updated.csv`.
    * Print the first few rows of the updated DataFrame showing the `Year` and `Year_Category` columns.

## Author

* **[Your Name]** - [Your GitHub Profile URL (optional)]

## License

[Add your license information here if you have one. For example, MIT License.]

## Acknowledgement

* This project was created as part of an assignment.
* The analysis uses the Pandas library for data manipulation.
