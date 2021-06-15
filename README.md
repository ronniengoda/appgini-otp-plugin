# appgini-otp-plugin
This plugin will enable you activate two step verification using email OTP in your Appgini application. Once activated, all users who attempt to login to your application will be sent an OTP to their registered email for verification. This happens all the time a user logs in. To use this plugin you must use SMTP as your mail sending method.

Want to see it in action? create an account and try login here: https://payherokenya.com/sps/portal

# How to setup
1. Download the appgini-otp zip file into your plugins folder in your appgini project.
2. Extract the contents of the zip file and ensure it goes into the appgini-otp folder inside the plugins folder.
3. Make sure your enable SMTP as your mail sending method and provide all the required details for that.
4. Go to Admin area and under the plugins menu you will see Appgini OTP option, select it
5. On the plugin page you will see a green button written Install Appgini OTP, click on it to install the plugin.
6. After install the plugin will be active now: you will have the option to activate or deactivate it if you want.
7. All users who will now attempt to login will need to provide their correct username and password, then after normal appgini authentication the Appgini OTP will send them an email containt a code they will use to verify their identity. If a user doesnt provide this code, they cannot access the account or perform any operations.

Thats it!! i hope you have a great experience using this plugin, incase of any problem dont fail to raise an issue or a better sugestion.
