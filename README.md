# Branch desktop downloads

Download the Branch desktop app for macOS and Windows from [Releases](https://github.com/peyyfi/branch-desktop-downloads/releases/latest).

Visit [Branch](https://branch.peyyfi.io/downloads) to choose your installer. All apps connect to the live workspace at https://workspace.branch.peyyfi.io.

Windows builds include x64, ARM64 and 32-bit (ia32). The 32-bit compatibility runtime is supported until January 2027 and requires Windows 10 or later. Mac builds require macOS 13 or later.

Windows installers are unsigned and Mac apps are not Apple-notarized. Check your organization’s installation policy before installing. Checksums are included with each release.

This repository hosts the download workflow and published installers. Build input is supplied as a private draft-release asset, verified against its recorded checksum, then removed before publication.

Version 0.1.2 adds microphone access for private voice calls and group voice rooms in Team Chat. Install the update over 0.1.1, then allow microphone access when starting or accepting a call. The existing live workspace and LiveKit project are unchanged.

The Apple Silicon DMG can be cross-built on an Intel Mac runner. Its ARM64 executable, code signature, audio-input entitlements and microphone usage description are verified before publication. For 0.1.2, the actual packaged Apple Silicon app also passed microphone deny/allow, camera denial and real two-way LiveKit synthetic-audio tests on an Apple Silicon Mac.
