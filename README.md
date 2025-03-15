# Vista Guard <img align="left" width="120" height="120" src="UWPAssets/150x150.png">

<br>

## What is Vista Guard?
Vista Guard Guard is a Windows Application for protecting your eyes. It will help you (also can force you!) to break if you are working with your PC for a long time using configurable times.


📦 Method 1: Use the graphical setup (recommended):


1. Run the setup and install EyesGuard.

Install Visual studio Community  2022 https://visualstudio.microsoft.com/vs/preview/ 
 -then clone the repo 
   Use this -- cmd git clone https://github.com/reenakh/vg-IU.git
 -Once repo is succesfully cloned click VistaGuard.sln open with VisualStudio 2022
 -Select EyeGuard as Start up project 
 -once application is build succesfully 
***Then tray you will red clour icon , once you click on that application open ***



#### Control Panel
![Vista Guard](Screenshots/Store/main.JPG)

#### Notify Icon
![Vista Guard NotifyIcon](Screenshots/Store/ContextMenu.png)

## What features does it have?

| Feature                  | Implementation State 
|--------------------------|----------------------
| Short Break              | ✔ Implemented       
| Long Break               | ✔ Implemented        
| Timing Customization     | ✔ Implemented        
| Stas                     | ✔ Implemented        
| Pause or Stop protection | ✔ Implemented       
| Windows Tray Integration | ✔ Implemented        
| Auto Start               | ✔ Implemented        
| Customize messages       | ✔ Implemented        
| Multi-language           | ✔ Implemented        


## 📐 Solution Structure

| Project Name   | Language | Description                                  |
|----------------|----------|----------------------------------------------|
| EyesGuard      | C#       | Main Application (at the time of starting project I didn't know F# to write the app entirely in F#)|
| EyesGuard.Data | F#       | Type Provider and Data Access / Translations |
| StorePackage   |          | Used to publish WPF app into Store           |
