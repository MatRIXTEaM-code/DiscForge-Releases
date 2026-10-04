# DiscForge

DiscForge is a Windows disc-imaging and preservation toolkit: read, burn, copy, check and repair CDs,
DVDs and Blu-ray discs, plus tools for old archives, game discs and saves. It comes with `dforge`, a
command-line version for Windows and Linux.

This repository holds the downloads only. DiscForge is free to use but not open source; the source
code is private.

![DiscForge](https://github.com/MatRIXTEaM-code/DiscForge-Releases/releases/latest/download/discforge-main-light.png)

![DiscForge in the dark theme](https://github.com/MatRIXTEaM-code/DiscForge-Releases/releases/latest/download/discforge-main-dark.png)

## Download

Get the newest version from **[Releases](../../releases/latest)**:

- `DiscForge-Setup-<version>.exe` — the installer (most people want this)
- `DiscForge-v<version>-win-x64.zip` — the same program as a folder, no installation
- `dforge-v<version>-win-x64.zip` — the command-line tool for Windows
- `dforge-v<version>-linux-x64.tar.gz` — the command-line tool for Linux

### "Windows protected your PC"?

The first time you run the installer, Windows may show a blue box saying **Windows protected your
PC** or **Unknown publisher**. That's because DiscForge isn't signed with a paid certificate yet, not
because anything is wrong with it. To carry on, click **More info**, then **Run anyway**.

If you'd like to check the download first, each release lists the SHA-256 of every file in
`SHA256SUMS.txt`. In PowerShell, `Get-FileHash DiscForge-Setup-<version>.exe` should show the
same value.

Nothing else needs installing: the .NET runtime is included. DiscForge needs administrator rights
because it talks to the disc drive directly.

DiscForge looks for a new version once a day (you can turn this off in Settings) and can update
itself: it downloads the installer from this page, checks it against `SHA256SUMS.txt`, and installs
it. Each release lists the SHA-256 of every download in `SHA256SUMS.txt`.

## Support DiscForge

DiscForge is free, with no adverts and nothing locked away. If it's useful to you, a donation helps
keep it going and pays for a code-signing certificate, so Windows stops warning about the download.
It's entirely optional and doesn't unlock anything.

**[Donate with PayPal](https://paypal.me/DiscForgeUK)**

## Reporting a problem

Open an [issue](../../issues). For a security problem, use **Report a vulnerability** on the
[Security](../../security) tab instead, so it stays private until it's fixed.

DiscForge never removes or gets around copy protection, and requests for that are closed.

Copyright (c) 2026 MaTRIX TeAm. All rights reserved.



