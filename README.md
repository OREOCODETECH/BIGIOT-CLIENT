BIGIOT-CLIENT<br/>
This is my first time release project using github,and now i'm still learning how to use it,sorry for the inconvenience.<br/>
<br/>Background<br/>
This project able to use ESP8266 connect to www.bigiot.net and control GPIO without coding for ESP8266.<br/>
<br/>Feature<br/>
-Built in GUI web interface for settings.<br/>
-Auto reconnect when client or WiFi disconnected.<br/>
-Can diretly control GPIO without any coding,which can reduce the cycle and difficulty of diy IOT devices.<br/>
-Support serial stream client content,can extrace control content form client JSON content.<br/>
<br/>Usage<br/>
WARNING:WRITE THIS FIRMWARE WILL FORMAT ALL CONTENT AND SETTINGS IN ESP8266,MAKE SURE FULLY BACKUP BEFORE WRITE FIRMWARE.<br/>
1.Download .bin file in release page.<br/>
2.Write .bin file into ESP8266 using "flash_download_tools_v3.6.8_0" by expressif (Recommend) or other similar software.<br/>
3.Search and connect AP: SSID:"ESP_IOT" PASSWORD:"12345678".<br/>
4.Visit "192.168.4.1" in browser.<br/>
5.Click "Settings" tag.<br/>
6.Fill settings and click "SAVE" button, then click "REBOOT" button to make sure that your changes are applied.<br/>
7.Get ESP8266 new IP in rounter by serial port or rounter DHCP list.
8.Visit ESP8266 new IP address in browser.<br/>
9.If all settings are correct,you should able to get "Device Checkin" status is "true" in Status page.
-In "status" page,you can get ESP8266 working details.<br/>
