This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# System requirements
           
#### Operating System: 
- Windows 10 64-bit
  
#### CPU: 
- Model: VivoBook_ASUSLaptop X513EAN_K513EA
- Number of cores: Four
- Clock Speed: Base Speed 2.80 GHz and Speed 3200 MHz

#### RAM:
- 15.7 GB

# Installation instructions

### First: Installing Node.js

1. Install Node LTS and choose Windows Installer. [Node.js Download Link](https://nodejs.org/en/download/ "Node.js download link website")
2. Run the Node.js installer. Follow the installation wizard, accepting the default settings unless you have specific preferences.
3. After the installation, open Command Prompt.
4. In the terminal, type "node -v" (without the quotations) and check the version numbers.
5. You have successfully installed Node.js!
- If you are having trouble installing or encounter errors, click here for [Troubleshoot](#Troubleshooting "Goto Troubleshoot")


### Second: Installing Android Studio and Configuration steps

1. Download Andriod Studio [Android Studio Download Link](https://developer.android.com/studio "Android Studio download link website")
2. Run Android Studio Setup.
3. Leave Android Studio and Android Virtual Device checked. 
4. Leave the installation for the location as it is.
5. Once the download is finished, a page saying "Welcome Android Studio" will pop up. This is where you set the environment for Android Studio.
6. The type of setup should be on Standard.
7. Select a UI Theme for what Android Studio would like.
8. Make sure these five things are selected:
- Android SDK
- Android API 34
- Performance (Intel HAXM)
- Performance (Android Emulator hypervisor driver)
- Android Virtual Device
9. Accept the Licence Agreements.
10. On the next page, it will start downloading and installing.
11. Once the installation has finished, click on "More Action".
12. Select SDK Manager.
13. In the tab SDC Platform, make sure "Android API 34" is selected.
14. After that, exit out of Android Studio.
15. For React Native to work, you must open "Windows Control Panel."
16. Click "User Accounts" and "User Accounts" again.
17. Click on Change my environment variables.
18. Click on New... to create new user variable.
19. In Variable Name type "ANDROID_HOME" and Variable value type the location of where Android\SDK.
- You can check the location by opening Android Studio app. Click "More Action" then SDK Manager. At the top of the page, it says "Android SDK Location." This is the location of the SDK installed.
20. After typing the information, press okay. Then scroll down in that same location where you typed ANDROID_HOME and find "Path."
21. Click "Path" then edit. A window will come up.
22. Click browse and find the path where you installed Android and look for "platform-tools." Then click ok and ok again.
23. You successfully installed Android Studio and set up React Native!
  
- If you are having trouble installing or encounter errors, click here for [Troubleshoot](#Troubleshooting "Goto Troubleshoot")

# Project Creation
1. Click the windows button + r
2. Search for "cmd"
3. In the command line, type this "npx react-native@latest init ToDoList" hit enter.
4. Afterwards, it will ask you, "Need to install the following package:" at the bottom of that, it will ask you, "Ok to proceed? (y)." Press y.
5. Wait for a few minutes until it's done creating the project.
6. You have successfully created a project!
- Note: If you want to change a TypeScript file for JavaScript, you can rename the specific file. For example, this code had a file called App.tsx. You would rename this to App.jsx and delete the redlines in the code. And thats it. You have changed the file to a jsx.  
   
# Running the Project
1. Open Android Studio.
2. Click Open.
3. Choose the location where the project was created.
4. At the top of the page there is a tab called "Build." Click on it and click on "Make project".
5. Wait until the app is done building.
6. It should say "build sucessful." After that go to the top of the page under "Run" click "Run This."
7. Once the Emulator runs the app there will be an error "Unable to load script." Go to the command line and type "npm run start" (without the quotations)
8. Then press r.
9. Once its done loading there will be a new page called "Welcome to React Native."
10. You have successfully ran a project!


# Troubleshooting

If you can't get this to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.
