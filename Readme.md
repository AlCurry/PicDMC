# PicDMC
### Latest version in the app store, as of May 1, 2018

New features support sharing on social media, sms, email and others, and date taken printed on the main picture display.

### In the app store for iphone and ipad, as of December 26, 2017
#### final project for ios app development class at Noble Desktop, Soho, NYC - September - December 2017

Screenshot .png files in this directory and in the app store.

PicDMC is short for picture distance, map, (weather & time) conditions. The app uses the IOS 
UIImagePickerController to allow the selection of a photo. Based on the photo’s meta data, 
specifically gps latitude and longitude, it determines the user’s current distance from where 
the picture was taken. Also the address, current weather, and time at the picture's location. 
These details are displayed in the lower left of the picture.

From this view, a user may select "Photo", to display the original image, "Map" to show the address 
on a map, or "Select" to select another image. A couple of included screen shots illustrate this.

There are some possible icons which could be used in place of text for the buttons included in the 
projects Assets.xcassets, though my preference is for text. Button color can be customized in line 21 
of AppDelegate.swift.

There are settings for the app implemented using the IOS Setting Bundle for metric or imperial measurements, 
font color (black or white), and whether or not to display labels.  Also InAppSettingKits cocoa pod was used 
to access the settings from within the app.

