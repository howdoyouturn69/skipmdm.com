# skipmdm.com

- Long press power button to shut down
- Long press power button to boot into recovery
- Connect to wifi to activate mac
- Open safari
- go to: skipmdm.com (I know, sounds fishy AF)
- click copy autobypass
- quit safari
- open terminal (tools --> terminal)
- command + v to paste the command and press enter
- Type: 1 and press enter
- press enter again to leave the default username (Apple)
- press enter again to leave the default password (1234)
- wait for it to finish and reboot
- sign in into the Apple profile (1234 password)
- breeze through the setup skipping everyting (Apple ID, Siri, Fingerprint, etc)
- Once on the desktop, create a new admin user with your actual info (Full Name, Username, Password)
- log out of the apple profile, and sign in into your newly create profile
- actually set up every properly now (Apple ID, Siri, Fingerprint, etc)
- once on the desktop, destroy the Apple profile and it's data
- profit

(Optional) Run in Terminal
- ```sudo launchctl disable system/com.apple.devicemanagementclient.teslad```
- ```sudo launchctl disable gui/501/com.apple.mdmclient.agent```
