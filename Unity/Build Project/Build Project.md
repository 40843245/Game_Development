# Build a Unity project in Unity
## Objectvie

In this article, I will teach you:

How to build an Unity project as packages in Unity.

## Prequisite

Install and Update them to latest version:

    corresponding packages and modules of the platform for building.
    
 ### Required modules
 #### Android
      
      Android SDK , 
      Android JDK ,
      Android NDK
      etc
 
 You can manually to install the required module, but you can adopt a simpler way -- install them with Unity Editor and NO NOTHING.
 
 For the list of corresponding packages and modules, see the references in Additional Reference section.    

## Step
The main steps:
Step 1:
In Unity project, select File -> Build Settings.
Step 2:
Add the scene for build (if NOT added).

Step 3:
Check the setting in Edit -> Project Settings-> Player-> <Platform>

Step 4:
Go back to File -> Build Settings.
Select platform for build. 
(If you don't want to build with your current used platform, you must switch platform by clicking "Switch Platform" button.)

Step 5:
Check the settings for build.

Step 6:
Click "Build" or "Build And Run" button.

That's done. You just have to wait a while.

## Figure
Here, these figures illustrates the steps of building Unity Projects.

For step 1:
  
https://github.com/40843245/Game_Development/blob/main/Unity/Build%20Project/Screenshot/buildingProjects_settings_3.png
  
 For step 2 to 6:
  
 https://github.com/40843245/Game_Development/blob/main/Unity/Build%20Project/Screenshot/buildingProjects_settings_1.png
  
 https://github.com/40843245/Game_Development/blob/main/Unity/Build%20Project/Screenshot/buildingProjects_settings_1.png

## Additional References
### Basic concept of Build Project of all platform
Unity Manual Docs:
  
https://docs.unity3d.com/Manual/BuildSettings.html

### Setup for Build on Android 
https://docs.unity3d.com/Manual/android-build-settings.html

### Setup for Build on UWP (Universal Window Platform)
https://docs.unity3d.com/Manual/windowsstore-buildsettings.html
    
### Setup for Build on Other Platform
    
Hyperlinks on the website.
    
https://docs.unity3d.com/Manual/BuildSettings.html
