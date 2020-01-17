## **Server**
This Application is ran off of Accutech's Cheetah API for the Login.
The tasks and activies and stored locally but will also be obtained from the API in future Iterations. 

## **File placement**
Everything that is default should be kept in there current state. Most of the files
seen are pre-made based on xamarin. The current UI code is placed within the views folder than is under the  "TrustAdministrationProject' Solution file. Each .xaml file has a .xaml.cs that allows functionality of the UI. the models folder is where we class the UI and have "GET" and "Set" presets.The .png files that are used for the icons in the action bar are located under TrustAdministrationProject.Android -> Resources -> Drawable. Lastly, the "ThemeResources" folder holds the current theme of the applications I.E. color scheme, font color, navigation bar color, etc. 

## **Troubleshooting**
currently, the application is ran on an android emulator.
Typically re-building the projct will resolve any issues.
any errors will be logged within the console of visual studio . 
The most Vulnerable pieces are the login that gives calls to the API and the creating task and activity pages. 
There can be some instances where the login is not accepted or the task does not save. a simple solution would be to repeat the process of re-entering the credentials or creating another task.
To start the application, you simply can Press CTRL and F5 or manually start the project by pressing the green play icon in the top menu bar of visual studio 
to stop the application, you simply close the emulator or press the red stop icon located adjacent to the play icon. 
