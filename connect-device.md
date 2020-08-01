# This command using for connected into android genymotion devices

* **Ubuntu/Linux**
  ```
  root@ubuntu-server:~# adb connect 192.168.28.28
  * daemon not running; starting now at tcp:5037
  * daemon started successfully
  connected to 192.168.28.28:5555
  ```
* **MacOS**  
  ```
  macos@rootbakar:~# adb connect 192.168.28.28:5555
  connected to 192.168.28.28:5555
  ``` 
  or using if you'r want directly access into android genymotion shell
  ```
  macos@rootbakar:~# adb shell
  vbox86p:/ # 
  ``` 
