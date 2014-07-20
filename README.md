One Touch Reboot
================

An application to reboot android device on launch<br>

Reboot your android device with one touch.<br>
This application requires ROOT access.<br>
Source code is at https://github.com/reddyr/OneTouchReboot<br>
<br>
Below is the key logic
<br>```Process process = Runtime.getRuntime().exec("su");
DataOutputStream outputStream = new DataOutputStream(process.getOutputStream());
outputStream.writeBytes("reboot" + "\n");
outputStream.flush();```
<br>
![Requesting for root access](https://github.com/reddyr/OneTouchReboot/blob/master/res/screenshots/Screenshot_2014-07-20-03-48-56.png)
<br> 

| Website  | URL |
| ------------- | ------------- |
| Source code  | https://github.com/reddyr/OneTouchReboot  |
| PlayStore  | https://play.google.com/store/apps/details?id=org.eguys.reboot  |


