# Mac_Changer
Mac Changer is a command-line tool designed to modify the Media Access Control (MAC) address of network interfaces. It provides a simple and convenient way to enhance privacy, security, and network troubleshooting.

## Feature

- Easily change the MAC address of any network interface.
- Supports random MAC address generation for increased privacy.
- Simple syntax and intuitive command-line interface.
- Built-in error handling and validation to prevent accidental misuse.

## Getting Started (This Python program work only in Linux Machine.)

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
![Image](https://github.com/RudrakshJhaveri/Mac_Changer/assets/140316405/e6f12068-7271-4c36-b418-c0ee21a4a3b1)

Step 4: Run the Python Program
Replace your <interface_name> with the actual name of the network interface you obtained from the ifconfig command, and <new_Mac_address> with the MAC address you want to set.
```
sudo python3 Mac_Changer.py -i <interface_name> -m <new_Mac_address>
```

Step 5: Run the Project with --help

To get more information about how to use the project, run it with the --help options:
```
sudo python3 Mac_Changer.py --help
```
![image](https://github.com/RudrakshJhaveri/Mac_Changer/assets/140316405/7dec3fda-7339-4faf-a6e8-0a13d3fed97f)
