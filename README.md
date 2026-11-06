# Guide Reticle Unlock Tool

![Guide Reticle Unlock Tool: the app window next to a Guide monocular showing its reticle and zeroing menu](docs/title.png)

A small app for Windows and Mac by TRIDOS.DESIGN that turns the **reticle and zeroing menu** on or off on a Guide thermal monocular. One licence key unlocks one monocular, permanently. It also saves the monocular's **photos and videos** to your computer over Wi-Fi, free.

**[Download for Windows](https://github.com/trakaismikus/guide-unlock-tool-releases/releases/latest/download/GuideUnlockTool-setup.exe)** · **[Download for Mac](https://github.com/trakaismikus/guide-unlock-tool-releases/releases/latest/download/GuideUnlockTool-mac.dmg)** · [All versions](https://github.com/trakaismikus/guide-unlock-tool-releases/releases) · [Buy a licence key](https://tridos.design/products/guide-reticle-unlock-tool-license)

## What you need

- A Windows PC: Windows 10 (version 1803 or newer) or Windows 11, 64-bit, with Wi-Fi.
- Or a Mac: macOS 13 Ventura or newer, Apple Silicon or Intel, with Wi-Fi.
- About 15 MB of disk space. Nothing else to install.
- A Guide thermal monocular with Wi-Fi, from the ZG40 family (TE211, TE211M, TE411, TE421, TQ630L and their variants). The app checks the model when it connects. A model and firmware pair we have not confirmed yet gets a red warning and can still continue.
- A licence key. Buy one at [tridos.design](https://tridos.design/products/guide-reticle-unlock-tool-license). It arrives by email. Monoculars bought from TRIDOS have a free licence included; the app finds it by itself.

## Install

### Windows

1. Download `GuideUnlockTool-setup.exe` from the link above.
2. Run it. Windows may show a blue **"Windows protected your PC"** box. That is Microsoft SmartScreen, which does not yet know this app. Click **More info**, check that the publisher reads **SIA TRIDOS**, then click **Run anyway**. The installer is signed and timestamped.
3. The app opens. Its version is shown bottom right.

### Mac

1. Download `GuideUnlockTool-mac.dmg` from the link above and open it.
2. Drag **Guide Unlock Tool** onto the **Applications** folder in the same window.
3. Open the app from Applications. The first time, macOS says it **could not verify** the app. Click **Done**.
4. Open **System Settings → Privacy & Security**, scroll down, click **Open Anyway** next to Guide Unlock Tool, then **Open Anyway** again and enter your Mac password if asked. You do this once per install or update. (The app is not notarized by Apple; this is how macOS lets you open it.)
5. When the app asks to **find devices on local networks**, click **Allow**. Without it the app cannot reach the monocular. If you clicked Don't Allow, the app shows a red box: open **System Settings → Privacy & Security → Local Network** and turn on **Guide Unlock Tool**.

## How to use it

The app has three numbered steps, a Media tab and a Restore tab. It never changes your computer's network settings; you join the Wi-Fi networks yourself. The app shows how, for Windows and for Mac.

### 1. Backup

1. On the monocular, turn Wi-Fi on.
2. On the computer, join the Wi-Fi named **TE Mini-…** (or similar). The password is usually `12345678`. On a Mac, use the Wi-Fi menu in the menu bar; the monocular may be under **Other Networks**.
3. The app reads the monocular and saves a backup of its settings. Nothing on the monocular changes.

### 2. Keys

1. Leave the monocular's Wi-Fi and rejoin your normal Wi-Fi, the one with internet.
2. The monocular appears in the list. Press **Add key**, type the key from your email, press **Apply key**.
3. If the monocular has a free licence included, the row says so and no key is needed.

### 3. Reticle

1. Rejoin the monocular's Wi-Fi.
2. Press **Turn reticle on**. Read the two warnings, then press **Apply**.
3. When the app says **Done and checked**, turn the monocular off and on. The reticle and zeroing menu is there.

The same button turns it **off** again later. The key stays valid.

### Media

Saves the monocular's photos and videos to your computer, straight over its Wi-Fi. No cable, no SD card reader, no licence needed.

1. Join the monocular's Wi-Fi and open the **Media** tab. Every photo and video on the monocular is shown, newest first.
2. Click a picture to preview it. Videos play straight from the monocular; nothing is saved until you download.
3. Select files (or **Select all**) and press **Download**. The bar at the bottom shows the progress and the time left. Files go to your Downloads folder; **Change** picks another folder. A file already saved is skipped, never overwritten.

Nothing on the monocular is changed or deleted.

### Restore

Puts the monocular back to the settings it had the first time the app saw it. Connect the monocular on its Wi-Fi and open the tab. If the original backup is on this computer, the screen shows when it was taken and offers **Restore original settings**. If it is not, go online on your normal Wi-Fi for a moment first; the app fetches it.

## Good to know

- **Firmware updates are disabled and the warranty is likely void while the reticle is turned on.** The app says this before every write.
- Do not disconnect the monocular while the app is writing.
- If the app is not sure a write landed, it offers **Check again**, never a blind second write.
- A newer version is announced in the app's footer. When a version is required, the app asks you to update before anything else. On a Mac, **Get the update** opens this page; install the new `.dmg` the same way. macOS then asks the first-open and Local Network questions again.
- **Save diagnostics** (bottom left of every screen) writes an encrypted log file to your Downloads folder. Send it to support if something goes wrong.

## Support

Email **mikus@tridos.design**. Include the monocular's model, serial number, and the diagnostics file if you have one.

© SIA TRIDOS · [TRIDOS.DESIGN](https://tridos.design)
