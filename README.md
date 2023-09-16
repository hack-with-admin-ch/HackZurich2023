
---



     _    _                                     _    _                  _      _                     _   
    | |  | |                                   | |  | |                | |    (_)                   | |  
    | |__| |   __ _   _ __    _ __    _   _    | |__| |   __ _    ___  | | __  _   _ __     __ _    | |  
    |  __  |  / _` | | '_ \  | '_ \  | | | |   |  __  |  / _` |  / __| | |/ / | | | '_ \   / _` |   | |  
    | |  | | | (_| | | |_) | | |_) | | |_| |   | |  | | | (_| | | (__  |   <  | | | | | | | (_| |   |_|  
    |_|  |_|  \__,_| | .__/  | .__/   \__, |   |_|  |_|  \__,_|  \___| |_|\_\ |_| |_| |_|  \__, |   (_)  
                     | |     | |       __/ |                                                __/ |        
                     |_|     |_|      |___/                                                |___/         



> Embrace this unique moment, innovate boldly, and most importantly, enjoy every step of the journey!🚀🛣️





# Welcome Hackers!🚀

We're thrilled to have you here for the challenge #6 . This is your chance to reshape the future of Swiss commuting by developing predictive models and user-centric solutions. 

Whether you're a data wizard or new to the hackathon scene, there's something for everyone. 

In this repository, you will find all the technical information and tools you need to master our challenge. 
You can find more information about our partners and us at https://www.bit.admin.ch/bit/en/home/themes/hackzurich/workshop.html .

Make sure to attend our upcoming workshop to deep dive into the Swiss Road Sensor data and gain expert insights from Lukas Ambühl of Transcality and ETH Zurich. 

**You can reach us in Discord [Channel #06-bit](https://discordapp.com/channels/1118186310478336011/1143111866680348722).**

## Our Challenge :  
### Intelligent Traffic Management: A User-Friendly Prognostic Solution for Swiss Roadways

This hackathon challenge invites innovative minds to employ Swiss road sensor data to predict traffic jams and create proactive solutions for road users. Our roads are embedded with numerous sensors that continuously collect data. Your mission, if you choose to accept it, is to harness this data, develop algorithms for traffic jam prognosis, and provide real-time, intelligent navigation guidance to users.

Participants are expected to take a two-pronged approach:

- **Predictive Analysis** : Create a model to analyze sensor data and prognosticate traffic jams. This model should be capable of identifying patterns, considering factors such as time of day, weather, and special events, to accurately forecast potential traffic congestion.

- **User-Centric Solutions** : Based on the prognosis, develop an intuitive, user-friendly interface that provides real-time suggestions to users. This could include alternate routes, optimal departure times, and advice on appropriate driving behaviour to minimize traffic-induced delays.

The end-goal of this challenge is to equip users with the necessary information to **make better travel decisions**, thereby **reducing traffic jams on Swiss roads** and promoting a smoother, more efficient commuting experience for all. This challenge calls for a blend of data science, AI, and UX design skills. If you have a knack for creating innovative solutions to complex problems, we invite you to participate in this exciting endeavor to reshape Swiss road travel.

 --- 

 
## Background

The Swiss roadway network, characterized by its meticulous engineering and strategic planning, plays a pivotal role in supporting the nation's mobility and economic vitality. In an effort to monitor and manage traffic flow, a sophisticated system of cameras has been deployed across these roads.


These aren't just your average surveillance cameras. They are meticulously designed and strategically positioned to capture granular data about the ongoing vehicular traffic. Every minute, these cameras record vital parameters such as the number of cars, trucks, and their average speeds. Such minute-by-minute data points not only paint a comprehensive picture of the traffic scenario but also provide rich datasets that hold significant potential for analysis and prediction.

Recognizing the value of this data, it has been made available to the public, ensuring transparency and fostering innovation. Interested individuals can access this treasure trove of information here.

In our endeavor to further promote research and solution development, we undertook an extensive data collection exercise. Over a span of two months, every minute's data was meticulously logged and archived. This extensive dataset, which you can find linked below on this page, has been made available for participants. It presents a unique opportunity for enthusiasts to dive deep into the intricate patterns of Swiss traffic.

The rationale behind sharing this dataset is clear. With the power of machine learning and advanced data analysis techniques, we believe that this data can serve as the foundation for predictive models. Whether you harness the capabilities of ML algorithms or use your distinct logic, the objective remains the same: to anticipate traffic jams and streamline the commuting experience.

As you embark on this journey of data exploration, analysis, and prediction, we invite you to leverage this dataset, discover hidden patterns, and craft solutions that could redefine the future of Swiss roadways.


 --- 


 
## Data

### Historical Data Set
 
 This is a robust set of historical sensor data from Swiss roads. This includes traffic counts, speed, vehicle types and event data which can be utilized for predictive modeling.

> The data are available only till the end of the Hack , after this persiod, they will be deleted.
> **An ofline vesion is also available on USB Sticks to allow you to start quickly your challenge**


#### Data description :
**MSR_Id** : The IDs for the counters are separated in two ways: one with a colon and the other with a period.

 - "XX:" stands for the supplier's acronym. For example, "CH:" means National supplier (Astra). 
 - The next part is the ID for the counting station, like "0610." or "0043."
 - Finally, there is a detector ID, which can range from 01 to 09 and represent the line (for example, 01 or 02).  

**TimeStamp** : The time of the measurement . The data are collected once per minute and each CSV file contain the values of all the sensors at this moment

**CarFlow | LorryFlow | AnyFlow** : Calculated Flow of Cars|Lorry|Any(other unrecognised type of vehicles or Motocycle ) in the last minute [Vehicle/Hours]. This value can be null if the sensor was offline . 

**CarSpeed | LorrySpeed | AnySpeed** : Speed Average of Cars|Lorry|Any(other unrecognised type of vehicles  or Motocycle ) in the last minute. This value can be null if the sensor was offline . 


Links to download the data :
|Period | Link  |
|--|--|
| From : 12/06/2023 to 24/06/2023 | <https://bithackzurich2023.blob.core.windows.net/data/12_06_to_24_06.zip> |
| From : 28/06/2023 to 07/07/2023 | <https://bithackzurich2023.blob.core.windows.net/data/28_06_to_07_07.zip> |
| From : 10/07/2023 to 17/07/2023 | <https://bithackzurich2023.blob.core.windows.net/data/10_07_to_17_07.zip> |
| From : 18/07/2023 to 25/07/2023 | <https://bithackzurich2023.blob.core.windows.net/data/18_07_to_25_07.zip> |
| From : 26/07/2023 to 01/08/2023 | <https://bithackzurich2023.blob.core.windows.net/data/26_07_to_01_08.zip> |
| From : 02/08/2023 to 09/08/2023 | <https://bithackzurich2023.blob.core.windows.net/data/02_08_to_09_08.zip> |
| From : 10/08/2023 to 17/08/2023 | <https://bithackzurich2023.blob.core.windows.net/data/10_08_to_17_08.zip> |
| From : 18/08/2023 to 25/08/2023 | <https://bithackzurich2023.blob.core.windows.net/data/18_08_to_25_08.zip> |
| From : 26/08/2023 to 02/09/2023 | <https://bithackzurich2023.blob.core.windows.net/data/26_08_to_02_09.zip> |


--- 


### Road traffic Real time API : 

The open data platform on mobility in Switzerland ontains data on individual mobility

Link : <https://opentransportdata.swiss/en/road-traffic/>

---

### Geolocation of the Sensors Data and Meta Data

The data with the desciption and geo location of each Measurment Station 

Link :<https://bithackzurich2023.blob.core.windows.net/data/SensorLocationMetaData.csv>
 
#### Data description :
**MSR_Id**: The same format as MSR_Id in the Historical Data Set

**Lane**: The lane name. Can be lane1-8 or emergency lane

**Direction**: The highways always start and finish somewhere according to the official definition  <https://en.wikipedia.org/wiki/Motorways_of_Switzerland>. The direction indicates whether this lane goes in the positive or negative direction.

**Latitude & Longitude**: The location of the sensor ( WGS84 format )

**Name**: The name of the sensor. It normally corresponds to the name of the location where it is placed.

**Canton**:The code of the canton where the sensor is located. More info:  <https://en.wikipedia.org/wiki/Cantons_of_Switzerland> 

**Street**: The name of the street where the sensor is located. More info: <https://en.wikipedia.org/wiki/Motorways_of_Switzerland>

--- 

### Geolocation Tracks of driving cars 
We recorded the available GPS data from multiple cars using phones while the cars were driving on the roads. These tracks can be useful for you to simulate the behavior of the cars in your applications.

Link : <https://bithackzurich2023.blob.core.windows.net/data/trackCars.zip> 

#### Data description :
The data are available as GPX, or GPS Exchange Format ( XML schema) . We provided also a converted version of this GPX file in a CSV Format 


---


### Judging criteria
We will follow the  [official evaluation criteria of HackZurich](https://hackzurich-2023.notion.site/Evaluation-dfc7510913ed4de2a9bdaa9c4a9ce8d9)


Additional Data for the **IMPLEMENTATION** criteria 

 To assess the accuracy of your prognosis algorithms, we require predictions based on the provided datasets. Please note the format for the data is the same as the Historical Data Set.

1.  **For the date 04.09.2023 at 05:30**:
    
    -   Reference Data: [State of the roads from 02:30 to 05:30](https://bithackzurich2023.blob.core.windows.net/data/4_09_from_2h30_to_5h30.zip)
    -   For Sensor ID = **CH:0056.05** (MSR_Id), predict the average*1 CarFlow and CarSpeed during the following time slots:
    
          P.a  05:55 to 06:05
        
          P.b  06:55 to 07:05
        
          P.c  07:55 to 08:05
        
2.  **For the date 07.09.2023 at 19:30**:
    
    -   Reference Data: [State of the roads for the last 3 hours](https://bithackzurich2023.blob.core.windows.net/data/07_09_from_16h30_to_19h30.zip).
    -   For Sensor ID = **CH:0342.01** (MSR_Id), predict the average *1 CarFlow and CarSpeed during the following time slots:
         
         P.d 19:55 to 20:05
        
         P.e  20:55 to 21:05
        
         P.f  21:55 to 22:05
        
   
    *1 calculate the average by adding your prognosis for each minute in the provided time slots and dividing by 11 
    
    Example :
   
    |Ref|Time|CarSpeed|CarFlow|
    |--|--|--|--|
    |v1|05:55 | 120 | 1000 |
    |v2|05:56 | 123| 1002 |
    | ... | ... | .. |
    | v10|06:04 | 113| 1004 |
    | v11|06:05 | 114| 1024 |

     AverageCarSpeed = (CarSpeed v1 + CarSpeed v2 + ... + CarSpeed v10 + CarSpeed v11) / 11

     AverageCarFlow = (CarFlow v1 + CarFlow v2 + ... + CarFlow v10 + CarFlow v11) / 11


> **Please be sure to provide the 12 values in the HackZurich Submission Form (google form ) under the question  "Anything else you want to let the judges know or share with them?"**

Use this format : Ref , AverageCarSpeed , AverageCarFlow (new line)

Question: Anything else you want to let the judges know or share with them?

Answer: 

P.a , 115, 1003 

P.b , 125, 403 

.... 

Rest of your comments 




---

## Links :

[Traffic Waves Video ](https://www.youtube.com/watch?v=19S3OdK6710)

[An Online page that show the curent data of the sensors ](https://verkehrszaehler-astra.opendata.iwi.unibe.ch/)

[A map with all the details of ther roads](https://map.geo.admin.ch/?layers=ch.astra.nationalstrassenachsen&lang=en&topic=ech&bgLayer=ch.swisstopo.pixelkarte-farbe&E=2843831.30&N=1129642.77&zoom=0)

[Online tool to view GPX Data](https://www.j-berkemeier.de/ShowGPX.html)

[Different show cases of project using Oopen Transport Data apis ](https://opentransportdata.swiss/de/showcase-5/)
