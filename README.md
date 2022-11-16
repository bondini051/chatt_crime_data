# CPD Crime Data
This purpose of the this project is to setup a connection to the Chattanooga Data API and pull Chattanooga Police Indcident data.

## Pulling Data from the API
Pulling data from Chattanooga Police Department API - https://www.chattadata.org/Public-Safety/Police-Incident-Data/jvkg-79ss
Reference on API Docs: https://dev.socrata.com/foundry/www.chattadata.org/jvkg-79ss

The requests library will be utilized to pull data from the api and then analyze the data (json) within pandas. 
The purpose of the project is to analyze police data in Chattanooga especially violent crime. There is a data dictionary at the above URL where the data can be pulled.
In order to pull the data that isn't throttled you will have to get your own API Token. The above URL will walk you through how to get the token. 
The data can also be pulled in a csv file.  

### Disclaimer
"The data provided in this public portal/website represents general data of incidents based on the Tennessee Incident Based Reporting System (TIBRS). 
Incidents involving protected classes (juveniles, domestic abuse victims) by Tennessee law have been removed. Additionally, some incident addresses have been 
generalized to block level and randomly offset to protect the privacy of victims of crime. All crime data posted is preliminary and may or may not have been 
reviewed and approved by the Chattanooga Police Department’s (CPD) quality control process; therefore, the data may change upon further investigation."
