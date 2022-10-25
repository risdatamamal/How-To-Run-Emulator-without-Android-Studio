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

4 Replace [YOUR_EMULATOR_DEVICE_NAME] with the device name you created in emulator

5 To get the device name go to: C:\Users\%username%\AppData\Local\Android\sdk\tools

6 Run cmd and type: emulator -list-avds

7 Copy the device name and paste it in the batch file

8 Save the file as emulator.bat and close

9 Now double click on emulator.bat and you got the emulator running!
