# COP3045-Team-1

#   COP3045 Automotive Data Analysis Project

# ---------------------------------------------------------------------------------------------------------------------------------

# Project Overview:

# This project is an automated data analysis and reporting application built for the COP3045 course. It uses real-world datasets to examine vehicle specifications and also uses car sales, generates visual charts, and creates an automated PDF report.

# ---------------------------------------------------------------------------------------------------------------------------------

# Files Included

# 1. main.py: Loads the CSV files, cleans the data, runs the analysis, and saves the charts.

# 2. generate_report.py: Compiles the analysis and #charts into a PDF report (Automotive_Data_Analysis_Report.pdf).

# 3. vehicle_specs.csv: Contains vehicle specifications and features.

# 4. car_sales.csv: Contains historical records of used car sales.

# 5. environment.yml: Lists the Conda environment settings and required libraries.

# ---------------------------------------------------------------------------------------------------------------------------------

# Setup Instructions

# 1. Clone the repository: 
# git clone https://github.com/ArrivingShortly/COP3045-Team-1.git 
# cd COP3045-Team-1

# 2. Set up the Conda environment:
# conda env create -f environment.yml
# conda activate project-env

# ---------------------------------------------------------------------------------------------------------------------------------

# Running the Application

# 1. Run the main script to process the data and create the charts:
# python main.py

# 2. Run the report script to generate the PDF file:
# python generate_report.py

## Environment Setup and Verification

The project environment was successfully created and tested on Windows using Anaconda and Python 3.10.22.

### Setup Instructions

1. Clone the GitHub repository.
2. Open Anaconda Prompt and navigate to the project directory.
3. Create the environment using:
   `conda env create -f environment.yml`
4. Activate the environment using:
   `conda activate project-env`

### Running the Application

Run the main data analysis program:

`python main.py`

The program should load both CSV datasets and generate three visualization files:

- `viz1_selling_price.png`
- `viz2_correlation.png`
- `viz3_mileage_vs_price.png`

Generate the PDF report using:

`python generate_report.py`

The report should be saved as `Automotive_Data_Analysis_Report.pdf`.

### Environment Verification Results

Tested successfully on Windows using Python 3.10.22.

- Conda environment created successfully.
- Both CSV datasets loaded without errors.
- All three visualizations generated successfully.
- PDF report generated successfully.

These tests confirm that the application runs in the configured environment. They do not independently verify the accuracy of the analysis or completeness of the dataset integration.