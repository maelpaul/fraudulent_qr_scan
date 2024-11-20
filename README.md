# Fraudulent QR Code Scanner

A malicious app for scanning QR codes, but which also collects your personal information.

The aim of this app is to make people aware of the permissions that are requested by phone apps and the personal information that these apps can then retrieve. 

## Authors

Nathan THIVIN  
Louis-Victor LADAGNOUS  
Maël PAUL

## Install app

Follow these steps:

- Open the "QrCodeScanner" project in Android Studio.

- Change "var ipServer" by your ip address in "QrCodeScanner/app/src/main/java/com/zizou/qrcodescanner/MainActivity.kt". 

- Change "sdk.dir" by your path to your Android SDK in "Gradle Scripts/local.properties".

- Sync project with Gradle files and upgrade Gradle if needed.

- Go to "Build" -> "Make Project".

- Go to "Build" -> "Build App Bundle(s) / APK(s)" -> "Build APK(s)". The APK can be found in "QrCodeScanner/app/build/outputs/apk/debug/app-debug.apk".

- Connect your phone to your computer with an usb cable and copy the APK on your phone.

- On your phone, touch the APK file and select "Install" to install the app. Don't scan the app if asked.

## Use the app

- Follow the instructions here "https://github.com/maelpaul/website_qrcode" to launch the server.

- Open the app and grant all the permissions.

- Scan a QR code and click on link to go on the website.

## 

![Logo](app-logo.png)
