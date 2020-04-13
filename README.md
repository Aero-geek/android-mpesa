# android-mpesa
This is a sample app showing the integration of mpesa with android. Credit to Licio Lentimo for his tutorials on doing the integration

#How to use
1. edit the gradle.properties file and add your consumer_key and consumer_secret from safaricom apis.
2. edit the AccessTokenInterceptor.java file with the following 
  a. business short code ; usually 174379 for sandbox environments
  b. passkey; can be found on safaricom portal
  c. partyb; this is same as business short code
  d. callback url; can be obtained from http://mpesa-requestbin.herokuapp.com/

 
