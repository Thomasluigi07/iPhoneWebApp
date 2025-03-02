# Where can I try this?
Go to http://iwa.thomasluigi07.com/
# What can i do with this?
Customise this as you wish! Should work on all iOS versions as long as the certificates used works on that iOS version (if using HTTPS)
## How do (old) iPhone Web Applications work?
They are made with html. You need an icon and a splash screen, and also need to add this code to your html head:
```
<meta name="apple-mobile-web-app-capable" content="yes" />
<meta name="apple-mobile-web-app-status-bar-style" content="black" />
<link rel="apple-touch-icon" href="icon.png" />
<link rel="apple-touch-startup-image" href="splash.png" />
```
If you would like more info about the older versions of iPhone web applications, go here: https://developer.apple.com/library/archive/documentation/AppleApplications/Reference/SafariWebContent/ConfiguringWebApplications/ConfiguringWebApplications.html
## How do i save this to my homescreen?
Press the share button at the bottom of the screen, then press "Add to Home Screen". Feel free to try without an internet connection, and delete once you are done.
## Why am I getting a certificate error????
Disable HTTPS and connect using HTTP, or install the certificate you're using for your site, such as the ISRG Root X1 CA (Let's Encrypt) certificate. Go to http://cydia.invoxiplaygames.uk/certificates in Safari to download them if you're on iOS 6(iOS 5?) or newer. If you're on an older iOS version that doesn't support certificate installation, you'll need to manually install it (not sure how).
