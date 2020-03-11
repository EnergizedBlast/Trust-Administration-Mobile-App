## **Server**
- This application uses Accutech's Cheetah API for the user login.

- The tasks and activities are stored locally, but will be obtained from the API in future iterations. 

## **File placement**
- Everything that is default should be kept in their current state. 

- The current UI code is placed within the views folder that is under the  "TrustAdministrationProject' solution file. Each .xaml file has a .xaml.cs that controls the functionality of the UI for that respect page. 

- The models folder is where where the classes used by the UI are and have "Get" and "Set" presets. 

- The .png files that are used for the icons in the action bar are located under TrustAdministrationProject.Android -> Resources -> Drawable. The "ThemeResources" folder holds the current theme of the applications I.E. color scheme, font color, navigation bar color, etc. 

- The local JSON files are saved to System.Environment.SpecialFolder.Personal, saved in the android emulator.

- The services folder holds different methods that are called on the front-end

## **Troubleshooting**

- Currently, the application is runnable on an Android emulator.

- To start the application, you simply can Press CTRL and F5 or manually start the project by pressing the green play icon in the top menu bar of Visual Studio with Android SDKs installed.

- To stop the application, you simply close the emulator or press the red stop icon located adjacent to the play icon. 

- Typically re-building the projct or factory reseting the emulator will resolve any issues.

- Any errors will be logged within the console of Visual Studio. 

- The most vulnerable pieces are the login that gives calls to the API and the creating task and activity pages. 

- There can be some instances where the login is not accepted or the task does not save. A simple solution would be to repeat the process of re-entering the credentials or creating another task.

- There have been errors relating to being unable to access a path; it usually is because the path to the project files is too long. To resolve, simple move the project to higher-leveled folders until the error disappears.

## **Producing APK**
1. Open Visual studio

2. Right-click the .Android project: select the ‘Properties’ tab. Be sure that selected drop down is ‘Release’, not ‘Debug’.

3. Define the minimum android version for the application.

4. Click 'Build --> "Clean Solution".

5. Click 'Build' -> 'Rebuild'.

6. Right-click the .Android project: select 'Archive'; this will pull up the Archive Manager view. After a moment, it'll create the package.

7. In the Archive Manage view, click at the bottom 'Distribute'. Select 'Ad Hoc'.

8. Select 'Import' and navigate to 'TAP.keystore' file location, located in the .Android project directory under 'Keystore'. The password for the key is "P@ssword1!".

7. Copy the resulting .apk file to device and install it for testing. 
