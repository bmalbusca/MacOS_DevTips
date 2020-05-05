# Step 1 - Factory default settings
- Select "44100 HZ” and “2ch – 16 bit Integer”  

- In the pop-up box, enter ``~/Library/Preferences`` then click Go.
Scroll down and find ``com.apple.bluetooth.plist``.
Drag it to the Trash Folder and then turn off Bluetooth.  [url_source](https://www.ikream.com/how-to-fix-sound-problems-on-your-mac-running-macos-mojave-32751)


# Step 2 - Reset The Core Audio
- Use te terminal : ``sudo killall coreaudiod``

# Step 3 - Restart your computer

