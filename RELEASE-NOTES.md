Moblift 0.16.2 is now **Developer ID-signed and notarized by Apple**.

**[Download Moblift for Mac](https://github.com/crnelious/Moblift-downloads/releases/latest/download/Moblift-macOS.zip)**

## Install

1. Download **Moblift-macOS.zip**, unzip it, and move **Moblift.app** to **Applications**.
2. Open Moblift and confirm macOS’s normal first-open prompt if shown.

Requires an **Apple Silicon Mac (M1 or newer)** running **macOS 14 or later**. Intel Macs and Windows are not supported by this build. The app was built using the macOS 27 SDK; compatibility has not been tested on every macOS version declared by the app.

## Changes in this download

- Signed the main app and bundled Mac runtime with Developer ID and secure timestamps.
- Removed development-only debugger access from the app and Node runtime.
- Included Apple’s notarization ticket with the app.
- Updated the bundled runtime version so existing installations can refresh the controller.

The app remains **version 0.16.2, build 27**. This release updates distribution signing and packaging; it adds no new app features. Automatic updates are not included.

Ordinary capture and video import do not require Xcode. Optional experimental iPhone remote control still requires Xcode, iPhone Developer Mode, and an Apple development team. See the attached **Moblift-Quick-Start.md**.

The main app source repository remains private. The download includes its runtime dependencies and the two Moblift helper source files needed for optional remote control. No capture library is included.

Download the ZIP asset for the app. GitHub’s “Source code” archives contain only this download repository’s documentation. A SHA-256 checksum is attached for download verification.
