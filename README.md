# Data Analysis & Visualizations

This repository presents a collection of projects focused on providing appropriate visualizations of data on interactive dashboards. The projects emphasize transforming raw data into insights through clear analytical reasoning, effective visual communication, and user-facing tools.

This repository acts as a **navigation hub** that explains each project and links to its dedicated implementation repository.

---

## What this category demonstrates

Across these projects, I demonstrate the ability to:

- perform structured exploratory data analysis on real-world datasets,
- design meaningful visualizations that support analytical conclusions,
- build interactive dashboards and applications (Shiny, Streamlit),
- work with temporal and spatial data,
- communicate insights clearly to non-technical audiences.

## Featured projects

### Spotify Shared Music Dashboard

**Technologies:** Python, pandas, Streamlit, Plotly

**Problem:**
How can shared music listening patterns between users be visualized in an
intuitive and exploratory way?

**Approach:**
I developed a page in a multi-page Streamlit dashboard focused on
shared listening behavior between users. Users can:

- select artists, songs, or albums,
- compare listening frequencies across users,
- explore results as flow-style visualizations or tables.

The dashboard supports flexible aggregation by year, song, or album.

**Outcome:**
A user-friendly interactive flow chart that reveals overlap in music preferences and listening habits across individuals.

➡️ **Repository:** [Spotify_Dashboard](https://github.com/Luki308/Spotify_Dashboard)

---

### Cryptocurrency & Stock Markets Dashboard

**Technologies:** Dashboard: Python, shiny, matplotlib. Backend: Nifi, Kafka, Hadoop, Hive, HBase, pySpark

**Problem:**

How can real-time and historical market data be combined into a meaningful, readable dashboard for cryptocurrency and stock traders?

**Approach:**

My team developed a shiny app that took data from our backend service that provided real-time data through Kafka and historical data through pySpark. Both were stored in HBase. Although i mainly took part in data preprocessing steps I inspected visualsations and overall dashboard so that it was readable and compliant with our data.

**Outcome:**

An IaaC service that provided real-time dashboard about crypto and stock markets.

➡️ **Repository:** [CryptoStockPrediction](https://github.com/szuvarska/CryptoStockPrediction)

---

### Posters

**Technologies:** Python, pandas, NumPy, NetworkX, Matplotlib, R, ggplot2, dplyr, Canva

**Problem:**
How can complex phenomena - social media manipulation, algorithmic matrix recovery, and sports economics — be communicated clearly through data visualization?

**Approach:**
I designed three independent research posters, each tackling a distinct analytical challenge:

* mapped Russian intelligence-linked Twitter networks to reveal how political narratives were amplified across ideological groups during the 2016 US elections,
* implemented the Soft-Impute algorithm to recover missing values in sparse movie-rating matrices and evaluated its correctness,
* analyzed historical Olympic data to assess whether host nations gain measurable medal advantages and whether the Games deliver financial returns.

**Outcome:**
Three publication-styled posters translating technical and empirical analyses into clear, visually compelling stories across network science, machine learning, and sports economics.

➡️ **Repository:** [Posters](https://github.com/Luki308/Posters)

---

### NYC-Citibike Dashboard

**Technologies:** R, dplyr, ggplot2, Shiny, Leaflet

**Problem:**
How did the COVID-19 pandemic affect bicycle usage patterns in New York City, and how does bike traffic vary spatially across neighborhoods and time of day?

**Approach:** Two complementary analyses were conducted:

1. A time-series analysis of ride counts and ride durations from 2019–2022, focusing on pandemic-related changes.
2. A spatial analysis of bike usage across NYC neighborhoods, including morning rush-hour patterns to distinguish residential from business-oriented areas.

Results were presented through interactive plots and maps and deployed as a Shiny application.

**Outcome:**
An interactive dashboard enabling users to explore temporal and spatial bike usage patterns in NYC, supporting intuitivecomparison across years, locations, and time windows.

➡️ **Repository:** [NYC---bikes-analysis](https://github.com/Luki308/NYC---bikes-analysis)

---

## Context

These projects were developed as part of my university coursework during following classes:

* Spotify Dashboard - Data Visualisation Techniques
* Cryptocurrency & Stock Markets Dashboard - Big Data Analytics
* Posters - Data Visualisation Techniques, Social Networks and Recommendation Systems
* NYC-Citibike Dashboard - Structured Data Processing
