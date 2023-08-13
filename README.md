# 2015 Flight Delays and Cancellations
#### Which airline should you fly on to avoid significant delays?

<br>

According to The **United States Federal Aviation Administration (FAA)**, a flight is considered to be delayed when it arrives 10 minutes later than its scheduled time. We consider a flight to be early when it arrives at least 10 minutes earlier that the scheduled time.

![Status](images/Flight_Status.png)  

The purpose of this specific work is to perform a comprehensive data analysis task on a large data set. After the dataset was chosen, a complete ETL procedure was conducted and the data was imported in a datawarehouse architecured with the cube patern. A plethaura of visualization were created. Ultimately, the data imported were utilised for various data mining operations and valuable insights were extracted.

<br>
The task was part of an assignment during the course Business Intelligence and Big Data Analytics of the Department of Management Science and Technology in the Athens University of Economics in Greece.

## Dataset 

The main dataset comes from the The U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics and was extracted from [Kaggle](https://www.kaggle.com/datasets/usdot/flight-delays?select=airlines.csv). The DOT tracks the on-time performance of domestic flights operated by large air carriers. Summary information on the number of on-time, delayed, canceled, and diverted flights is published in DOT's monthly Air Travel Consumer Report and in this dataset of 2015 flight delays and cancellations.
<br>
<br>

![AircraftTimeline](images/Aircraft_Timeline.png)  

An additional dataset was used in order to obtain information on the aircraft. The database ["Aircraft Registration" from the Federal Aviation Administration](https://www.faa.gov/licenses_certificates/aircraft_certification/aircraft_registry/releasable_aircraft_download) was used.  

The information gathered is depicted in the graphic below

![AircraftInfo](images/Aircraft_Info.png)  

<br>

The core objetive of the task is to identify the factors which cause a flight to be delayed. 

## Data Warehouse Architecture & ETL process


