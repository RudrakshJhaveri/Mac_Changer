# Mac_Changer
Mac Changer is a command-line tool designed to modify the Media Access Control (MAC) address of network interfaces. It provides a simple and convenient way to enhance privacy, security, and network troubleshooting.

## Feature

- Easily change the MAC address of any network interface.
- Supports random MAC address generation for increased privacy.
- Simple syntax and intuitive command-line interface.
- Built-in error handling and validation to prevent accidental misuse.

## Getting Started

Make sure you have Python 3.6+ installed, then run the following command:

Step 1: Clone the Repository
```
git clone https://github.com/RudrakshJhaveri/Mac_Changer.git
```
Step 2: Navigate to the Project Directory
```
cd Mac_Changer
```
Step 3: Check Interface Name
To change the MAC address of a specific network interface, you first need to know its name. Open a terminal and run the following command to display the network interfaces and their names:
```
ifconfig
```
Step 4: Run the Python Program
```
python3 mac_changer.py -i <interface_name> -m <enter_new_Mac_address>
```
Replace your_interface_name with the actual name of the network interface you obtained from the ifconfig command, and new_mac_address with the MAC address you want to set.

