---
layout: post
title: How to stop the jailbreak certificate from getting revoked
date: 2017-08-22 16:00:00
---

Hey,
welcome to my first blog post, today i'll show you how to stop the Yalu app and phoenix from getting revoked 
when you download them OTA (without computer) as you might know i'm hosting both of yalu and phoenix here: ayouch.me/jbme & ayouch.me/phoenix
and it's cool to be able to jailbreak an idevice without the need of a computer like the old days (jailbreak-me way) but the 
only problem is that apple hate that and they try their best to stop it, so they revoke the used certificate (and sometimes it
happens often because of some kids reporting the certificate to apple) anyway this not a problem anymore because today we have
a fix.
Great,so if you want it to last a year for you just add this repo: http://iapps4u.net/cydia & install a package called 
nomorerevocations and BOOM you fixed this and now you're safe even if apple revoke the certificate next time you'll not be affected
because basically this package once you install it, it automatically block ocsp.apple.com on the hosts file which mean that your
device can't connect anymore to apple revocation server and that's why you're safe and the certificate will keep working until
it's expiry date like if the revocations didn't happen (pangu used this method on 9.3.3 jailbreak that's why it never stopped 
working untill the expiry date which mean that it lasted for a full year) and also i want to mention that this method is safer
than the vpn profile method (but also it works only for jailbroken devices)
BTW i'm not the developer of that package or the owner of that repo it's by @Jakeashacks so if you have more questions feel free
to ask him!
(hurry up and do it now while it's signed because once it's revoked it's too late and you can't rescue it)
