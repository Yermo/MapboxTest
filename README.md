# Mapbox Test App

This is a simple Android application is in support of a StackOverflow question.

It loads a Mapbox native GL map of New York. It was created following the Getting Started 
steps documented by MapBox here: https://www.mapbox.com/install/android/

To run it, you will need to get a free access token from MapBox and add it to the 
app/src/main/java/com/amapboxtest/mapboxtest/MainActivity.java file.

The intent behind creating this minimal app was to determine whether or not a Pause/Resume crash in the NativeScript Mapbox plugin 
(as mentioned here: https://github.com/EddyVerbruggen/nativescript-mapbox/issues/271 ) is due to a bug in the base Mapbox GL
library or is due to something in the Nativescript plugin.

As it turns out, this app does not crash under those circumstances which implies there's something about the Nativescript plugin 
that's causing the crash.
