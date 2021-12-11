https://capacitorjs.com/docs/guides/push-notifications-firebase

Android
Integrating Firebase with the Android app
This section more-or-less mirrors the setting up Firebase using the Firebase console documentation. See below for specific Capacitor-related notes.

Go to the Project Overview page for your Firebase project and at the top, click on the Android icon to add a new android application.

Add new Android Application in Firebase Console
The next screen will ask you for some information about your application.

Your Android package name should match the appId from your capacitor.config.json file
We used com.mydomain.myappname for this Capacitor app ID, so that is what we’ll use for this entry.
Nickname and Debug Signing Certificate are optional
Then click the Register app button.

Download and Use the google-services.json file
The next prompt will ask you to download a google-services.json file. This file contains the information your Capacitor app needs to connect to Firebase from Android.

Download the google-services.json file to your local machine. Then move the file into your Capacitor Android project directory, specifically under android/app/.