### Objective
Prepare a prototype (based on raspberry-pi) to detect fire, ring buzzer, send an email alert, and monitor it live through a web server. 

#### Run: 
    server.py

<details close>	
  <summary> Key Features </summary>
  
  - Use Pm2.5 sensor to detect smoke/fire
  - On detecting fire
    - Ring Buzzer
    - Initiate Camera Module 
    - Send Email Alert
    - Initiate Web Server   

</details>

<details close>	
  <summary> Learning Outcomes </summary>

  - Multithreading
    - Smoke sensor thread
    - Camera module thread
    - Server gateway
  - Email Notification
    - Smoke quantity
    - Fire Image
    - Web Server Link
  - Create Web Server
    - Smoke quantity
    - Smoke Image
    - Timestamp
  - Hardware Communication
    - Buzzer
    - Pm2.5 Sensor
    - Camera
    - Raspberry Pi
</details>


### Future Work
Store captured images as bytes rather then png files to optimize the fire alert and monitoring time.

