# openvpn-install-for-mikrotik

OpenVPN installer for Debian, Ubuntu, Fedora, CentOS, Arch Linux, Oracle Linux, Rocky Linux and AlmaLinux.

This script is designed to use the MikroTik router and RouterOS as a client.

The original script, unchanged, is in the `openvpn-install.sh` file and was taken from the repository https://github.com/angristan/openvpn-install

## Usage

First, get the script and make it executable:

```bash
wget https://raw.githubusercontent.com/volstr/openvpn-install-routeros/main/openvpn-install-routeros.sh -O openvpn-install-routeros.sh
```

Then run it:
```sh
sudo bash ./openvpn-install-routeros.sh
```

## Major changes in the openvpn-install-routeros.sh file
- `auth SHA512` changed to `auth SHA1`
- Removed `tls-crypt` from certificate


More detailed information on the author's page https://github.com/angristan/openvpn-install
