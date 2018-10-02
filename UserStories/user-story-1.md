## User Story Formular
```
As a <User Role>  
I Want <Goal>  
So <Benefit>.  
```

## User story 1

As a user,  
I want to update the frequency of measurement,  
so that I get more telemetry.  

### solution
I would make the program able to receive commands and then update the property, which controls the frequency.

## User story 2

As a user,  
I want to update a program, OTA, on windows 10 iot core,
so that I do not have to do it on local lan. 

### solution
  
This is a jungle, but when searching the web for answers this seems like the best way to go [MS MDM CM](https://docs.microsoft.com/en-us/windows/client-management/mdm/enterprisemodernappmanagement-csp)  
  
Windows store is currently not supported at the moment on windows iot [Link](https://docs.microsoft.com/en-us/windows-hardware/service/iot/servicing-msstore)  



The following links descripes a way to update apps on Windows iot core 
  
[how to push...](http://blog.infernored.com/how-to-push-updates-to-raspberry-pi-uwp-apps-in-prod)  
[sideload](https://matthijs.hoekstraonline.net/2016/09/27/auto-updater-for-my-side-loaded-uwp-apps/)  


