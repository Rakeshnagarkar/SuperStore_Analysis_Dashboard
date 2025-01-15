# Superstore Analysis Dashboard
A Streamlit-based data visualization dashboard for analyzing superstore sales data. The dashboard provides insights into category-wise sales, region-wise sales, time-series analysis, and hierarchical sales using interactive charts and filters.

## Features:
* File Upload: Upload .csv, .txt, .xlsx, or .xls files for analysis.
* Date Filtering: Filter data by start and end dates.
* Region, State, and City Filters: Drill down into specific regions, states, or cities.
* Visualizations:
* Category-wise Sales (Bar Chart)
* Region-wise Sales (Pie Chart)
* Time-Series Analysis (Line Chart)
* Hierarchical View (TreeMap)
* Segment-wise Sales (Pie Chart)
* Scatter Plot (Sales vs. Profit)
* Summary Tables: Downloadable tables for specific categories and regions.
* Export Options: Export processed data as .csv files.

## Prerequisites:
Before you start, ensure you have the following installed on your system:
### 1) Python (>=3.8)
### 2) pip (Python package manager)

## Required Python Libraries:
1) streamlit
2) pandas
3) plotly
4) openpyxl
5) xlrd (for .xls file support)

## Installation and Setup:
Follow these steps to set up the project on your local machine:

#### Step 1: Clone or Download the Repository
* Clone the repository
  git clone https://github.com/your-repo/superstore-dashboard.git

* Or download the .zip file and extract it.

#### Step 2: Navigate to the Project Directory
* cd superstore-dashboard

#### Step 3: Install Dependencies Install the required Python libraries listed in requirements.txt:
* pip install -r requirements.txt

#### Step 4: Verify the Installation Ensure all required libraries are installed:
* pip list

#### Step 5: Run the Streamlit App Execute the following command to launch the app:
streamlit run app.py

##### Step 6: Access the Dashboard
* After running the above command, Streamlit will provide a URL (e.g., http://localhost:8501).
* Open the URL in your browser to access the dashboard.

#### Best Part:
Any Superstore owner can use our app to manage and visualize their sales data free of cost, simply by creating an Excel sheet with columns similar to those in Superstore.xls
