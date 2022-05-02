## Capstone Project- EDA on Telecom data Delhi
Team was tasked to analyze the data collected by the client and push the analysis to the team building the dashboard.
![](https://github.com/darsh2303/EDA-on-Telecom-data-for-Delhi/blob/main/report%20omage.png?raw=true)


### Data Description
User data and device information was provided by allowing us to connect to the client’s servers and extracting the information using MySQL. The MySQL Connector driver for Python was used to connect to the servers through a Jupyter Notebook and the downloaded data was saved in csv format.

The user dataset consisted of over 74 thousand data points, having 4 variables. These are the device id, gender of the user, age and the relevant age group.

![enter image description here](https://github.com/darsh2303/EDA-on-Telecom-data-for-Delhi/blob/main/1%20db.jpg?raw=true)
An example is shown here:

The device dataset consisted of over 87 thousand data points, having 3 variables. These are the device id, device brand and the device model.

An example is shown here:
![enter image description here](https://github.com/darsh2303/EDA-on-Telecom-data-for-Delhi/blob/main/2%20db.jpg?raw=true)

Note that the phone brand and device models have some of the data in simplified chinese.

The events dataset was sent via link to a direct download from the client’s servers. The dataset consisted of over 32.5 lakh data points, having 7 variables. These are the device id, event id, time stamp, location data in the form of latitude and longitude, city and state.

An example is shown here:

![enter image description here](https://github.com/darsh2303/EDA-on-Telecom-data-for-Delhi/blob/main/3db.jpg?raw=true)

Since the device id is the common variable in all three data sets, this was used as the anchor for mapping the data points and merging / syncing the data sets for further analysis.

Additionally, the client has requested that we focus our analysis for the state of Delhi only. The final dataset for analysis, filtered for the state of Delhi after merging of the datasets, contains just over 7.5 lakh records, each record consisting of 12 variables.

An example of the data is here below:
![enter image description here](https://github.com/darsh2303/EDA-on-Telecom-data-for-Delhi/blob/main/4db.jpg?raw=true)

Note that the above image shows the data after cleanup and final merging.

You can check the notebook by [clicking here.](Capstone%20project%20_%20EDA%20Telecom%20data.ipynb)
