# Arcodia Launcher - User Guide

Welcome to the Arcodia Launcher! This guide will help you get started with connecting to the shard.

---

## First Time Setup

### Step 1: Select Your Ultima Online Directory

The launcher needs to know where your Ultima Online installation is located. Here's how to set it up:

1. Click the Browse button next to the Ultima Online directory field
2. Navigate to your UO installation folder
   - Common location: `C:\Games\Ultima Online Classic\Electronic Arts\Ultima Online Classic`
3. Select the folder and click OK

The text box will turn green when a valid UO directory is detected (it checks for required files like `art.mul` or `artLegacyMUL.uop`).

---

## Understanding the Buttons

| Button | Description |
|--------|-------------|
| **Check for Updates** | Checks if there are any new or updated files available from the shard server. This runs automatically when you first open the launcher. Shows you what files need to be downloaded. |
| **Update Now** | Only appears when updates are available. Downloads and installs the new/updated files. Creates a backup before updating (so you can restore if needed). |
| **PLAY** | Launches the game client and connects to the shard. Requires: A valid Ultima Online directory selected, and client files to be up to date. |

---

## How Updates Work

**Check for Updates** - The launcher compares your files against the server's manifest

- **New Files** - Shown as `[NEW]` - files that don't exist on your computer
- **Changed Files** - Shown as `[CHANGED]` - files that are different from the server version

When you click **Update Now**:

1. A backup is created (just in case)
2. New files are downloaded
3. Updated files replace the old versions

---

## Troubleshooting

| Issue | Solution |
|-------|----------|
| **"Invalid UO directory"** | The folder you selected doesn't contain the required UO files. Make sure you select the folder containing `art.mul` or `artLegacyMUL.uop`. |
| **"Client not found"** | The game executable wasn't found. Make sure you've run Update Now to download the client files. Check that `client_executable` in the config matches your actual game file. |
| **"File is locked by another process"** | Another program is using a file that needs to be updated. Close any programs that might be using UO files (including the game itself). Click Check for Updates again - the new file will be saved and applied. |
| **Update fails with errors** | Check your internet connection. Try running the launcher as Administrator. Make sure your firewall isn't blocking the connection. |

---

## Notes

- Your settings are saved automatically
- The launcher preserves your character data and settings during updates
- Backups are kept in the backup folder - you can restore from them if needed