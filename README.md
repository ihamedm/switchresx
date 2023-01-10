#SwitchResX Settings for LG 21:9 UltraWide

SwitchResX is a utility that allows users to override the default resolution settings in OSX. For more information, including download links, vist http://www.madrau.com/ .

##Disabling System Integrity Protection (SIP)

If you are running OSX 10.11 or higher, SIP must be disabled. To disable SIP do the following:
  - Boot into the recovery partition by pressing CMD + R when starting up your Mac.
  - Once in recovery mode, open a terminal window.
  - Type the command csrutil disable
  - Reboot

##Adding Custom Settings
  - After launching SwitchResX, select the external monitor from the list on the left. 
  - Select the 'Custom Resolutions' tab.
  - Add a new custom resolution be clicking the + symbol at the bottom of the window.
  - Adjust the settings to match the appropriate PNG provided in this gist.
  - Press 'Ok'
  - Close SwitchResX and save when prompted.
  - Restart your Mac.
  
  After following these steps, you should be able to adjust the resolution of your external monitor through the 'Display'    window in System Preferences. 