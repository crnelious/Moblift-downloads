Moblift 0.16.2 is a preview Mac app for capturing and organizing iPhone screens.

## Download and install

Download **Moblift-macOS.zip** under Assets, unzip it, and move **Moblift.app** to **Applications**. Do not choose GitHub’s “Source code” archives; those contain only this download repository’s documentation.

- **Apple Silicon (M1 or newer)**
- **macOS 14 or later** declared by the app; built with the macOS 27 SDK
- Approximately **73 MB**
- Main app version **0.16.2**, build **27**

## First launch

This preview is Apple Development-signed and **not notarized**. If macOS reports that the developer cannot be verified or Apple cannot check the app, and you trust this download, try opening it once, then use **System Settings → Privacy & Security → Open Anyway**. See [Apple’s instructions](https://support.apple.com/en-us/102445). Company-managed Macs may require IT approval.

Ordinary capture and video import do not require Xcode. Optional experimental remote control does require Xcode, iPhone Developer Mode, and an Apple development team; see **Moblift-Quick-Start.md**.

## Included

- Packaged Moblift app with its bundled remote-control runtime
- Quick-start instructions
- SHA-256 checksum for the ZIP

The main Mac app source repository remains private. The runtime includes third-party dependencies and two Moblift helper source files required for optional remote control. No capture library is included.

Automatic updates and Developer ID notarization are not included in this release. Compatibility has not been tested on every macOS version declared by the app.
