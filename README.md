#  Nyxthecoder's PowerShell Profile

Welcome to my custom PowerShell profile. This is a collection of functions, aliases, and scripts designed to turn the Windows command line into a beautiful, fast, and friendly development environment.

It focuses on aesthetics (`oh-my-posh`, `Terminal-Icons`), rapid system maintenance (`winget`, `scoop`, `CTT`), and mental health (`affirm`). 

> **Note:** This profile is optimized for Windows 11 (with Komorebi support), but works on any Windows 10+ system with PowerShell 7+ installed.

---

##  Prerequisites & Modules

To make this profile work exactly as intended, you will need to install the following tools and PowerShell modules. 

### 1. Essential Terminal Tools (Install via Winget, Scoop, or direct download)
- **[Fastfetch](https://github.com/fastfetch-cli/fastfetch)** (Provides the beautiful system info on launch)
- **[Oh My Posh](https://ohmyposh.dev/)** (The engine for the stylish terminal prompt)
- **[lsd](https://github.com/lsd-rs/lsd)** (An `ls` replacement with icons and colors)
- **[dust](https://github.com/bootandy/dust)** (A more intuitive `du` alternative for disk usage)

### 2. Required PowerShell Modules
You can install these by opening **PowerShell (Admin)** and running the `Install-Module` command for each:

| Module | Purpose | Install Command |
| :--- | :--- | :--- |
| **[PSReadLine](https://github.com/PowerShell/PSReadLine)** | Enhanced terminal history, syntax highlighting, and predictive autocomplete. | `Install-Module PSReadLine -Force` |
| **[Terminal-Icons](https://github.com/devblackops/Terminal-Icons)** | Adds colorful folder and file icons to your directory listings. | `Install-Module Terminal-Icons -Force` |
| **[PSScriptAnalyzer](https://github.com/PowerShell/PSScriptAnalyzer)** | Linting tool to help check your profile for syntax errors. | `Install-Module PSScriptAnalyzer -Force` |
| **[BurntToast](https://github.com/Windos/BurntToast)** | Allows the terminal to pop up modern Windows 11 notifications. | `Install-Module BurntToast -Force` |
| **[posh-git](https://github.com/dahlbyk/posh-git)** | Integrates Git status information into the prompt. | `Install-Module posh-git -Force` |
| **[PSFzf](https://github.com/kelleyma49/PSFzf)** | Integrates the `fzf` fuzzy-finder into PowerShell. | `Install-Module PSFzf -Force` |
| **[Microsoft.WinGet.Client](https://github.com/microsoft/winget-cli)** | Official module for interacting with the Winget package manager. | `Install-Module Microsoft.WinGet.Client -Force` |
| **[Microsoft.WinGet.CommandNotFound](https://github.com/microsoft/winget-cli)** | Helps you find missing commands via Winget. | `Install-Module Microsoft.WinGet.CommandNotFound -Force` |

---

##  Installation Guide

1. **Clone this repository** or download the `Microsoft.PowerShell_profile.ps1` file.
2. Open your PowerShell profile location by typing `vim-profile` (or `notepad $PROFILE`).
3. **Copy the contents** of the script into your profile file and save.
4. **Restart your terminal** (or type `reload-profile`).
5. Type `lf` to view the list of custom functions now available to you!

---

##  Built-in Commands Cheat Sheet

- `syu` - Update all Winget and Scoop packages at once.
- `pw` - Generate a secure, random password and copy it to your clipboard.
- `get-ip` - Display your current public IP address.
- `wttr` - Check the weather forecast in your area.
- `df` - Check your disk usage in a human-readable format.
- `affirm` - Receive a comforting and encouraging message.
- `net-reset` - Reset your entire Windows network stack.
- `CTT` - Run the Chris Titus Tech Windows Utility.
- `lf` - Display this current menu of functions.

---

## License

This project is licensed under the **MIT License**. 
You are free to use, modify, and distribute it, provided you retain the original copyright notice.

---

## Credits & Support

Created with love and chaos by **Nyxthecoder** (Lumi, the Local Tech Cryptic). 
If you enjoy this profile, give the repo a Star on GitHub! 

*(Note: If you're missing one of the required modules, just run the `Install-Module` command for it, and you're good to go!)*
