# St. Sebs Docs

## How to install code onto the robot
1. go to `Gradle` plugin on the right hand side
2. (need to verify if this is necessary) select `Tasks` -> `build` -> `build`
3. confirm that there's no error
4. select `TeamCode` -> `build` -> `build`
5. confirm that there's no error
6. connect to the robot wifi
7. select `TeamCode` -> `install` -> `installDebug`
8. confirm that the log says
   ```  
> Task :TeamCode:installDebug
Installing APK 'TeamCode-debug.apk' on 'Control Hub v1.0 - 7.1.2' for :TeamCode:debug
Installed on 1 device.
   ``` 
9. check the robot (driver hub) and confirm it has the code 

 