# powbot_logs
This little tool will make finding logs for your emulator or device easier. Scriptwriters greatly appreciate logs and it helps them debug/fix issues with their scripts.

_Screenshot_
![image](https://github.com/Nickert1337/powbot_logs/assets/98966743/addc104a-b7f5-4a37-a425-3ed362be9bdf)

# Removing 'spammy' lines from the log
Open 'blacklisted_lines.ini' and add a part of the line you want to remove from the log. Regex can be used to match multiple lines with changing formats. 

# Help
## Emulator or device does not show up in devices list
Usually this means ADB is not enabled, so make sure ADB is enabled.

### Enabling ADB on LDPlayer:
Open settings for the emulator you are trying to see and make sure "ADB debugging" is on "open local connection"
![image](https://github.com/Nickert1337/powbot_logs/assets/98966743/e7f736ea-1bc3-40d3-aefc-ab9fd4c411a8)

