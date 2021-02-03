**This repository contains projects that have been done for Practicum Yandex100 training program.**

**[Project notebook](https://ulfsky.github.io/sales_funnel/sales_funnel.html)**


# Data

Each log entry is a user action or an event.<br>
EventName — event name<br>
DeviceIDHash — unique user identifier<br>
EventTimestamp — event time<br>
ExpId — experiment number: 246 and 247 are the control groups, 248 is the test group<br>
____

# Goal:
to investigate user behavior for the company's app (a startup that sells food products).<br>
First we will preprocess the data and study the sales funnel: <br>

find out how users reach the purchase stage<br>
How many users actually make it to this stage<br>
how many get stuck at previous stages<br>
Next we will check the results of an A/A/B test: if change of the fonts for the entire app have any impact on users. We will pick up the equal number of users for all 3 groups and run a statistical test to check if there is a statistically significant difference in number of users for any of the events.<br>
____

# Libraries used:
- pandas, <br>
- IPython.display, <br>
- plotly.express, <br>
- plotly, <br>
- matplotlib.pyplot, <br>
- matplotlib, <br>
- numpy, <br>
- scipy, <br>
- seaborn, <br>
- math, <br>
- sys, <br>
- warnings<br>


