# SVPHM AMS Web App

Intended for use as an **iOS** web app, while waiting on the creation of an SVHA Apple Developer Account. For Android users, the app can be downloaded from the Google Play Store [here](https://play.google.com/store/apps/details?id=com.adrianwong.svphm.ams_app).

## Usage
To use the app as intended:
* Navigate to [https://svphm-ams.github.io/ams-app/](https://svphm-ams.github.io/ams-app/) in Safari
* Click on the "Share" <img src="share-button.png"> button
* Click on the "Add to Home Screen" <img src="add-to-home-screen.png"> button
* Follow the prompt to add the app to the home screen
* Open the app from the home screen

## Known Issues
* The app can still be accessed from the browser, but has some unintended behaviour due to Apple permanently enabling pinch-to-zoom for accessibility reasons even when the viewport setting has been set to `user-scalable=no`. See: [What's New in Safari 10.0](https://developer.apple.com/library/content/releasenotes/General/WhatsNewInSafari/Articles/Safari_10_0.html).
* The app is designed to be viewed in portrait mode. However (while it supposedly should), specifying an orientation in the web app manifest does not lock the web app's orientation. Beyond performing some ridiculous workarounds, there appears to be no easy way to do this. See: [here](https://stackoverflow.com/questions/5298467/prevent-orientation-change-in-ios-safari) and [here](https://developer.mozilla.org/en-US/docs/Web/API/Screen/lockOrientation#Browser_compatibility).
* No splash screen. Splash screens have been broken on iOS web apps for quite some time now. See: [here](https://forums.developer.apple.com/thread/23924).
