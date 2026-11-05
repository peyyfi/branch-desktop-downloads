# Branch desktop downloads

Download the Branch desktop app for macOS and Windows from [Releases](https://github.com/peyyfi/branch-desktop-downloads/releases/latest).

Visit [Branch](https://branch.peyyfi.io/downloads) to choose your installer. All apps connect to the live workspace at https://workspace.branch.peyyfi.io.

Windows builds include x64, ARM64 and 32-bit (ia32). The 32-bit compatibility runtime is supported until January 2027 and requires Windows 10 or later. Mac builds require macOS 13 or later.

Windows installers are unsigned and Mac apps are not Apple-notarized. Check your organization’s installation policy before installing. Checksums are included with each release.

This repository hosts the download workflow and published installers. Build input is supplied as a private draft-release asset, verified against its recorded checksum, then removed before publication.
