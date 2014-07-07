---
layout: post
title:  "Using Whatsapp on Windows without Bluestacks"
date:   2014-07-01 21:18:35
categories: 
---

This post explains how to use Whatsapp on your Windows PC without the Bluestacks application. Its very easy to setup.

1. Download and install Pidgin desktop client from [Pidgin](http://pidgin.im) .

2. Then download WhatsApp Registration Tool (WART) from [here](https://github.com/shirioko/WART/raw/master/WART-1.6.8.0.exe) .

3. Open WART. Enter your 10 digit mobile number prefixed with your country code. For ex: 91XXXXXXXXXX (91 is country code for India).

![Enter Number](http://i1051.photobucket.com/albums/s432/brijeshb42/ghost-blog/Capture1.png)

4. After that click on Request id. You will get a SMS with a code on your mobile number which you used in the last step. Enter that code in WART application and confirm.

![Enter Code](http://i1051.photobucket.com/albums/s432/brijeshb42/ghost-blog/Capture2.png)

5. Then you will get a password associated with your mobile number. Copy and save this password somewhere temporarily and close WART.

![Copy Password](http://i1051.photobucket.com/albums/s432/brijeshb42/ghost-blog/Capture3.png)

6. Now download Whatsapp plugin for pidgin from [here](http://davidgf.net/nightly/whatsapp-purple/win32/last-whatsapp.dll) .

7. Paste this downloaded dll file in ```C:\Program File(x86)\Pidgin\plugins```.

8. Now open Pidgin and add your whatsapp account. In username field, enter the mobile number as previuosly described prefixed with country code. In password field, paste the password you copied from WART application and check the ```Remember Password``` field.

9. Confirm everything and press OK.

10. Enjoy Whatsapp on your desktop :) .


## Note
Whatsapp allows only one client for an account at any instant of time. So if you are using an account on desktop, you will not be able to use that account from Whatsapp on your phone. If you want to use that account from your phone, you will have to re-register from your phone on Whatsapp.
