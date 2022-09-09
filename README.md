<p align="center">
<img src="https://github.com/D3VL/L3MON/raw/master/server/assets/webpublic/logo.png" height="60"><br>
A cloud based remote android managment suite, powered by NodeJS
</p>

## Features

- GPS Logging
- Microphone Recording
- View Contacts
- SMS Logs
- Send SMS
- Call Logs
- View Installed Apps
- View Stub Permissions
- Live Clipboard Logging
- Live Notification Logging
- View WiFi Networks (logs previously seen)
- File Explorer & Downloader
- Command Queuing
- ~~Built In APK Builder~~

## Prerequisites

- NodeJs
- A Server

## Runs on Localhost or Server

npm install
node index.js

or

npm start

6. Set a Username & Password
   Default login details:
   usermame: admin
   password: password

Change Password

    1. Stop L3MON
    2. Open `maindb.json` in a text editor
    3. under `admin`
        - set the `username` as plain text
        - set the `password` as a LOWERCASE MD5 hash
    4. save the file
    5. run `npm start`

7. in your browser navigate to `http://<SERVER IP>`

## Notes

1. There is no online builder
2. You have to buld or edit the payload using apk editor or Android Studio
3. Will work on all platforms

## Whats New

1. Nothing new, fixed ejs errors
2. Fixed dependency issues, vulnerabilities
3. Fixed app crash after device restart ( New issue raised, used UUID, so each restart you will loose previous id)

## Todo

1. Location is always throws empty (even in the Original One)
2. Null pointer error while using Device Id as an Identifier
3. Waiting for your responses

## Screenshots

|                                                                                                                                                                                                        |                                                                                                                                                                                                                                                                            |                                                                                                                                                                                                           |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | --- |
|          <a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/call_log.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/call_log.png"> Call Log</a>          | < href="https://github.com/D3VL/L3MON/raw/master/Screenshots/apk_builder.png"> <a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/clipboard.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/clipboard.png"> Clipboard Log</a> |                                                                                                                                                                                                           |
|          <a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/contacts.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/contacts.png"> Contacts</a>          |                                             <a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/devices.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/devices.png"> Devices</a>                                              |    <a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/file_explorer.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/file_explorer.png"> File Explorer</a>    |     |
|           <a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/gps_log.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/gps_log.png"> GPS Log</a>            |                                             <a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/sms_log.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/sms_log.png"> SMS Log</a>                                              |           <a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/sms_send.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/sms_send.png"> Send SMS</a>            |     |
| <a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/installed_apps.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/installed_apps.png"> Installed Apps</a> |                                         <a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/microphone.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/microphone.png"> Microphone</a>                                         | <a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/notification_log.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/notification_log.png"> Notifications</a> |     |
|        <a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/event_log.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/event_log.png"> Event Log</a>         |                                                <a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/login.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/login.png"> Login</a>                                                 |     <a href="https://github.com/D3VL/L3MON/raw/master/Screenshots/wifi_manager.png"> <img width="1604" src="https://github.com/D3VL/L3MON/raw/master/Screenshots/wifi_manager.png"> WiFi Manager</a>      |

## Thanks

L3MON-MOD

All Credits goes to ORIGINAL LEMON author, though the project is archived and did not allow to contribute and ExploitSpy has a backdoor, that's why I have to Mod this for you

## Disclaimer

<b>We Provides no warranty with this software and will not be responsible for any direct or indirect damage caused due to the usage of this tool.<br>
L3MON-MOD is built for both Educational and Internal use ONLY.</b>

<br>
<p align="center">Reborn with ❤️ By <a href="//techncyber.com">Techncyber</a></p>
<p align="center" style="font-size: 8px">v.2.0.0</p>
