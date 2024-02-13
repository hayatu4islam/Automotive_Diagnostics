<p align="center"><img width="90%" height="250px" src="https://github.com/hayatu4islam/Automotive_Diagnostics/blob/main/OBD-banner.webp" /></p>

## UNVEILING AUTOMOTIVE INSIGHTS: AN OBD II DATA ANALYSIS

This project involves the analysis of a dataset comprising Engine Coolant Temperature, Engine RPM, Vehicle Speed Sensor, etc.

The aim is to identify patterns and factors of interest in order to provide meaningful insights.

The following problems are investigated:
* **Predicting vehicle states**
    * **Engine overheating** - Look for patterns in engine coolant temperature and intake air temperature to identify instances of overheating.
    * **Engine (poor) performance** - Examine relationships between engine RPM, airflow rate, and vehicle speed to identify any patterns indicating poor engine performance. Find maximum fuel economy versus speed.
    * **Full efficiency** - Explore how the absolute throttle position and accelerator pedal positions correlate with the vehicle speed and airflow rate to assess fuel efficiency.
    * **Throttle response** - Analyse the data to understand how accelerator pedal positions D and E influence the engine RPM and vehicle speed, addressing potential throttle response problems.
* **Analysing driving behaviour**
    * 
* **Visualising the speed and elevation on a map (From YT)**


## Objectives:
In order to achieve the aim of this project, the following are the objectives of the project:
* **Optimising fuel efficiency:** Identify combinations of throttle positions and engine RPM that result in optimal fuel efficiency.
* **Performance enhancement:** Explore patterns in the dataset to find ways to enhance overall engine and vehicle performance.
* **Fault detection:** Develop models to detect anomalies or patterns indicative of potential engine or vehicle issues, such as overheating or irregular throttle response.
* **Driver behaviour analysis:** Explore how accelerator pedal positions relate to vehicle speed and engine RPM to understand driver behaviour and potentially improve driving habits for better efficiency.
* **Predictive maintenance:** Use the data to build predictive models that can anticipate maintenance needs based on changes in parameters like coolant temperature or airflow rate.
* **Emission control:** Analyse the dataset to identify factors influencing emission levels, considering parameters like airflow rate and throttle positions.
    
## Decision Makers
* Drivers
* Automotive Company
* 

## Dataset
The dataset used in this project is obtained from https://radar.kit.edu/radar/en/dataset/bCtGxdTklQlfQcAq#
The dataset comprises CSV files containing **ten vehicle signals** logged via the OBD-II interface: Engine coolant temperature, intake manifold absolute pressure, enginer RPM, vehicle speed sensor, intake air temperature, air flow rate from mass flow sensor, absolute throttle position, ambient air temperature as well as the accelerator pedal positions D and E. The data was recorded with the OBD-II dongle KIWI 3 from PLX Devices in combination with the smartphone application OBD Auto Doctor from Creosys on an iOS device.

The file name is assembled according to the following scheme: \<yyyy-mm-dd>\_\<brand>\_\<model>\_\<from>\_\<to>\_\<condition>\_\<extension>.csv - \<from> and \<to> represent start and end position of the log according to the German number plates, i.e. KA = Karlsruhe etc. - \<condition> is a label indicating the principle road conditions (e.g. normal, frei/free, Stau/busy) - \<extension> is optional and marks special situations occurring in the vehicle speed data.
