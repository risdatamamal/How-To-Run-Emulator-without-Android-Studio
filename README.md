# How To Run Emulator without Android Studio

You can make a batch file, that will open your emulator directly without opening Android Studio. If you are using Windows:

1 Open Notepad

2 New file

3 Copy the next lines into your file:
```
 cd /d C:\Users\%username%\AppData\Local\Android\sdk\tools
 emulator @[YOUR_EMULATOR_DEVICE_NAME]
```

Notes:

- Replace [YOUR_EMULATOR_DEVICE_NAME] with the device name you created in emulator

- To get the device name go to: C:\Users\%username%\AppData\Local\Android\sdk\tools

- Run cmd and type: 
```
emulator -list-avds
```

- And you can see [YOUR_EMULATOR_DEVICE_NAME]

- Run cmd and type: 
```
emulator -avd [YOUR_EMULATOR_DEVICE_NAME]
```

Example: 
```
emulator -avd Pixel_2_API_27
```
