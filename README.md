# ovpn-kando
The KandoHost Co dedicated OpenVPN Easy , Free & Fast installation for all Linux Server Os's

# openvpn-install

![Test](https://kndo.ir/git/lint.svg)
![Lint](https://kndo.ir/git/badge.svg)
![visitors](https://visitor-badge.glitch.me/badge?page_id=1saeedir.ovpn-kando)

OpenVPN installer for Debian, Ubuntu, Fedora, CentOS, Oracle Linux and Arch Linux.

This script will let you setup your own secure VPN server in just a few seconds.


### Installation

Run the script and follow the assistant:

`wget https://git.io/JYvoU -O ovpn.sh && bash ovpn.sh`

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.

### Feauters :

When OpenVPN is installed, you can run the script again, and you will get the choice to:

- Add a client
- Remove a client
- Uninstall OpenVPN

In your home directory, you will have `.ovpn` files. These are the client configuration files. Download them from your server and connect using your favorite OpenVPN client.

## Compatibility

The script supports these OS and architectures:

|                 | i386 | amd64 | armhf | arm64 |
| --------------- | ---- | ----- | ----- | ----- |
| Amazon Linux 2  | ❔   | ✅    | ❔    | ❔    |
| Arch Linux      | ❔   | ✅    | ❔    | ✅    |
| CentOS 7        | ✅   | ✅    | ✅    | ✅    |
| CentOS 8        | ❌   | ✅    | ❌    | ✅    |
| Debian >= 9     | ✅   | ✅    | ✅    | ✅    |
| Fedora >= 27    | ❔   | ✅    | ❔    | ❔    |
| Ubuntu 16.04    | ✅   | ✅    | ❌    | ❌    |
| Ubuntu >= 18.04 | ✅   | ✅    | ✅    | ✅    |
| Oracle Linux 8  | ❌   | ✅    | ❌    | ❔    |

To be noted:

- It should work on Debian 8+ and Ubuntu 16.04+. But versions not in the table above are not officially supported.
- The script requires `systemd`.
- The script is regularly tested against `amd64` only.


## Say thanks

You can [![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/1saeed.ir@gmail.com) if you want!

## Credits 

Many thanks to the [contributors] and Nyr's original work.
