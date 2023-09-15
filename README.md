# Forticlient SSL VPN Client Launcher

This script is used to automate the launch of the Forticlient SSL VPN Client using the Expect scripting language. It simplifies the process of connecting to a VPN server by providing the necessary credentials.

## Configuration

Before using the script, you need to configure the following parameters:

- `FORTICLIENT_PATH`: Path to the Forticlient VPN binary. If left empty, the script will attempt to locate it automatically.
- `VPN_HOST`: The VPN server's hostname or IP address.
- `VPN_USER`: Your VPN username.
- `VPN_PASS`: Your VPN password.

## Usage

1. Make sure the script is executable by running the following command:

   chmod +x script

2. Execute the script with the following command:
   sudo bash script_path
