# Welcome to ZZSC9020 GitHub repository for GROUP-3

This GitHub repository stores the data files, source code, model results, model outputs and project report artifacts. 

## Group and project information

### Group members and zIDs

- Rushmila Islam (z5456038)
- Karim Adham (z5468227)
- Rishantha Rajakaruna (z5441528) 
 


### Brief project description

This research project focuses on short-term forecasting. We primarily use half
hourly temperature, historical half hourly actual demand, calendar information (holidays,
weekends) and time of the day as critical data sources. We analyse the relationship
between demand and the features above in detail. We use two models,
**XGBoost** and **Prophet by Meta** to forecast half hourly daily demand. By
using multiple metrics, we compare the performance of each model. We also compare
the results of the two models against the short-term demand forecast published
by the Australian Energy Market Operator.

## Repository structure

The repository has the following folder structure:

- data: Data used for analysis
- gantt_chart: Contains the file which links to our overall project plan
- models: The output of Prophet Model
- report: RMarkdown and related artifacts used to generate the final project report
- results: results of model predictions
- src: source code used to prepare, analyse and build the model
