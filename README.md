Outline VPN Auto Installer Script
===============================

This script automates the installation of Outline VPN Server on your system. It streamlines the process by configuring the firewall, updating the system, installing Docker, and installing the Outline Server.

Requirements
------------

- This script is intended for use on Debian-based systems.
- You should run the script with root privileges or as a user with sudo access.

Usage
-----

1. Download the script: `wget https://raw.githubusercontent.com/AmirOVH/outline-install/main/outline-install.sh`
2. Make the script executable: `chmod +x outline-install.sh`
3. Run the script: `./outline-install.sh`
4. Follow the prompts to configure the firewall and proceed with the installation.

Script Features
---------------

- Firewall Management: The script allows you to choose whether to remove the firewall from the system. It supports both UFW and iptables configurations.
- System Update: It updates the system packages, including upgrading and dist-upgrading.
- Docker Installation: Docker is installed to provide a containerized environment for running the Outline Server.
- Outline Server Installation: The script downloads and executes the Outline Server installation script.

Note: If the installation fails, the script will display an error message indicating that the Outline VPN installation has failed.

Customization
-------------

You can modify the script to fit your specific needs. For example, you can change the firewall ports, add additional system updates, or customize the Docker installation process.

Contributing
------------

Contributions to improve and enhance this script are welcome. Feel free to fork the repository, make your changes, and submit a pull request.

License
-------

This script is released under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute it as per the terms of the license.

Disclaimer
----------

Please use this script responsibly and ensure that you have appropriate permissions to modify your system. The author and contributors of this script are not responsible for any misuse, damages, or consequences that may arise from using this script.
