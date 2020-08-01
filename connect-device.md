# This command using for connected into android genymotion devices

* **Ubuntu/Linux**

  ```adb connect 192.168.28.28```
  
* **MacOS**  

  ```adb connect 192.168.28.28:5555``` 
  or using if you'r want directly access into android genymotion shell
  ```adb shell``` 

* **Connect into specific device, if you'r connected into multiple device**

  ```
  macos@rootbakar ~ % adb devices
  List of devices attached
  192.168.1.17:5555	device
  192.168.56.128:5555	device
  ```

  ```adb -s 192.168.1.17:5555 shell```
