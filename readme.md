# Billy's New Clean Install Mac Setup Guide

This is a checklist for me. Your mileage may vary. I usually just upgrade to new OSes in place


## Clean Install on Existing Mac

### Check and Verify Backups

- Using macOS's Time Machine?
	- Go into Time Machine and verify that you can see older files.
	- Run a Time Machine 

### Copy off Important Stuff

#### Ensure temp state is saved to disk

- Check programs like Textmate. Do you have any *untitled.txt* documents that need to be saved?

#### Place to look for Files

- Desktop
- Documents
- Google Drive folder (verify that sync has been turned on and all files are synced to Google Drive)
- Downloads (clean out old, unneeded files like DMG

#### Settings for important programs?

- Export Chrome Bookmarks

### Copy everything off to another drive


## 🎉 Wipe and Install! 🎉

- Command + R = Recovery Mode
- Command + Option + R = Internet Recovery Mode

- Disk Utility to erase/reparition
- Install macOS
- Hurray! Now you are set to update!

## System Preferences

### Dock

Make the Dock sane.

- Position on screen: Left
- Programs to remove from doc
  - Mail
  - Contacts
  - Reminders
  - Maps
  - Photos (if work)
  - Facetime
  - iTunes (if work)

### Mission Control

Make Window Management Sane.

System Preferences -> Mission Control

- Mission Control shortcut set to "Control + Secondary Mouse Button"
- Application windows shortcut set to "Option + Secondary Mouse Button"
- Show Desktop shortcut set to "Command + Secondary Mouse Button

### Mouse

- System Preferences -> Mouse -> Uncheck Natural Scrolling

### Keyboard Setup for Microsoft Sculpt:

Make my windows keyboard function properly.

- System Preferences -> Keyboard -> Modifier Keys
  - Switch Option key (slated arrow outline) to Command
  - Switch Command key to Option key

### Time Machine

Setup Time Machine if appropriate.

- Check "Show Time Machine in Menu"

### Trackpad

- System Preferences -> Trackpad -> More Gestures -> Check "App Exposé"
### Sound

- System Perferences -> Sound -> Output -> Check "Show volumn in menu bar"

### Users & Groups

Get rid of Guest, show password hints

- System Preferences -> Users & Groups
  - Guest User -> Uncheck "Allow Guests to log in to this computer" 
  - Login Options -> Check "Show password hints"

## Clean up menu bar

Get rid of clutter

- System Preferences -> Keyboard -> Input Soorces -> Uncheck "Show input menu in menu bar"

## Finder Settings

Streamline the finder.

- Finder -> Preferences -> New Finder Windows Show -> Documents
- Remove from sidebar
  - Applications
  - Recent Items
  - iCloud Drive
- Hide Tags

- View -> "Show Path Bar"
- View -> "Show Status Bar"

## Workflow programs

Things I need for using the system:

### Yoink

A Click and Drag shelf. Get it in the App Store

- Preferences -> General -> check "Launch Yoink at login"
- Preferences -> General -> uncheck "Show menu bar icon"

### Moom
For Window layout. Get it in the App Store

- Preferences -> check "Launch automatically on login"
- Preferences -> Run as "menu bar" application


## Programs

Things I need to get work done:

### Google Backup and Sync

- [Download it here](https://www.google.com/drive/download/thankyou/)
- Uncheck Syncing for Documents, Desktop, Picture
- Create Google Docs folder
- Update Finder to default to Google Docs
  - Finder -> Perferences -> General -> New Finder windows show -> Other -> Select Google Drive folder.

### Google Chrome

- Bookmarks -> Show Bookmarks bar
- Settings -> Show Home Button -> New Tab
- Settings -> On Startup -> Continue where you left off
- Import old Bookmarks file.
- Extensions:
  - [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) 

### Homebrew

[Grab it here](https://brew.sh/). Then install:

- `brew install gifsicle`
- `brew install ffmpeg`
- `brew install pngquant`

### Last Pass

Get the [universal installer](https://lastpass.com/download/cdn/lpmacosx.zip) so it installs in all browsers.

### Terminal

Terminal -> Preferences -> General

 - On startup, open: New window with profile -> "Homebrew"

Terminal -> Preferences -> Profiles

 - Set "Homebrew" as default.
 - In Homebrew, set font to be "SF Mono" and 14pt.


### Other Programs
- [MacDown](https://macdown.uranusjr.com/)
- [Textmate](https://macromates.com/download)
- Slack (AppStore)
- Skitch (Appstore)
- Trello (AppStore)
 
