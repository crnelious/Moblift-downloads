# Moblift quick start

Moblift saves screens from an iPhone or an existing recording. An **app** contains
**flows**; a flow contains the screens for a task. For example:
Shopping app → Checkout → Cart, Delivery, Payment, Confirmation.

## Capture

1. Move Moblift into Applications and open it. The quick start appears once; reopen
   it from **Help → Moblift Quick Start**.
2. Choose **New App…** and name the app you're studying. Add a flow such as Sign in.
3. Connect an unlocked iPhone by USB, trust the Mac, and choose **Live Capture →
   Connect → Start Session**. Or choose **Open Recording…** to import a video.
4. **Space** captures the iPhone screen. **⇧⌘R** starts and stops recording.
   Captures save automatically on this Mac.

## Compare

Click **Detach** (⇧⌘D) for a standalone phone with a small floating toolbar.
The camera captures; the record button starts or stops a video. The bezel and
controls never appear in the saved PNGs or recordings. Remote control still works. Select a saved screen on the right;
Moblift shows it in the main canvas for comparison. The selected flow remains the
capture destination, shown in both windows.

Click the **Reattach** arrows at the top right, or close the phone window, to put it back. A running recording
continues through detach and reattach. **Show iPhone** brings the separate window
forward. Double-click anywhere on a saved screenshot row to open its large preview.
The eye button still opens Quick Preview.

## Organize and share

- Drag screens to put them in order or move them into another flow. Use **New Flow
  from Selection** to group selected screens. Drag a flow into another to nest it.
- **⌘Z / ⇧⌘Z** undo and redo edits. History lasts until you quit.
- The **folder button above the screenshots** opens Documents → Moblift → App →
  Flow. Repeated clicks refresh the same folder. Numbered PNGs follow the current
  screen order. Moblift preserves files added or changed outside the app.
- **Export…** makes a separate snapshot at a destination you choose. It includes
  recordings and leaves earlier exports alone.

## Use your Mac keyboard on the phone

Remote control is optional. Start with normal capture and use the phone directly
if you don't need it.

The main toolbar groups device/session status on the left and capture mode, Detach
and Start/End Session on the right. Phone controls sit directly below its preview.

When remote control is ready, click **Type on iPhone** or press **⌘K**. Click a text
field on the phone, then use your physical Mac keyboard. The control changes to
**Typing on iPhone**, and the footer shows the active shortcuts.

| Action | Shortcut |
| --- | --- |
| Capture while browsing | Space |
| Enter or leave phone typing | ⌘K |
| Leave typing mode | Esc |
| Capture, including while typing | ⇧⌘C |
| Start or stop recording | ⇧⌘R |
| Detach or reattach phone | ⇧⌘D |

In typing mode, Space types a space. Keyboard input stays in Moblift and stops when
its window loses focus. Other Mac apps and text fields keep their normal keys.

## First remote-control setup

Open **Settings → Experimental → Set up remote control…** for the in-app guide.

1. Install the current Xcode, open it once, and sign in under Settings → Accounts.
2. Connect the iPhone by USB and trust the Mac. Enable Developer Mode in iPhone
   Settings → Privacy & Security, following Apple's restart prompts. Some versions
   also expose a UI Automation switch under Developer settings.
3. Enable Experimental Features and iPhone Remote Control. In Live Capture, click
   **Control**, select the same phone shown in the preview, and enter your Apple
   development team ID. Connection details you rarely need are under **Advanced
   connection settings**. Allow provisioning only if you want Xcode to register
   this phone for your development team.
4. Connect and keep the phone unlocked. Initial helper installation can take a few
   minutes. Existing confirmed pairings reconnect automatically.

The helper uses the **Mobbin logo**. iOS names the runner **WebDriverAgentRunner**
and can display an automation message while it runs. This is Apple's indication
that developer tools are connected. Moblift does not hide it.

## Build details

Requires Apple Silicon and macOS 14 or later. Built and checked with Xcode 27 and
the macOS 27 SDK. The download contains the app and its bundled controller, never
someone's capture library. This build is signed with Developer ID and notarized by Apple. Automatic updates
are not included.
