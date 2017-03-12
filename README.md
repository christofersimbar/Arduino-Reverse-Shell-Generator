# Arduino-Reverse-Shell-Generator

Adapted from Powershell-Reverse-Rubber-Ducky Written by James Cook @b00stfr3ak44
https://github.com/b00stfr3ak/Powershell-Reverse-Rubber-Ducky

This ruby script will:</br>
1. Generates a shell script based on Windows Powershell</br>
2. Uploads the shell script to default root of Apache webserver: <b>/var/www/html/shell.txt</b></br>
3. Generates a complete Arduino sketch that will download and execute the shell script</br>
4. Run a default Apache webserver</br>
5. Open a meterpreter listener</br>

If you want to use other webserver, you can modify the arduino script later. Just change the URL.<br/>

This basic setup only works on LAN. If you want to try it using Internet, you need to configure a <b>Port Forwarding</b> or <b>DMZ</b> on your modem.
