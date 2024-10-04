# How to execute the code

## List of Jupyter Notebooks

- 0_Install_Libraries.ipynb - Consists of additional python libraries that needs to be installed (if they are not already installed)
- 1_Data_Preparation.ipynb - Prepare data for analysis and Model Build
- 2_Exploratory_Data_Analysis.ipynb - Exploratory Data Analysis
- 3_Model_XGBOOST.ipynb - XGBoost Model build, testing and forecasting
- 4_Model_Prophet.ipynb - Prophet Model build, testing and forecasting


## How to execute source files

### Step 1: 
This is an optional step. If the libraries contained within *0_Install_Libraries.ipynb* is already installed, then this step can be skipped. Otherwise, please run this step to install the third-party python libraries.

### Step 2:
Open and execute *1_Data_Preparation.ipynb* to prepare data for analysis and model build. If in case of any failure, please run from the start.

### Step 3:
Open and execute *2_Exploratory_Data_Analysis.ipynb* To generate all the Exploratory Data Analysis results.

### Step 4:
Open and execute *3_Model_XGBOOST.ipynb* to build and test XGBoost model. This may take few mins in certain steps as the processing takes time. 

### Step 5:
Open and execute *4_Model_Prophet.ipynb* to build and test Prophet model. Please note the execution time of this script could vary between 30 mins to 1 hour due to Grid Search taking considerable time.


## Troubleshooting

1. Not all libraries are added to *0_Install_Libraries.ipynb* install notebook. If subsequent notebooks fail due to unavailability of packages in your local machine, please proceed to install the missing packages separately.

2. In *1_Data_Preparation.ipynb*, two zip files are merged together using operating system specific command executed through Python. The command is written to handle MS Windows and Apple Operating Systems. If the zip merge fail, please use the appropriate zip merge command within the operating system.

3. It is advisable to run from the start if any of the Jupyter Notebooks fail
