# Moblift for Mac

Capture full-resolution screenshots from an iPhone or a screen recording, then organize them into apps and flows.

## Download

**[Download Moblift 0.16.2 for Mac](https://github.com/crnelious/Moblift-downloads/releases/latest/download/Moblift-macOS.zip)** · approximately 73 MB

Requires an **Apple Silicon Mac (M1 or newer)** running **macOS 14 or later**. Intel Macs and Windows are not supported by this build. Built using the macOS 27 SDK; the app declares macOS 14 as its minimum version. Compatibility has not been checked on every supported macOS version.

[Latest release and downloads](https://github.com/crnelious/Moblift-downloads/releases/latest) · [Quick start](Quick-Start.md)

## Install

1. Download and unzip the ZIP file.
2. Drag **Moblift.app** into **Applications**.
3. Open Moblift.

This is a preview build signed with an Apple Development certificate. It is **not Apple-notarized**, so macOS may prevent it from opening normally. If the warning says the developer cannot be verified or Apple cannot check the app, and you trust this download, try opening it once, then go to **System Settings → Privacy & Security → Open Anyway**. Follow [Apple’s instructions](https://support.apple.com/en-us/102445). If your company manages your Mac and this option is unavailable, ask your IT team for help.

## Start capturing

- **From an iPhone:** connect an unlocked iPhone by USB, tap Trust if prompted, and choose Live Capture. Allow camera access if requested. Create an app and flow, start a session, and press Space to capture.
- **From a recording:** choose Open Recording to import a video and save the frames you need.
- Captures are saved locally on your Mac. The download contains no capture library.

The optional experimental iPhone remote-control feature requires Xcode and additional setup. Ordinary capture and video import do not require that setup. See the [quick start](Quick-Start.md).

## Updates and package contents

This build does not update automatically. Download a newer release here when one is available.

This repository distributes the packaged Mac app and user instructions. The main Mac app source repository remains private. The app includes third-party runtime dependencies and two Moblift helper source files used to build its optional on-device remote-control helper. Third-party license files are included with the bundled runtime.

SHA-256 checksums are attached to each release so downloads can be verified.
