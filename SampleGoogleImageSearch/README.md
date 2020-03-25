SampleGoogleImageSearch
=======================
● User can enter a search query that will display a grid of
images from Google Images.
● User can modify advanced search options such as:
○ Size (small, medium, large, extra-large)
○ Color filter (black, blue, brown, gray, green, etc...)
○ Type (faces, photo, clip art, line art)
○ Site (espn.com)
● User should be able to endlessly scroll
○ Automatic “endless” pagination as user scrolls

NOTE: There is an error while calling Google Ajax API similar to the one noticed here: http://stackoverflow.com/questions/23458293/how-to-avoid-connection-errors-in-android-async-task

The issue is fixed after adding below App permissions:
   <uses-permission android:name="android.permission.INTERNET" /> 
   <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
