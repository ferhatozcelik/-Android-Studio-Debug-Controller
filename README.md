
# Android Studio Debug Controller Plugin


##Releases Version

[<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1a/JetBrains_Logo_2016.svg/1200px-JetBrains_Logo_2016.svg.png" width="100"/>](https://plugins.jetbrains.com/plugin/18732-debug-controller?preview=true)

[Download Plugin](https://plugins.jetbrains.com/plugin/18732-debug-controller?preview=true)

[Download Zip](https://github.com/ferhatozcelik/Android-Studio-Debug-Controller/blob/master/Debug-Controller.zip?raw=true)

##Adb Komutları

###Start Server
> adb start-server

###Kill Server
> adb kill-server

###Wifi Connect
> adb -s <-devicename-> tcpip <-deviceip:port->

###Launch App
> adb -s <-devicename-> shell monkey -p <-packagename-> -v 1

###Kill App
> adb -s <-devicename-> shell am force-stop <-packagename-> 

###Restart App
> adb -s <-devicename-> shell am force-stop <-packagename->
> 
> delay:1500ms
> 
> adb -s <-devicename-> shell monkey -p <-packagename-> -v 1

###Clear App Data
> adb -s <-devicename-> shell pm clear <-packagename-> 
> 
> delay: 1500ms
>
> adb -s <-devicename-> shell monkey -p <-packagename-> -v 1

###Uninstall App
> adb -s <-devicename-> uninstall <-packagename-> 

 ###Install App
> adb -s <-devicename-> install <-apkpath-> 



[<img src="https://ferhatozcelik.com/assets/images/logov2.png" width="50"/>](https://ferhatozcelik.com/)
by Ferhat OZCELIk
