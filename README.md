# System-Tools-Suite

**COMING SOON**

**System Tools Suite Installer**

**Description**

This script provides an interactive, terminal-based installer for downloading a complete suite of custom-built Arch Linux tools developed by Gainer552. With a simple numeric menu, users can selectively or fully download powerful tools built for cybersecurity, system maintenance, disk scanning, file shredding, installation automation, and more. Designed for speed and simplicity, it eliminates the hassle of locating, cloning, and managing multiple repositories manually.

**Table of Contents**

1. Installation
2. Usage
3. Features
4. Tests
5. Disclaimer

**Installation**

1. Download the script file: `system_tools_suite.sh`
2. Make it executable:
   chmod +x system_tools_suite.sh
3. Run it:
   ./system_tools_suite.sh

**Usage**

To use this program, follow these steps:

1. Run the script from your terminal.
2. When prompted, enter the directory path where you'd like the tools to be downloaded.
3. Select one or more tools from the menu.
4. To finish your session, select option `0`.

**Features**

• MiniCoreNet:
A decentralized, serverless networking toolkit for secure file sharing and communications. No servers, no limits, total freedom.

• Disk Tamper Scanner:
A low-level disk scanner that detects physical or logical signs of tampering. Useful for forensic inspection or integrity verification.

• Arch Protect Suite:
A streamlined toolkit that installs multiple defensive security tools to harden Arch Linux systems quickly and efficiently.

• Arch Medic:
A repair-oriented utility designed to recover and fix broken Arch installations or misconfigurations without requiring full reinstalls.

• Arch Care:
A maintenance automation script that updates, cleans, and manages Arch Linux systems intelligently for long-term performance.

• Arch Installation File (JSON):
A configuration file used to automatically deploy customized Arch Linux installations using `archinstall`.

• Xcrypt:
A lightweight Bash encryption utility for securely encrypting and decrypting files with ease and portability.

• Bash File Shredder:
A zero-dependency file shredder designed to permanently and securely destroy files beyond recovery, with audit-friendly usage.

• All Tools Option:
Allows the user to instantly download all the above tools in a single action for quick setup on any system.

**Tests**

• Manual QA tested on Arch Linux x86_64.
• Tested for correct repository cloning.
• Handles invalid paths and options gracefully.
• Fully interactive and supports multiple tool downloads in one session.

**Disclaimer**

This script is provided "as is" with no warranty, express or implied. The author assumes no responsibility or liability for any damage, data loss, or unintended consequences resulting from its use. Use at your own risk. Ensure you understand the nature of the tools being downloaded and run only in secure and trusted environments.
