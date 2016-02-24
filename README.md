# Oinion
Parody of Food Game on 2008.pumkin.com

## Contributing to this Project

### Download Android SDK
1. Download the Android SDK Zip Package for your platform [here](https://developer.android.com/sdk/index.html#Other).
2. Extract the Zip Package
3. Run SDK Manager.exe
4. Check off everything Android 4.4.2 and above. Leave everything that is already checked checked.
5. Click Install some# Packages
6. When prompted, check off Accept License
7. Click Install
8. Take note of the SDK Path at the top of the window.
9. When it is done, close the SDK Manager.

### Setting Up libGDX Project
1. Run libGDX App Set Up
2. Enter the following information:
```
Name: Oinion
Package: com.sshsgd.oinion
Game Class: Game
Destination: [Path to Game Dev Folder]\Oinin\Project
Android SDK: [Path to your Android SDK]
```
3. Make sure ONLY Desktop and Android are checked in Sub Projects
4. Make sure ONLY Freetype and Controllers are checked in Extensions
5. Check Eclipse in Advanced
6. Click Generate
7. Use Reconmended Build Tools

### Set up Git
Copy the .git link on the right hand side of your fork of the repository. Open GitShell and cd to your project's folder. Type in the following commands:
```
git init
git remote add origin link-to-your-fork
git fetch origin master
git reset --hard FETCH_HEAD
git clean -df
```
From there, you can add the repository to GitHub for desktop and contribute to the repository

### Eclipse Workspace
1. Make an Eclipse Workspace in [Path to Game Dev Folder]\Oinin\workspace (NOT IN PROJECT FOLDER)
2. Click Import
3. Existing Projects into Workspace
4. Browse to [Path to Game Dev Folder]\Oinin\Project
5. Check all projects on the list (android, core, and desktop)
6. Click Import
