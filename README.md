🦠 COVID-19 Data Analysis Dashboard

A simple and interactive dashboard built using Python (Flask/Streamlit), CSV dataset, and custom CSS styling, which visualizes state-wise COVID-19 daily data.

📌 Project Overview

This project analyzes state-wise daily COVID-19 data including:

📊 Daily confirmed, recovered, and deceased cases

🗺 State-wise comparison

📈 Trend analysis over time

💹 Growth rate visualization

🎨 Styled UI using custom CSS

The dashboard helps users track COVID-19 patterns, visualize trends, and understand the spread across regions.

📂 Project Structure
|-- app.py                      # Main application (Flask/Streamlit)
|-- state_wise_daily data file IHHHPET.csv   # Dataset used for analysis
|-- style.css                   # UI styling for dashboard
|-- README.md                   # Project documentation

🛠 Technologies Used

Python

Pandas

Matplotlib / Seaborn / Plotly

Flask / Streamlit (depending on your app.py)

CSS

📊 Features

✔ State-wise daily COVID-19 data visualization
✔ Line charts for Confirmed / Recovered / Deceased
✔ Trend analysis (daily & cumulative)
✔ Clean UI using custom CSS
✔ Automatic data loading & preprocessing
✔ Interactive filtering (State selector, Date range)

🧹 Data Preprocessing Steps

The dataset is cleaned using the following steps:

Removing missing/duplicate records

Renaming columns for simplicity

Converting date columns to proper datetime format

Grouping data by state & date

Calculating daily and cumulative counts
