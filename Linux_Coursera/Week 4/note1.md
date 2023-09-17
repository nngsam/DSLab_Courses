Hands-on Lab: Historical Weather Forecast Comparison to Actuals


- Exercise 1 - Initialize your weather report log file
```
touch rx_poc.log
```
- Exercise 2 - Download the raw weather data


```
touch rx_poc.sh
chmod u+x rx_poc.sh
```
- Exercise 3 - Extract and load the required data
```
```
- Exercise 4 - Schedule your Bash script rx_poc.sh to run every day at noon local time

```
(base) samng@Sam-MacBook Week 4 % crontab -e
crontab: no crontab for samng - using an empty one
crontab: installing new crontab
(base) samng@Sam-MacBook Week 4 % crontab -e
crontab: no changes made to crontab
```

- Exercise 5 - Create a script to report historical forecasting accuracy

```
fc_accuracy.sh
```
- Exercise 6 - Create a script to report weekly statistics of historical forecasting accuracy
```
weekly_stats.sh
```