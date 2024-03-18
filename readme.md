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

## 🧼 Wipe and Install! 💻
When Booting:

- Command + R = Recovery Mode
- Command + Option + R = Internet Recovery Mode

Once Booted:
- (if necessary) Disk Utility to erase/repartition
- Install macOS
- Hurray! Now you are set to setup your new Mac!

## System Settings

### Dock
 
Make the Dock sane.

- Position on screen: *"Left"*
- Programs to remove from dock
  - Mail
  - Contacts
  - Reminders
  - Maps
  - Photos (if work)
  - Facetime
  - Music (if work)
  - App Store
  - News
  - Apple TV
  - Free Form
  - System Settings

### Mission Control

Make Window Management Sane.

System Settings → Desktop & Dock → Shortcuts...

- Mission Control shortcut set to *"Control + Secondary Mouse Button"*
- Application windows shortcut set to *"Option + Secondary Mouse Button"*
- Show Desktop shortcut set to *"Command + Secondary Mouse Button*

System Settings → Desktop & Dock → Hot Corners...

- Disable all hot corners

### Mouse

- System Settings → Mouse → Uncheck *"Natural Scrolling"*

### Keyboard Setup for Microsoft Sculpt:
Make my windows keyboard function properly.

- System Settings → search for "Modifier Keys"
  - Switch Option key (slated arrow outline) to Command
  - Switch Command key to Option key

### Software Update
- Check *"Automatically keep my mac up to date" *

### Time Machine
Setup Time Machine if appropriate.

### Trackpad
- System Settings → Trackpad → More Gestures → "App Exposé" → Select "Swipe Down with three fingers"

## Clean up Menu bar
Get rid of clutter

- Command + Drag to remove icons
	- Siri
	- Spotlight

- System Settings → Keyboard → Input Sources → Uncheck *"Show input menu in menu bar"*

## Clean up Notification Center
- Right-click *"Weather"*
	- Size → *"Medium"*
	- Edit Weather → Set location to *"My Location"*
- Add Photos Widget
- Remove everything else

## Application Settings

### Finder
Streamline the finder.

- Finder → Settings → General → New Finder Windows Show → *"Documents"*
- Finder → Settings → Sidebar
	- Uncheck
		- *"Airdrop"*
		- *"Applications"*
		- *"Recents"*
		- *"iCloud Drive"*
		- *"Shared"*
		- *"Recent Tags"*
	- Check
		- Home Folder
- View → *"Show Path Bar"*
- View → *"Show Status Bar"*

### Music
Making Music Sane

- Settings → General →
	- Library → Check *"Automatic Downloads"*
	- Show → Uncheck *"Apple Music"*
	- Notifications → Uncheck *"When Song Changes"*
- Settings → Advanced →
	- Check *"Add songs to Library when adding to playlists"*
	- Check *"Automatically Update Artwork for Imported Songs"*

### Safari
- Settings → General →
	- Safari opens with: *"All windows from last session"*
	- Homepage: https://duckduckgo.com
- Settings → Search → Search engine → *"DuckDuckGo"*
- Settings → Advanced → Check *"Show features for web developers"*
 
## Workflow programs
Things I need for using the system:

### Ad Block by Magic Lasso
Ad-blocking for Safari. [Get it in the App Store](https://apps.apple.com/us/app/ad-block-by-magic-lasso/id1198047227?mt=12)

### Moom
For Window layout. [Get it in the App Store](https://apps.apple.com/us/app/moom/id419330170?mt=12)

- Grant it Accessible access (should be prompted)
- Preferences → Check *"Launch automatically on login"*
- Preferences → Run as *"faceless"* application

### Yoink
A Click and Drag shelf. [Get it in the App Store](https://apps.apple.com/us/app/yoink-improved-drag-and-drop/id457622435?mt=12)

- Preferences → General → 
	- Check *"Launch Yoink at login"*
	- Uncheck *"Show menu bar icon"*
	- Uncheck *"Occasional reminder to review Yoink"*
- Preferences → Advanced → 
	- Check *"JPG"* data and all the "dragged-out" file tions

## Programs

Things I need to get work done:

### Google Drive

- [Download it here](https://www.google.com/drive/download/thankyou/)
- Select *"Mirroring"* Mode

If Work:

- Update Finder to default to Google Docs
  - Finder → Perferences → General → New Finder windows show → Other → Select Google Drive folder.

### Google Chrome (If Work)

- Bookmarks → Show Bookmarks bar
- Settings → Show Home Button → New Tab
- Settings → On Startup → Continue where you left off
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

Terminal → Preferences → General

 - On startup, open: New window with profile → "Homebrew"

Terminal → Preferences → Profiles

 - Set "Homebrew" as default.
 - In Homebrew, set font to be "SF Mono" and 14pt.


### Other Programs
- [MacDown](https://macdown.uranusjr.com/)
- [Textmate](https://macromates.com/download)
- Slack (AppStore)
- Skitch (Appstore)
- Trello (AppStore)
 
