# push2phone
Script to send push notifications from unix.

This is a script to send notification from unix to your android or ios device.
It uses www.pushover.com as the service provider.

#### To get this to working : 

1.	Create an account in www.pushover.com. Note your userid.

2.	Download the app on your mobile device, sign in and give it a device name.

3.	Create a app in the web app, note its appid.

4.	Create a credentials file, “.pushover” in your home with access permission 700.
      Template :
      _token='YOUR_APP_CODE'
      _user='YOUR_USER_CODE'
 
6.	Copy the following scriptfile in your ~/bin.

7.	To run it.
     push2phone <Notification Header> <Notification Message>
Eg:  $ push2phone "Test Notification Header" "This is a test notification to device"


Source of Information : 
https://www.cyberciti.biz/mobile-devices/android/how-to-push-send-message-to-ios-and-android-from-linux-cli/
