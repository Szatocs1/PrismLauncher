# PrismLauncher Setup Guide for Minecraft Server (1.21.1)

This guide helps you set up [PrismLauncher](https://prismlauncher.org/) on Windows to play on a cracked Minecraft server with Forge mods (version 1.21.1). It includes creating an offline account.

## Prerequisites
- Windows OS
- Web browser
- [Accounts JSON file](https://github.com/Szatocs1/PrismLauncher/blob/main/accounts.json) (download later)

## Step 1: Download and Install PrismLauncher
1. Open [https://prismlauncher.org/download/windows/](https://prismlauncher.org/download/windows/) in your browser.
2. Download the **Windows Installer (.exe)**.
3. Run the .exe file.
4. During installation, set the install directory to your **Desktop** (second tab/screen).
5. Allow through **Account Control** (click Yes/Igen).
6. Complete installation. The launcher interface will open.
7. Set your preferred language and appearance.
8. Skip Microsoft account login.

## Step 2: Set Up Offline Account
1. In PrismLauncher, click the **Steve head** (top-right) → **Manage accounts**.
2. Press **Win + R**, type `%appdata%`, press Enter.
3. Navigate to `PrismLauncher` folder.
4. Download [accounts.json](https://github.com/Szatocs1/PrismLauncher/blob/main/accounts.json):
   - Go to https://github.com/Szatocs1/PrismLauncher
   - Click `accounts.json`
   - Click **...** (top-right of file view) → **Download**
5. Drag the downloaded `accounts.json` into the `PrismLauncher` folder (overwrite if prompted).
6. Back in launcher: Close **Accounts** tab.
7. In the account selection popup, click **OK**.
8. Ignore any \"This account does not own Minecraft\" warning → **Cancel**.
9. Steve head → **Manage accounts** again.
10. Click **Add Offline**:
    - Name your account → **OK**.
    - Close launcher.
11. Verify: In `%appdata%\PrismLauncher`, check for `metacache`, `prismLauncher`, `prismLauncher_update` folders. If missing, notify @Szatocs1.
12. Reopen launcher → Steve head → **Manage accounts**.
13. **Add Offline** → Set name → **OK**.
14. Select your profile → **Set Default**.

## Step 3: Create Minecraft Instance
1. Main screen → **Add Instance**.
2. Search/filter for **1.21.1**, select **Forge** as Mod Loader.
3. Click **OK**. Instance appears.
4. Click instance → **Launch** (right side).

## Step 4: Connect to Server
Contact @Szatocs1 for the private server address (not public for security).

## Troubleshooting
- **No metacache folders after Step 2.11**: Redownload accounts.json or check paths.
- **Account not detected**: Restart launcher after JSON placement.
- **Launch fails**: Ensure Forge 1.21.1 selected; check Java (bundled usually).

## Notes
- This creates a **cracked/offline account** for server play.
- Server uses Forge mods—do not change version without checking compatibility.
- For issues/contributions: Open GitHub issues or contact maintainer.

Success! You've set up PrismLauncher for the server. 🎮
