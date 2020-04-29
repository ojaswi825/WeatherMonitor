# WeatherMonitor
An IoT project to monitor weather and real time visualizations

### Abstract
This is a weather monitoring service. We use different kind of sensors to monitor metrics such as temperature, pressure, humidity, etc. This project the weather is a very generic term, this project actually aims to monitor indoor parameters such as offices, buildings, etc.

### Objectives of this project:
* To monitor indoor conditions.
* To display the data real time, visualizations
* Send alerts and trigger actions in case of anomalies.
* To use machine learning to predict anomalies beforehand.
* More to come.

Currently we are using simulated device and sending data to Azure cloud. The data is stored in Azure Cosmos DB for scalability and due to unstructed data.

### Current progress of the project:

* Data can be parsed in the cloud
* The parsed data can be stored into CosmosDB.