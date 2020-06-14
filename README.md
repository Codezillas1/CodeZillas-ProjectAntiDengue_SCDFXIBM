# CodeZillas-ProjectAntiDengue_SCDFXIBM
Using IoT and mobile applications through IBM Cloud to fight dengue

CodeZillas is a team consisting of Verlyn, Hongyu, Jannah, Cleven and Joshua 

We are tackling Problem Statement 4: Preventing the Spread. Our solution, Project Anti-Dengue, aims to reduce the manpower-intensive nature of patrolling by officers. While COVID-19 SARS-CoV2 virus dominates the news nowadays, there’s another virus that continues to spread in our communities - dengue. Current preventive measures are often manpower-intensive. Moreover, during a global health crisis like the current one, it becomes more difficult for officers to carry out patrolling duties.

Link to Youtube video: https://youtu.be/l5pWQdRYiVM

Link to detailed solution (with detailed descriptions): https://docs.google.com/document/d/1TZgB6F1qOBqc9aVYQ3GkXsezLFHDEGaeLTX5B5uExmE/edit#

Step-by-step instructions to install software/run demo:
    Solution 1: 
    Use of node red and the code can be found here 
https://github.com/Codezillas1/CodeZillas-ProjectAntiDengue_SCDFXIBM/blob/master/solution%201%20(CODES%20for%20sensor)

    Solution 2: Use of weather data can be found here https://developer.ibm.com/recipes/tutorials/weather-data-meets-ibm-cloud-part-1-ingestion-and-processing-of-weather-data/
    NEA Weather API: https://api.data.gov.sg/v1/environment/4-day-weather-forecast
    NEA Air Temperature API: https://api.data.gov.sg/v1/environment/air-temperature
    
    Solution 3:
    The model_android and model_ios directories can be found inside the folder named Object_Recognition_Model. 

    For Android, follow the instructions found here: https://github.com/cloud-annotations/object-detection-android
    For iOS, follow the instructions found here: https://github.com/cloud-annotations/object-detection-ios

    Solution 4: 
    Chatbot Dennis can be found through this link. https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=e6979558-e5a3-49cb-86f7-3c954456770a&serviceInstanceID=997d6c06-8a26-4de6-9500-989f631a0e25 



    For Solution 1 (Drain Sensors), IBM Node-RED and Cloudant was used.
    For Solution 2 (Detecting Weather Conditions), IBM Functions, Cloud Storage and SQL Query was used.
    For Solution 3 (Object Detection), IBM Cloud Annotations and Watson Machine Learning was used.
    For Solution 4 (ChatBot-Dennis), Watson Assistant was used.
