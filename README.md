# allbounty

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

A Bash script to automate the installation of essential penetration testing and bug bounty hunting tools on Kali Linux.

## Description

`allbounty` is a convenient Bash script designed to streamline the setup process for ethical hackers and bug bounty hunters. It automates the installation of a curated selection of commonly used tools, saving you time and effort. This script excludes mobile hacking tools and the SecLists package, focusing on core web and network security tools.

## Features

* Automated installation of essential penetration testing tools.
* Excludes mobile hacking tools and SecLists for a focused setup.
* Checks for existing installations to avoid redundant operations.
* Provides clear output and error handling.
* Handles Nessus Essentials setup reminder.

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

Simply run the script after cloning and navigating to the directory. The script will handle the installation process automatically. Follow the on-screen instructions, especially regarding the Nessus Essentials setup.

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues to improve the script.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Release Text Example (for a release on GitHub)

**Release v1.0.0 - Initial Release**

* Initial release of the `allbounty` script.
* Automates the installation of core penetration testing tools on Kali Linux.
* Excludes mobile hacking tools and SecLists.
* Includes checks for existing installations.
* Provides a reminder for Nessus Essentials manual setup.
* Basic error handling implemented.

---

**Short Description for Repository:**

A Bash script to automate the installation of essential penetration testing and bug bounty hunting tools on Kali Linux, excluding mobile hacking tools and SecLists.
