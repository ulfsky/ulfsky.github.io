**This repository contains projects that have been done for Practicum Yandex100 training program.**

# Data
The visits table (server logs with data on website visits):<br>
Uid — user's unique identifier<br>
Device — user's device<br>
Start Ts — session start date and time<br>
End Ts — session end date and time<br>
Source Id — identifier of the ad source the user came from<br>
All dates in this table are in YYYY-MM-DD format.<br>
The orders table (data on orders):<br>
Uid — unique identifier of the user making an order<br>
Buy Ts — order date and time<br>
Revenue — Yandex.Afisha's revenue from the order<br>
The costs table (data on marketing expenses):<br>
source_id — ad source identifier<br>
dt — date<br>
costs — expenses on this ad source on this day<br>
____

# Goal:
In the course of the project we are going to analize and optimize marketing expenses of Yandex.Afisha. We are going to look into data related to site visits, orders and costs from June 2017 through May 2018.<br>

<br>
____

# Libraries used:
- pandas,
- plotly,
- plotly.express,
- matplotlib.pyplot,
- numpy, 
- scipy, 
- seaborn 

[Project notebook](https://ulfsky.github.io/marketing_expences_analysis/marketing_expences_analysis.html)