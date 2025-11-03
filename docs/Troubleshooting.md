---
title: "Troubleshooting Google Cloud Nightscout"
description: "Guide to diagnosing and fixing common problems with Google Cloud Nightscout. Documentation and help for setup, errors, and configuration issues."
---

# Google Cloud Nightscout Troubleshooting 
[Google Cloud Nightscout](../) >> [Troubleshooting](./GCNS/Troubleshooting.md) >> Stopped Nightscout troubleshooting  
  
If you cannot log into your virtual machine, it is possible that it has stopped.  See the following section.  
<br/>  
  
---  
  
#### **Stopped virtual machine**  
Go to [Google Cloud](https://cloud.google.com/).  Sign into Google.  
Click on Console.  
![](./images/Console.png)  
  
From the menu, select "Compute Engine > VM instances".  
  
You should see something like what is shown below with a checkmark under status.  
![](./images/VMisRunning.png)  
  
But, if you see something like what is shown below with a square symbol (stop) under status, it means your virtual machine has stopped.  
![](./images/VMhasStopped.png)  
  
If you see that, please click on the 3-dot drop-down menu and select "Start".  
![](./images/StartVM.png)  
<br/>  
<br/>  
  
---  

#### **Restart the server**  
There are actions that require a restart after.  For example, any update that changes the startup routine needs a restart to complete.  If you have forgotten to restart when you should have, it could be the cause of the problem.  
If you can log into your virtual machine, but Nightscout is not running, [restart](./Restart.md) now.  
Restarting the server is harmless and can resolve many issues.  So, it should be the first step in troubleshooting.  
<br/>  
<br/>  
  
---  
  
#### **Wait**  
After you restart the server, Nightscout will not be running immediately.  It may need a minute to start operation.  
If it's still not running after you wait a minute, look at the [status page](./Status.md).   
<br/>  

---  
  
#### **Status page flags**  
If you see items in red on the status page, look at the [status page flags](./StatusKey.md) and follow the instructions.  
<br/>  
  
---  
  
#### **Free DNS login**  
It is common to forget to log into your Free DNS account once every 6 months.  Log in.  If you see anything unusual, see [this](./FreeDNS_Min_Login.md).  
<br/>  
  
---  
  
#### **Phase 1**  
If you have restarted the server and logged into your Free DNS account and your Nightscout is still not running and there are no red markers on the status page, install Nightscout phase 1 from the Google Cloud setup submenu.  
Then, [restart](./Restart.md).  
  
