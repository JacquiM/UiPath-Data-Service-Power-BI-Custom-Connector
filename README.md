# UiPath-Data-Service-Power-BI-Custom-Connector
UiPath Data Service is a great way to store data being utilised by automations but can be tedious to currently visualise in the UiPath stack. For that reason, one of the best ways to visualise the data living in UiPath Data Service is through Power BI. Since there is an API available for interaction with UiPath Data Service, the API can be connected to Power BI directly or through a custom connector. The custom connector is a little more advanced but, in essence, should work if the steps in this repo are followed.

## Steps:
- Download these files as a zip file from GitHub
- Unzip the files to your local computer
- Copy the UiPathDataService.mez file to your Power BI Custom Connectors folder -> Documents\Power BI Desktop\Custom Connectors
- Start Power BI
- The custom connector should be automatically recognised - it might prompt for a security change. If you are prompted to change security settings, go to File > Options > Security > Web Preview Level > Data Extensions. Check the 'Allow any extension to load without validation or warning' option and restart Power BI Desktop
![image](https://user-images.githubusercontent.com/26733937/183361570-0bc3f335-c9ba-4032-a5a7-6bad63e8878b.png)
