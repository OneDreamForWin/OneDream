# bed_tracker

A new Flutter project for tracking hospital beds according to the user's location.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## PROBLEM IN CURRENT SCENARIO 
The second largest populated country in the world, India faces various hindrances to its development. India’s health ministry did not respond to a request for comment on how it will cope with the predicted rise in infections, given that most public hospitals are overcrowded at the best of times. The federal government has said in media briefings that not all patients need hospitalization and it is making rapid efforts to increase the number of hospital beds and procure health gear.
The federal government’s data from last year showed there were about 714,000 hospital beds in India, up from about 540,000 in 2009. However, given India’s rising population, the number of beds per 1,000 people has grown only slightly in that time.
India has 0.5 beds per 1,000 people, according to the latest data from the Organization for Economic Co-operation and Development (OECD), up from 0.4 beds in 2009, but among lowest of countries surveyed by the OECD. In contrast, China has 4.3 hospital beds per 1,000 people and the United States has 2.8, according to the latest OECD figures.
Hence there is a need of managing this Situation immediately!!!

## PROTOTYPE 
We at Flutterify aim to build an easy and interactive mobile app for both IOS and android users  to track the no. of beds in the nearby Hospitals .
We are using Google  Maps sdk and Places api to find the details of nearest hospital depending upon the user's current  location , using the geolocation package provided by Flutter. As getting the each and every database of all the hospitals is not possible so we are trying to build our own  serverless No SQL  database with the help of   Firebase and cloud Firestore to update the no. of beds .Without going to hospitals users can check  if there is available bed or not !
Hence this small initiative is an effective way to manage the crisis situation 

## Technology STACK

-	Flutter
-	Dart
-	Google Cloud
-	Places API
-	Gelocation
-	Flutter Provider


## Download the app from [here]().
**Steps-** Open the link -> Click Download -> Click Drive -> Choose Your Account -> Click App Installer -> Open App

## PPT Link [here]().

<!-- ## Video Link [here](). -->

## Permissions

* Location
* GPS

## Requirements
* Android version 5.0 and above


## Screnshots 
<table>
  <tr>
    <td><img src="" height = "580" width="300"></td>
    <td><img src="" height = "580" width="300"></td>
  </tr>
  <tr>
    <td><img src="" height = "580" width="300"></td>
    <td><img src="" height = "580" width="300"></td>   
  </tr>
</table>

## Setup on your machine - 

- Open cmd/terminal
- Navigate to your workspace
- Then type in: ```git clone https://github.com/SAMYAK99/TrackaBed```
- Import the Project in Android Studio and start coding!

## To Setup the project properly add the following to local.properties under Gradle Scripts

GOOGLE_MAP_KEY="Add your google map api key"
