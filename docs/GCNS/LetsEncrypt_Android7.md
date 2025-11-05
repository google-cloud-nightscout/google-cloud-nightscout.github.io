---
title: "Let's Encrypt Support Ended for Android 7"
description: "Learn why Android 7 devices can no longer access Google Cloud Nightscout sites with Let's Encrypt certificates, understand SSL handshake errors, and get guidance for continued access."
---

# Let’s Encrypt Support for Android 7 Has Ended
[Google Cloud Nightscout](../../) >> Let's Encrypt and Android 7  

Google Cloud Nightscout uses Let’s Encrypt. Unfortunately, free support for Android 7 has ended, as described [here](https://community.letsencrypt.org/t/support-for-android-7-and-older-from-oct-2024/216446).  If you try to access a Google Cloud Nightscout site using Android 7 or older, it will fail. Devices running newer versions will continue to work fine.  
  
You may see the following error on your uploader:  
`javax.net.ssl.SSLHandshakeException: Java.security.cert.CertPathValidatorException: Trust anchor for certification path not found.`  

In the case of a follower app or web browser, you may see a message like:  
`... can't open the page.`  
  
To access your site, use a device running Android 8 or newer.  
  
