# Snow Leopard Icons for Glow
Snow Leopard icons for use with the Glow Theming Engine

Method of installation: Drop the icons (not the folders!) in your `/Library/GlowThemes/Snow Leopard` folder.

## Structure: 

### Dock Icons: 
Icons that are only used in the Dock application. These icons must be named as follows: `[CFBundleID][@2x][.png]` 
You can find the CFBundleID by finding the application in finder, right click -> Show Package Contents -> Contents -> open Info.plist and find Bundle identifier or CFBundleIdentifier. 
It should be in the format of com.company.product. Make sure you add @2x after the bundle identifier and before the .png. At the moment, only .png images are supported. 

### System wide icons:
Icons that are used elswhere in the system (/Applications folder for example). They must be named as follows: ApplicationName.icns. Only .icns is supported. 

### Folder Icons: 
Icons for folders. Must be named Folder.icns. For example, to theme the library folder, name the icon Library.icns. Only .icns supported. 


***This list is not complete, please submit new icons and I'll merge them.***
