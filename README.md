# Simple_AR_App
A simple AR app using latest version of ARcore (dated: June 2021)
-------------

This AR app uses ARcore version 1.24.0 and sceneform version 1.16.0 to build an ARmodel which uses your emulator/phone's camera to display a .glb model in the app ->res ->raw folder. The raw folder has 3 different models taken from Google Poly. Choose any you like or add more in the same folder. Just change the argument in the 
```
.setSource()
```

function in the MainActivity.java file.

Also your phone should have latest version of Google AR services installed from Playstore if you run the app on phone.

This project is perfect for a demo of AR services and serves as an entry into makin AR apps.
