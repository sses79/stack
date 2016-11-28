
#### Chapter 6: [Publishing your app](http://ionicframework.com/docs/guide/publishing.html)

[make apk]

```bash
keytool -genkey -v -keystore my-release-key.keystore -alias crm -keyalg RSA -keysize 2048 -validity 10000

jarsigner -verbose -sigalg SHA1withRSA -digestalg SHA1 -keystore my-release-key.keystore android-release-unsigned.apk crm

jarsigner -verify -verbose -certs android-release-unsigned.apk

zipalign -v 4 android-release-unsigned.apk crm.apk
```


> Ionic Intro Tutorial with   [Splashscreen ](http://codepen.io/mhartington/pen/dHaDC/?editors=1010) - CodePen.


Images should be **png**, **psd** or **ai** files. Minimum dimension should be 192x192 for icon image and 2208x2208 for splash screen image. The images need to be saved to resources folder instead of default ones. After we are done with it, all we need is to run the following in command prompt window.

`C:\Users\Username\Desktop\MyApp>ionic resources`

Now if you check resources/android or resources/ios folders you will see that images we added before are resized and cropped to accommodate different screen sizes. Now when we run our app on device we will see splash screen ***before the app is started*** and we will also see that default Ionic icon is changed.


##Ionic.io

####Hook up with Ionic Platform
>`$ ionic io init`

####Ionic Platform services
>`$ ionic add ionic-platform-web-client`

####Uploading
>`$ ionic upload --note "Some details about this upload"`


####Push

#####Native push
Android push notifications use the Google Cloud Messaging (GCM) service.

####Deploy

#####Update


##Ionic 2