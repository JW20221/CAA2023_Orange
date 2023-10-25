# CAA2023_Orange

## Project： Home Assistant Panel
---

## Table of Contents
1. Project description
2. Things used in this project
3. How to set it up
4. Demo
5. Acknowledgement

---

## 1. Project description
The M5Stack and PIR motion sensor-based home assistant panel is a compact and versatile device that combines security, thermostat control, and a night light feature. It enhances home security by detecting motion and sending immediate notifications to the user's smartphone via IFTTT. Data is logged and stored in Google Cloud BigQuery for analysis. The panel also offers thermostat control for optimal comfort and a customizable night light. 

Detailed description can be found in the Project Description Folder.

---

## 2. Things used in this project
### Hardware components

M5Stack Core2

M5Stack PIR Motion Unit

### Software apps and online services

Google Cloud - BigQuery

Google Cloud - Cloud Functions

IFTTT - Webhook

---

## 3. How to set it up
### Step 1: UIFlow interface Development
Connect your M5Stack Core2 to UIFlow by entering the API Key. Connect PIR Sensor to M5Stack via Port B, and add PIR sensor as a new unit on UIFlow. Here is the code for interface development.
![image](https://github.com/JW20221/CAA2023_Orange/assets/114418889/f42aae79-18fd-4971-9541-dfbd6e170acb)
Zoom in to see the whole code.

<img width="564" alt="image" src="https://github.com/JW20221/CAA2023_Orange/assets/114418889/96cd62db-8b76-4ad4-8e5f-c868f67e7699">

### Step 2: Setting Up IFTTT Notifications
Sign up for an acount on the IFTTT (If This Then That) platform. Create a Webhook integration as "This" and a notification as "That". Here is a tutorial for step-by-setp setting up. https://www.youtube.com/watch?v=6cTEbomZvZI

### Step 3: Google Cloud Functions and BigQuery Setup
Log in to your Google Cloud account, create a new project whthin the Google Cloud Console. Develop a Cloud Function that handles data push to Google Cloud BigQuery. The code for Main.py can be found in ddedddddd. In requirements.txt, add "google-cloud-bigquery".
![image](https://github.com/JW20221/CAA2023_Orange/assets/114418889/e6fe16ff-5906-41b0-a524-cbd54653a8b6)

### Step 4: Create a Web Page via Google Cloud Functions 
Google Cloud Functions can also be used to create a simple webpage to deisplays the data gathered by the PIR motion. The code can be found in ddddd. 
![image](https://github.com/JW20221/CAA2023_Orange/assets/114418889/e6b3ffdf-b5d1-4dc8-9fa5-8e8988a52d76)

## 4. Demo
This demo shows how the project works. 

https://youtu.be/gTaHTY7ASlk


## 5. Acknowledgement
I would like to express my thanks to Johannes, Stergios and Prof. Vlachos for their invaluable assistance and support during the completion of the project.
