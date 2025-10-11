# Esperantaj vortkomponentoj Android app

> 💡 This is an Android app generated with [Bubblewrap](https://github.com/GoogleChromeLabs/bubblewrap). For the contents of the app, you should check out [this repository](https://github.com/helloyanis/Esperantaj-Vortkomponantoj) instead.

## Build the project

To build the project, clone this repo, and open it with Android Studio to build it like any other project.

Please note that if you use the official site https://vortkom.🦊💻.ws your build will have an extra URL bar to show it still goes to my site

## Features of this app :

- Lightweight!
- Executes in AndroidBrowserHelper, which will pick how to execute the app :
	- In Chrome if it's installed (for most features, like the offline mode)
	- In the default browser if Chrome isn't installed
	- In a webview if no browser is installed
- Local only, after a 1st launch online to cache the necessary data you can execute the app fully offline!

## Reporting issues

Please report here any issues that are exclusive to the Android TWA version. Please try on the website first to check if the issue also occurs there.

## Build the project

To build the project, clone this repo, and open it with Android Studio to build it like any other project.

Please note that if you use the official site https://vortkom.🦊💻.ws your build will have an extra URL bar to show it still goes to my site. This is a feature of AndroidBrowserHelper which require [digital asset links](https://developers.google.com/digital-asset-links/v1/getting-started) on the website which mach the app's signature, to make sure the app doesn't connect to a malicious website.

To fix this, you can also [clone the website](https://github.com/helloyanis/Esperantaj-Vortkomponantoj), and edit the [assetlinks.json](https://github.com/helloyanis/Esperantaj-Vortkomponantoj/blob/main/.well-known/assetlinks.json) file to [include your build's signature](https://developer.chrome.com/docs/android/trusted-web-activity/android-for-web-devs#digital-asset-links).

> *Note to F-Droid team* : Please do **not** follow the fix! Once the app is built on F-Droid, I will update the digital asset links to match the app's signature!