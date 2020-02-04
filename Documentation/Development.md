## **Tech aspects**
- This project was developed on Windows 10 operating systems, using Visual Studio as the IDE.
- Frameworks include: JQuery mobile, Xamarin, RestSharp
- Front-end: Xaml 
- Backend: C#
- API: Cheetah API

## **Cloning**
1. Download Visual Studio Community Version at https://visualstudio.microsoft.com/downloads/
2. Open Visual Studio and click "Clone or check out code"
3. Enter this URL: https://github.com/nabartling/TrustAdministrationMobileAppcode.git (if you need access to clone, please contact Nick at nabartling@bsu.edu).
4.Choose a location for the repo to be cloned (Desktop or C:Drive works best to avoid recieving a Long Path Error upon runtime).
5.After it has cloned, Click Tools -> Android -> Android Device Manager.
6. When prompt with a new window click new. And make sure the following is the same:

## **Folder structure**
**Main Solution** 
-work is done within the Main solution (TrustAdministrationAppCode) 
-priority is android 
-Models: used for storing the objects that are manipulated in the following folders 
-Services: used for creating methods and functions that will be used in the front end
-ThemeResources: used to store different themes, color schemes, etc.
-Views: Where all Front-end work is stored along will the c# page for each page. 

**Android Solution** 
-Resources: where all android specific images and themes are stored.

## **Important files**
**Main Solution**
Models Folder: Token.cs, Taskdata.cs, Constants.cs, ActivtyData.cs, Authenticator.cs, MainActivity.cs 
ThemeResources Folder: LightTheme.xaml
Views Folder: Homepage.xaml/.xaml.cs, TaskPage.xaml/.xaml.cs, ActivityPage.xaml/.xaml.cs, viewActivityPage.cs ViewTaskPage.cs MainPage.cs MenuPage.cs Login.xaml/.xaml.cs, User.cs 
Services Folder: ActivityHandler.cs, Autheniticator.cs LocalJsonEditor.cs TaskHandler.cs
All of the listed files are essential for testing and for the software to run properly.  
In addition, there is a .gitattributes file and a .gitignore file that are for github purposes. 
