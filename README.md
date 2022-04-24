# Bed_Tracker

A new Flutter project for tracking hospital beds according to the user's location.

## PROBLEM IN CURRENT SCENARIO 
The second largest populated country in the world, India faces various hindrances to its development. India’s health ministry did not respond to a request for comment on how it will cope with the predicted rise in infections, given that most public hospitals are overcrowded at the best of times. The federal government has said in media briefings that not all patients need hospitalization and it is making rapid efforts to increase the number of hospital beds and procure health gear.

The federal government’s data from last year showed there were about 714,000 hospital beds in India, up from about 540,000 in 2009. However, given India’s rising population, the number of beds per 1,000 people has grown only slightly in that time.

India has 0.5 beds per 1,000 people, according to the latest data from the Organization for Economic Co-operation and Development (OECD), up from 0.4 beds in 2009, but among lowest of countries surveyed by the OECD. In contrast, China has 4.3 hospital beds per 1,000 people and the United States has 2.8, according to the latest OECD figures.

Hence, a better solution is needed and here comes technology in place to cope up with the situation. As per the situation, it would have been better if people knew if any bed is empty at some hospital or not. So, a mobile application will come in handy which will show the availability of beds (with different types of beds) at any hospital as per user's choice/requirements according to their geolocation or on their search basis.

Hence there is a need of managing this Situation immediately!!!

## PROTOTYPE 
We at Flutterify aim to build an easy and interactive mobile app for both IOS and android users to track the number of beds in the nearby Hospitals and also in the Hospitals of other cities.

We are using **[covidbedsindia.in](https://documenter.getpostman.com/view/15598746/TzXzDH7k#3188a9c3-c98d-4edd-ba17-34816f9571d6) API** to find the details of nearest hospital depending upon the user's current location, using the geolocation package provided by Flutter and people can also search by the city name or the hospital name to find the number of beds available in a particular hospital/hospitals of a city. 

As getting the each and every database of all the hospitals is not possible so we are trying to build our own serverless No SQL database with the help of Firebase and cloud Firestore to update the number of beds. 

So, now without rushing to hospitals in search of bed users can check if there is available bed or not by using our app!
We've also added an **unique feature** in our app like users can directly contact the hospitals by calling them directly to ask for any queries.
Hence, we've taken a small initiative this small initiative is an effective way to manage the crisis situation. 

## What makes the App Unique?

- Realtime Data of the bed, So in case of emergency the user is up to date with the availability of the beds.
- Hospital Can Register and update the bed count from the app itself which is very easy and handly compared to maintaining in a desktop software.
- The user (Patient) can directly call the hospital via the app. No need to google number online.
- Search any hospital in the city/ state by name within the app.

## Technology STACK

-	Flutter
-	Dart
-	Google Cloud
-	Places API
-	Gelocation
-	Flutter Provider


## Download the app from [here](https://drive.google.com/file/d/1_ffyqvu2N-g8XUQi3S8Kda_qZ2ueCDrV/view?usp=sharing).
**Steps-** Open the link -> Click Download -> Click Drive -> Choose Your Account -> Click App Installer -> Open App

## PPT Link [here](https://docs.google.com/presentation/d/1-xvJQnlfb7X_ilyWGF9KTiYqHeHKI3Gyjl3EE0UjVuc/edit#slide=id.g125944e0cb1_3_25).

## Figma Design File Link [here](https://www.figma.com/file/0fb7UNXmUJMJzjr4Nr30JP/Bed_Tracker?node-id=0%3A1).

## Permissions

* Location
* GPS

## Requirements
* Android version 5.0 and above


## Screnshots 
<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/104226601/164974955-09dcf6b8-67cf-4e42-9ec1-66716c1f3ed6.png" height = "580" width="300"></td>
    <td><img src="https://user-images.githubusercontent.com/104226601/164975037-d3b607ab-4108-4a90-9d4e-b93dcf4a439d.png" height = "580" width="300"></td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/104226601/164975085-d7ceef70-fd81-4827-ae9b-6e7a9098537a.png" height = "580" width="300"></td>
    <td><img src="https://user-images.githubusercontent.com/104226601/164975136-b82c23d6-cdcd-4e89-be1b-2308e2179102.png" height = "580" width="300"></td>   
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/104226601/164975188-2062c0dd-d891-4f6e-9fd9-26ab40455f28.png" height = "580" width="300"></td>
    <td><img src="https://user-images.githubusercontent.com/104226601/164975216-269619ac-d3bb-4ec0-b256-c21a75308658.png" height = "580" width="300"></td>
  </tr>
</table>

## Setup on your machine - 

- Open cmd/terminal
- Navigate to your workspace
- Then type in: ```git clone https://github.com/OneDreamForWin/OneDream```
- Import the Project in Android Studio and start coding!

## To Setup the project properly add the following to local.properties under Gradle Scripts

GOOGLE_MAP_KEY="Add your google map api key"
