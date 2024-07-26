# VisitCleaner - A Modifiable PowerShell System Cleaner

VisitCleaner is a PowerShell script designed to clean various temporary files and optimize SSD performance on Windows PCs. This script helps free up disk space by removing unnecessary files and performing other system maintenance tasks. As Windows already has many of these features built in, this script was designed with accessibility and customization in mind.

## Features

- Cleans temporary files
- Clears browser cache (Chrome and Firefox)
- Cleans thumbnail cache
- Cleans prefetch folder
- Cleans temporary fonts
- Flushes DNS cache
- Cleans system temporary files
- Cleans printer temporary files
- Cleans DirectX Shader Cache
- Empties the Recycle Bin
- Analyzes disk space before and after cleaning
- Shares time spent performing each operation
- Optimizes SSD performance

## Requirements

- Windows 11/10 operating system (8.1 and 7 may work if PowerShell is updated to 5.1.)
- PowerShell
- Administrator privileges

## Usage

1. **Download and Extract**:
   - Download the repository as a .zip file and extract it.

2. **Run the Script**:
   - Ensure you have administrative privileges.
   - Run the `RunVisitCleaner.bat` file as administrator to execute the script.

3. **Optional**:
   - If your system has an HDD instead of an SSD, you can remove or comment out the `Optimize-SSD` function from `VisitCleanerScript.ps1`.

## Disclaimer

- **Disclaimer**: Use this script at your own risk- it is a system maintenance tool that modifies system files and settings. Although designed to be safe to use, you are responsible for any damage or data loss that may occur as a result of using this script.
- **Compatibility**: This script is designed for systems with SSDs. If you have a HDD, remove the `Optimize-SSD` function to avoid potential issues.
- **Permissions**: Ensure you have the necessary permissions and administrative rights to run this script.
- **Backups**: If you are uncertain about how this will affect your system, back up your system or remove functions you do not want to execute.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Feedback and Contact

For feedback or questions, visit [VisitPaul.com](https://VisitPaul.com).
