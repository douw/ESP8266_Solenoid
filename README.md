# ESP8266_Solenoid
A solenoid controller based on [terryjmyers](https://github.com/terryjmyers)/**[_ESP8266Template](https://github.com/terryjmyers/_ESP8266Template)**

This is very much a work in progress and not operational yet. 

<!--

Features:

1. Serial command interface
2. Telnet command interface, (login required)
3. Serial and telnet commands share common interface
4. Stores website login credentials in salted hash on EEPROM
5. SPIFFS Storage of config.json for network settings, project name, and sensor scaling(calibration data), NTP settings, etc
6. Access Point automatically created when WiFi not configured
7. Webpage allows viewing of data, configuring network settings, viewing system data, editing files in SPIFFS, and more
8. NTP integrated with time zone offset and DST calculations
9. SMTP email
10. Web based OTA Updates

How to install:

1. Install my other libraries or delete references:
    1. https://github.com/terryjmyers/PulseTimer.git
    2. https://github.com/terryjmyers/LoopStatistics.git (not really needed you can delete references to this mroe easily)
    3. https://github.com/terryjmyers/TimeLib.git (Updated for DST and time zone offsets)
2. Install the arduino IDE file system uploader: https://github.com/esp8266/Arduino/blob/master/doc/filesystem.md#uploading-files-to-file-system
3. Upload /data folder using file system uploader tool from Arduino IDE
4. Download program
5. Connect to Access point to setup WiFi credentials, or use serial interface.  WiFi credentials are ONLY stored on the ESP WiFi config memory section
6. Optional things to setup (things I've blanked out before uploading sketch that you'll want to fill back in:
    1. ProjectName which becomes the SSID and mDNS responder
    2. FUNCTIONAL_DESCRIPTION & CONTACT INFORMATION which shows on the root webpage
    3. BACKDOOR_PASSWORD which can be used to bypass HTTP and telnet login
    4. EMAILBASE64_LOGIN, EMAILBASE64_PASSWORD, FROM, and EmailAddress in the email section
    5. sha1salt which is appended to the plain text web/telnet login/password before hashed and stored in EEPROM.  Change to be 17 bytes of random data-->
