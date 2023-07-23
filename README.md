# Mac_Changer
Mac Changer is a command-line tool designed to modify the Media Access Control (MAC) address of network interfaces. It provides a simple and convenient way to enhance privacy, security, and network troubleshooting.

# Feature

- Easily change the MAC address of any network interface.
- Supports random MAC address generation for increased privacy.
- Simple syntax and intuitive command-line interface.
- Built-in error handling and validation to prevent accidental misuse.

## Installation

Make sure you have Python 3.6+ installed, then run the following command:

```bash
pip install mac-changer

Usage: mac-changer [options] interface

Options:
  --mac, -m    Specify a custom MAC address to set.
  --random, -r Generate and set a random MAC address.
  --reset, -s  Reset the MAC address to the original value.
  --help, -h   Show this help message and exit.
