**This repository contains projects that have been done for Practicum Yandex100 training program.**

# Data
The data is stored in 2 tables. 

The dataset `telecom_dataset_us.csv` contains the following columns: <br>
<br>
- direction — call direction (`out` for outgoing, `in` for incoming)<br>
- internal — whether the call was internal (between a client's operators)<br>
- operator_id — operator identifier<br>
- is_missed_call — whether the call was missed<br>
- date — date the statistics were retrieved<br>
- user_id — client account ID<br>
- calls_count — number of calls<br>
- call_duration — call duration (excluding waiting time)<br>
- total_call_duration — call duration (including waiting time)<br>

 
 The dataset `telecom_clients_us.csv` has the following columns:<br>
<br>
- tariff_plan — client's current plan<br>
- date_start — client's registration date<br>

____

# Goal:
to study effectivness of phone operators for virtual telephony service CallMeMaybe. <br>
To define ineffective operators we will study the following features: <br>
- number of missed incoming calls (internal and external),  <br>
- waiting time for incoming calls,  <br>
- number of outgoing calls,  <br>
- number of internal calls between operators.  <br>

Also we will study these features for every tariff plan the company has (A, B, C) and define ineffective operators for every of this plan.  <br>

We will test the hypothesis if the difference in operators performance for different tariff plans is statistically significant.<br>
Finally we will draw basic conclusions and develop some recommendations on how to improve operators performance. <br>
____

# Libraries used:
- pandas, 
- IPython.display,
- scipy,
- matplotlib, 
- numpy, 
- functools, 
- stats, 
- seaborn, 
- math, 
- plotly

[Project notebook](https://ulfsky.github.io/phone_operators_analysis/phone_operators_analysis.html)