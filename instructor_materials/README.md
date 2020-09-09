## Instructor materials

This content will be run as a short [workshop](./workshop.md), where you will lead students in building a flutter app


## Leading a Flutter Session 

Session contents are available at Linkedin Learning from the App Development Brewery. Sessions are intended to be within 1 hr 30 minutes. 

| Time       |                                                                                                         |
| ---------- | ------------------------------------------------------------------------------------------------------- |
| 10 minutes | Introduction and welcome, explain the session goals                                                     |
| 30 minutes | Play the video presentation                                                                             |
| 20 minutes | Code walk-through                                                                                       |
| 15 minutes | Trial and error, make small edits                                                                       |
| 15 minutes | Open Q&A                                                                                                |
|            |

## Teaching a workshop


Before the workshop, send out an email outlining your schedule and encouraging pre-installation of the following:

https://drive.google.com/file/d/1e2_5wm2sradsvNIHgturJ29R9LZfgHH2/view?usp=sharing

One stop quick install guide for windows. 
Flutter Sessions
Extracted from, and expanded upon official flutter documentation at
https://flutter.dev/docs/get-started/install/windows	
If you do are working off a Mac please refer to
https://flutter.dev/docs/get-started/install/macos
Download flutter
https://storage.googleapis.com/flutter_infra/releases/stable/windows/flutter_windows_1.20.2-stable.zip
Extract to C:\src\flutter




 
 
Update your path
From the Start search bar, enter ‘env’ and select Edit environment variables for your account.
Under User variables check if there is an entry called Path:
If the entry exists, append the full path to flutter\bin using ; as a separator from existing values.
If the entry doesn’t exist, create a new user variable named Path with the full path to flutter\bin as its value.











Check if flutter is installed properly
Open command prompt and run flutter doctor

Download and Install android studio
https://developer.android.com/studio
when prompted, make sure to install the latest Android SDK, Android SDK Command-line Tools, and Android SDK Build-Tools, which are required by Flutter when developing for Android.
If you have an android phone
Set up your Android device
To prepare to run and test your Flutter app on an Android device, you need an Android device running Android 4.1 (API level 16) or higher.
Enable Developer options and USB debugging on your device. Detailed instructions are available in the Android documentation.
Windows-only: Install the Google USB Driver.
Using a USB cable, plug your phone into your computer. If prompted on your device, authorize your computer to access your device.
In the terminal, run the flutter devices command to verify that Flutter recognizes your connected Android device. By default, Flutter uses the version of the Android SDK where your adb tool is based. If you want Flutter to use a different installation of the Android SDK, you must set the ANDROID_SDK_ROOT environment variable to that installation directory.
Only If you do not have an android phone
Set up the Android emulator
To prepare to run and test your Flutter app on the Android emulator, follow these steps:
Enable VM acceleration on your machine.
Launch Android Studio > Tools > Android > AVD Manager and select Create Virtual Device. (The Android submenu is only present when inside an Android project.)
Choose a device definition and select Next.
Select one or more system images for the Android versions you want to emulate, and select Next. An x86 or x86_64 image is recommended.
Under Emulated Performance, select Hardware - GLES 2.0 to enable hardware acceleration.
Verify the AVD configuration is correct, and select Finish.
For details on the above steps, see Managing AVDs.
In Android Virtual Device Manager, click Run in the toolbar. The emulator starts up and displays the default canvas for your selected OS version and device.

