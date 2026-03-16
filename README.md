# AddToAutorun

![](https://github.com/HemulGM/AddToAutorun/blob/master/screen1.png)

## Description

AddToAutorun is a utility tool that allows you to easily add applications to the Windows autorun/startup folder. This tool simplifies the process of managing programs that launch automatically when your system starts.

## Features

- ✅ Simple and user-friendly interface
- ✅ Add applications to autorun with a single click
- ✅ Remove applications from autorun
- ✅ Lightweight and fast
- ✅ No installation required (portable)

## Installation

1. Download the latest release from the [Releases](https://github.com/TheTitanrain/AddToAutorun/releases) page
2. Extract the archive to your desired location
3. Run the executable file
4. No additional dependencies required

## Usage

1. **Add Application to Autorun:**
   - Launch the application
   - Select the executable file you want to add to autorun
   - Click the "Add" button
   - The application will now start automatically on system startup

2. **Remove Application from Autorun:**
   - Open the tool
   - Select the application from the list
   - Click the "Remove" button
   - The application will no longer start on system startup

## Requirements

- Windows 7 or later
- Administrator privileges required to modify autorun entries

## Technical Details

- **Language:** Delphi/Pascal
- **Platform:** Windows

## How It Works

The tool modifies the Windows Registry to add or remove startup entries. Changes are made to:
- `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run` (User-specific autorun)
- `HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Run` (System-wide autorun - requires admin)

## Troubleshooting

**Issue:** Administrator privileges error
- **Solution:** Run the application as Administrator

## Contributing

Contributions are welcome! Please feel free to submit issues and pull requests.

## Support

If you encounter any issues or have suggestions, please open an [Issue](https://github.com/TheTitanrain/AddToAutorun/issues) on GitHub.

---

**Note:** Use this tool responsibly. Modifying autorun entries can affect system performance if you add too many applications.
