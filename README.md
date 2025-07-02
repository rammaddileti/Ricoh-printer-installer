# Ricoh Printer Installation Script

Automated PowerShell script for installing Ricoh M C251FW printers on Windows systems.

## Features

- ✅ Automated driver installation
- ✅ Network printer port configuration  
- ✅ Error handling and logging
- ✅ Prerequisite validation
- ✅ Duplicate installation prevention
- ✅ Network connectivity testing

## Quick Start

1. **Download** the latest release
2. **Extract** to a local directory
3. **Place** your Ricoh driver files in the `drivers/disk1/` folder
4. **Run** as Administrator:
   ```powershell
   .\scripts\Install-RicohPrinter.ps1 -IPAddress "192.168.1.100"
