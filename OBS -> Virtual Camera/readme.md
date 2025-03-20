sch:
- https://www.google.com/search?q=obs+virtual+camera+webcam0
- https://www.google.com/search?q=obs+to+android+studio , https://www.google.com/search?q=obs+to+android+studio+camera
- https://www.google.com/search?q=screen+to+webcam0

# set: Resolution
sch: https://www.google.com/search?q=android+studio+avd+set+camera+resolution

https://stackoverflow.com/questions/79239634/how-to-change-the-camera-resolution-in-android-studio-avd

code:
```
avd_instance=Pixel_9
config=~/.android/avd/${avd_instance}.avd/config.ini

echo "hw.camera.maxHorizontalPixels = 1920" >> $config
echo "hw.camera.maxVerticalPixels = 1080" >> $config
```


# transform: Flip Horizontally
https://stackoverflow.com/questions/79239634/how-to-change-the-camera-resolution-in-android-studio-avd
