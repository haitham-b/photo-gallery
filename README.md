# Photo Gallery App
Technology stack: Ionic7, Angular, and Capacitor.
simple multi-platform app with functionality to take pictures, store them to local file system, and delete them.



# Requirements
- Node https://nodejs.org/en/download
- Android Studio and Android SDK https://developer.android.com/studio?gclid=Cj0KCQjwiIOmBhDjARIsAP6YhSXKDPZKNHzGENuDngZdh4BG8YIkroKHZka7L3BqlIjmmJOFBgYiPzkaAgg4EALw_wcB&gclsrc=aw.ds


# Deploying locally
to run locally in browser in dev mode
```commandline,
ionic serve
```

to open android project in Android Studion
```commandline,
ionic cap open android
```

to run in Android Studio dev mode (for android devices)
```commandline,
# - Enable developer mode on your android devide.
# - Open Android Studio -> Device Manager, and pair your Android device over wifi.
# - run the following command to run the app on your android device. dont forget to press enter to chose your device

ionic cap run android -l --external 
```


# Install the Appflow SDK
```commandline,
ionic live-update add --app-id="6e9539d3" --channel-name="Production" --update-method="background"
```
