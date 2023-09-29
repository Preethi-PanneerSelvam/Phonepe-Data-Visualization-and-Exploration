#Phonepe Pulse Data Visualization and Exploration

##1. Requirement Libraries to Install
pip install pandas numpy os json requests subprocess mysql.connector sqlalchemy pymysql streamlit plotly.express

##2. Import Libraries

import requests
import subprocess
import pandas as pd
import numpy as np
import os
import json

##SQL libraries

import mysql.connector
import sqlalchemy
from sqlalchemy import create_engine
import pymysql

##Dashboard libraries

import streamlit as st
import plotly.express as px

##3. E T L Process

a) Extract data
Initially, we Clone the data from the Phonepe GitHub repository by using Python libraries.

b) Process and Transform the data
Process the clone data by using Python algorithms and transform the processed data into DataFrame format.

c) Load data
Finally, create a connection to the MySQL server and create a Database and stored the Transformed data in the MySQL server.

##4. E D A Process and Frame work

a) Access MySQL DB
Create a connection to the MySQL server and access the specified MySQL DataBase by using pymysql library

b) Filter the data
Filter and process the collected data depending on the given requirements by using SQL queries

c) Visualization
Finally, create a Dashboard by using Streamlit and applying selection and dropdown options on the Dashboard and show the output are Geo visualization, bar chart, and Dataframe Table


##5. User Guide

Step 1.
Select any one option fron All India or State wise or Top Ten categories or Basic Insights

Step 2.
Select any one option fron Transaction or User.

Step 3.
Select any Year, Quarter and additional required option.

Step 4.
Finally, You get the Geo Visualization Analysis or Bar chart Analysis and Table format Analysis

