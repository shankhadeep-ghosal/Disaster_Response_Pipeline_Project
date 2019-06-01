# Disaster_Response_Pipeline_Project
creating a machine learning pipeline to categorize disaster events so that you can send the messages to an appropriate disaster relief agency.

This project will include a web app where an emergency worker can input a new message and get classification results in several categories. The web app will also display visualizations of the data

# Tools and requiremts:
Language : Python Packages : numpy, pandas, matplotlib , seaborn, scikit learn, mltk, sqlalchemy etc. Jupyter notbook is used for coding purpose then the code is transfered to .py file format.

# Installation :
Python Flask is used to create dashbord.So Flask need to be installed.
Above mentioned libraries/packages are required. `pip install ....`
The code should run with no issues using Python versions 3.*.

# Project Motivation :

In my experience, It is very hard to get final model at a time. A lot of changes in feature selection, data cleanings are required to get desired result. To make it easy and to make a well structured, easily manged we need pipeline concepts.

# File Descriptions :
There are 3 main folders and README.md file.
Those 3 folder are following:
	* app : Consists run.py for dashboard purpose
	* data : Consists required csv files and process_data.py which is for ETL pipeline.
	* models: Consistes train_classifier.py which is for ml pipeline and model building.

# Data Source: Data is provided by figure8.