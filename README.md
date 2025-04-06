# All Bounty tools

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

`allbounty` is a Bash script designed to automate the installation of essential penetration testing and bug bounty hunting tools on Kali Linux. It streamlines the setup process, allowing security professionals and enthusiasts to quickly configure their environment. This script excludes mobile hacking tools and SecLists, focusing on core web application and network security assessment utilities.

## Features

* Automated installation of a wide range of Kali Linux penetration testing tools.
* Excludes mobile hacking tools and extensive wordlists (SecLists) for a focused setup.
* Checks for existing installations to prevent unnecessary re-installation.
* Provides clear output during the installation process.
* Handles special cases, such as Nessus Essentials' manual setup requirement.
* Uses robust Bash scripting practices for reliable execution.

## Installation

1.  Clone the repository:

    ```bash
    git clone [https://github.com/muazify/allbounty.git](https://github.com/muazify/allbounty.git)
    cd allbounty
    ```

2.  Make the script executable:

    ```bash
    chmod +x install_pentest_tools.sh
    ```

3.  Run the script with root privileges:

    ```bash
    sudo ./install_pentest_tools.sh
    ```

## Usage

After running the script, the specified penetration testing tools will be installed on your Kali Linux system. Follow any on screen instructions regarding manual setup, especially for Nessus Essentials.

## Tools Installed

The script installs the following tools:

* `nmap`
* `wireshark`
* `metasploit-framework`
* `aircrack-ng`
* `burpsuite`
* `owasp-zap`
* `sqlmap`
* `hydra`
* `john`
* `hashcat`
* `nikto`
* `dirb`
* `wpscan`
* `nessus-essentials`
* `openvas`
* `maltego`
* `theharvester`
* `recon-ng`
* `sublist3r`
* `amass`
* `masscan`
* `responder`
* `impacket`
* `crackmapexec`
* `evil-winrm`
* `searchsploit`
* `armitage`
* `beef-xss`
* `set`
* `fern-wifi-cracker`
* `pixiewps`
* `reaver`
* `xplico`
* `autopsy`
* `volatility`
* `binwalk`
* `foremost`
* `chkrootkit`
* `rkhunter`
* `nuclei`
* `ffuf`
* `dirsearch`
* `feroxbuster`
* `httpx`
* `waybackurls`
* `meg`
* `hakrawler`
* `sn1per`
* `rengine`
* `autorecon`
* `osmedeus`
* `keyhacks`
* `cyberchef`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.
