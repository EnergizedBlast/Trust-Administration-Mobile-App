## **Server**
This application is uses Accutech's Cheetah API for the user login.
The tasks and activities are stored locally, but will be obtained from the API in future iterations. 

## **File placement**
Everything that is default should be kept in there current state. The current UI code is placed within the views folder that is under the  "TrustAdministrationProject' solution file. Each .xaml file has a .xaml.cs that controls the functionality of the UI for that respect page. the models folder is where where the classes used by the UI are and have "Get" and "Set" presets. The .png files that are used for the icons in the action bar are located under TrustAdministrationProject.Android -> Resources -> Drawable. Lastly, the "ThemeResources" folder holds the current theme of the applications I.E. color scheme, font color, navigation bar color, etc. 

## **Troubleshooting**
Currently, the application is runnable on an Android emulator.
Typically re-building the projct will resolve any issues.
Any errors will be logged within the console of Visual Studio. 
The most vulnerable pieces are the login that gives calls to the API and the creating task and activity pages. 
There can be some instances where the login is not accepted or the task does not save. A simple solution would be to repeat the process of re-entering the credentials or creating another task.
There have been errors relating to being unable to access a path; it usually is because the path to the project files is too long. To resolve, simple move the project to higher-leveled folders until the error disappears.
To start the application, you simply can Press CTRL and F5 or manually start the project by pressing the green play icon in the top menu bar of Visual Studio with Android SDKs installed.
To stop the application, you simply close the emulator or press the red stop icon located adjacent to the play icon. 
