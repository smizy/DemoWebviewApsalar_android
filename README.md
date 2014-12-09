DemoWebviewApsalar_android
==========================

A demo webview app with Apsalar SDK on Android.

Refer to:
http://support.apsalar.com/customer/portal/articles/772141-using-javascript-in-android-application

1. Before event tracking in webview, You need to integerate Apsalar Android SDK.
(import apsala.jar into app/libs/, etc...)

 Refer to:
 http://support.apsalar.com/customer/portal/articles/717507-integrating-the-android-sdk

1. Change API key and secret in MyActivity.java

	```Apsalar.startSession(this, "<API_KEY>", "<SECRET>");```

1. Change API key in assets/www2/level2.html or assets/www/level2.html
	```"{'ps': '<API KEY>'...```
