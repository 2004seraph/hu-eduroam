# Fork to Learn How eduroam Config Works

So far I've been able to reproduce a build. However, it required turning off linting in the Android Gradle config because of changes in the ecosystem: the app doesn't request FINE_LOCATION for the WiFi config and doesn't check to see if it has those permissions before using the APIs.

## HU Berlin eduroam
-----------------

Android app for configuring [Eduroam](http://eduroam.org) wifi network for users of [Humboldt University of Berlin](https://www.hu-berlin.de) on Android 4.3 and up.

The app is based on [nikhef-eduroam](https://github.com/synnack/nikhef-eduroam) from Wilco Baan Hofman.

[<img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png"
     alt="Get it on Google Play"
     height="80">](https://play.google.com/store/apps/details?id=de.hu_berlin.eduroam)
[<img src="https://f-droid.org/badge/get-it-on.png"
     alt="Get it on F-Droid"
     height="80">](https://f-droid.org/packages/de.hu_berlin.eduroam/)

## License

Apache-2.0
