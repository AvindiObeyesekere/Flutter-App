# Flutter-App
Developing with Flutter + Dart 

#Code for Flutter Mobile app in the Master Branch - Ocean Rescue

--Instructions for Seeting up the project

1. Download Flutter SDK:

--Go to the official Flutter website: Flutter SDK.
Choose your operating system (Windows, macOS, or Linux) and follow the installation instructions.
Set up environment variables:

2. For Windows:
-Go to Control Panel > System > Advanced System Settings > Environment Variables.
-Add a new system variable for Flutter:
-Variable name: PATH
-Variable value: <path-to-flutter-sdk>\flutter\bin

3. Install Flutter and Dart Plugins in Android Studio--

-Open Android Studio.
-Go to Preferences (macOS) or File > Settings (Windows/Linux).
-In the Plugins section, search for the Flutter plugin and install it.
-After installing Flutter, the Dart plugin will be installed automatically.

4. Set Up Android Emulator (Optional but recommended)
In Android Studio, open the AVD Manager (from the top-right toolbar, click on the AVD Manager icon).
Create a new virtual device (e.g., Pixel 5) with a system image of your choice (preferably with Google APIs).
Ensure the emulator works by running it.

5. Check Flutter Version Compatibility
You can also run the following command to see your current Flutter version:

flutter --version

6. Ensure you are using a stable version. If necessary, you can upgrade Flutter by running:

flutter upgrade


7. Check for compatible Dart and Flutter versions with:

flutter doctor 
8. Resolve Dependencies

flutter pub get



