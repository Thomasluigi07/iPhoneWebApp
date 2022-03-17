# Where can I try this?
Go to https://thomasluigi07.github.io/iPhoneWebApp/!
# What can i do with this?
Customise this as you wish! Works on all iOS versions as long as you have certificate fixing for older versions.
## How do iPhone Web Applications work?
They are made with html. You need an icon and a splash screen, and also need to add this code to your html head:
```
<meta name="apple-mobile-web-app-capable" content="yes" />
<meta name="apple-mobile-web-app-status-bar-style" content="black" />
<link rel="apple-touch-icon" href="icon.png" />
<link rel="apple-touch-startup-image" href="splash.png" />
```
Icons need to be 57x57 for older iOS versions.
## How do i save this to my homescreen?
Press the share button at the bottom of the screen, then press "Add to Home Screen". Feel free to try without an internet connection, and delete once you are done.
## Why am I getting a certificate error????
You need to install the Let's Encrypt certificates to get around this problem. Use https://cydia.invoxiplaygames.uk/certificates to download them if you're on iOS 6 or newer (YOU DO NOT NEED TO JAILBREAK YOUR DEVICE). If you're on an older device, you'll need to manually install it (which i have no idea how to do so, plus you'll need to have a jailbroken device.)
