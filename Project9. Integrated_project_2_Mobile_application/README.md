If you have problems viewing the code, please use https://nbviewer.jupyter.org/

# Initial data
Вata on logs of user behaviour:

- EventName — event name
- DeviceIDHash — unique user identifier
- EventTimestamp — event time
- ExpId — experiment number: 246 and 247 are the control groups, 248 is the test group

# Goals

 Investigate user behaviour for the company's app. Check how new fonts for the entire app affect it.
 
 # Libraries used
 
- pandas
- numpy 
- matplotlib.pyplot
- scipy
- seaborn
- plotly 
- math

# Content

The following tasks were solved:

- Exploratory data analysis was held
- Sales funnel analysis
- A/B test results analysis

# Main conclusions

- Users who have reached Offers page, most often go to the Cart page and then to the Payment.
- The most users are lost on stage of transfer from Main screen to Offers page. It's worth thinking about conversion increase on this stage.
- A/B test shows that fonts changing does not significantly affect conversion. Users proportion who makes orders does not significantly differ in the control and experimental groups. 
