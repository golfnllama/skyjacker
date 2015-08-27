# skyjacker

PURPOSE -->
  This project is designed to demonstrate the vulnerabilities present in current wireless technology.
  Using the TShark, this script collects and analyzes broadcast Probe Requests sent by mobile devices 
  looking to associate with an access point. Only the SSIDs present in the broadcasts are saved. These 
  SSIDs are written to the screen and organzied alphabetically.

REQUIREMENTS --> 
Wireless network adaptor must be in monitor mode (mon0).
Tshark must be installed.
Script must be run as root.
Term:ANSIScreen perl module must be installed.

NOTES --> A file called airodump.txt will be created in the script's working directory. This file contains
the SSIDs that were captured.
