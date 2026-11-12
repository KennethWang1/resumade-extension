# ResuMade browser extension

The ResuMade extension reads the job posting you are looking at, tailors your resume to it, and helps fill in the application. It works with your account at [resumade.tech](https://resumade.tech).

It is not in the Chrome Web Store or Edge Add-ons yet. Until it is, install it with one command. The command downloads the latest release from this page and checks it against the published checksum.

## Install

**Windows** (Chrome, Edge or Brave): open PowerShell and run

```powershell
irm https://github.com/KennethWang1/resumade-extension/releases/latest/download/install.ps1 | iex
```

**macOS / Linux** (Chrome, Edge or Brave): open Terminal and run

```bash
curl -fsSL https://github.com/KennethWang1/resumade-extension/releases/latest/download/install.sh | bash
```

The script asks which browser you use, puts the extension in a folder, and opens the browser's extensions page. Browsers don't let programs add extensions from outside their stores, so you finish with three clicks:

1. Turn on **Developer mode**.
2. Press **Load unpacked**.
3. Choose the folder the script printed. On Windows and macOS the path is already on your clipboard.

Then pin ResuMade from the puzzle-piece menu and click it to sign in.

## Update

Run the same command again, then press the reload arrow on the ResuMade card on the extensions page. You stay signed in.

## Manual install

Download `resumade-chrome.zip` (Chrome, Brave) or `resumade-edge.zip` (Edge) from the [latest release](https://github.com/KennethWang1/resumade-extension/releases/latest). Unzip it into a folder you will keep, then follow the three steps above. `SHA256SUMS.txt` lists the checksum of each file.

## Uninstall

Press **Remove** on the ResuMade card on the extensions page, then delete the folder: `%LOCALAPPDATA%\ResuMade` on Windows, `~/.resumade` on macOS and Linux.

## Privacy

See the [ResuMade privacy policy](https://resumade.tech/privacy). Questions: support@resumade.tech.
