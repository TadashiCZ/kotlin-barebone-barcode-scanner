# Kotlin Barebone barcode scanner based on ML Kit Showcase App with Material Design

* Barcode detection using the Barcode API in live camera

## Steps to run the app

* Clone this repo locally
* [Create a Firebase project in the Firebase console, if you don't already have one](https://firebase.google.com/docs/android/setup)
* Add a new Android app into your Firebase project with package name com.google.firebase.ml.md
* Download the config file (google-services.json) from the new added app and move it into the module folder (i.e. [app/](./app/))
* Build and run it on an Android device

## How to use the app

This app supports two usage scenarios: Live Camera

### Live Camera scenario

It uses the camera preview as input and contains one workflow: barcode detection.
- Barcode detection
  - Barcode scanning with whole screen and showing scanned code

## Original project license
© Google, 2019. Licensed under an [Apache-2](./LICENSE) license.
