# NetworkManager Command Line Interface (nmcli) Simplified
### (Created by TheAnonymousCrusher on Github)

The following article provides a simple documentation for the
nmcli aliases used to simplify the process of managing network
connections in a Linux system. 
<br><br>
It also highlights that ```nmcli``` works well with window managers like ```sway``` or ```dwm```, which typically have no UI to connect to networks. This makes ```nmcli``` an essential tool for these environments, despite the inefficiency of its syntax. This project aims to address this issue by improving the syntax and overall user experience for regular nmcli users.

# Basic Use
## 1. Connect to a Network

The nmcon alias is used to connect to a WiFi network.The
command requires the name of the WiFi network and the password
as arguments. The syntax is as follows:

```nmcon 'WIFI_NAME' password 'PASSWORD'```

For example, to connect to a WiFi network named 'Office_Wifi'
with the password 'password1234', you would use:

```nmcon 'Office_Wifi' password 'password1234'```

## 2. Disconnect from a Network

The nmdis alias is used to disconnect from a WiFi network. The
command requires the name of the WiFi network as an argument.
The syntax is as follows:

```nmdis 'WIFI_NAME'```

For example, to disconnect from a WiFi network named
'Office_Wifi', you would use:

```nmdis 'Office_Wifi'```

## 3. Show Network Status

The nmstat alias is used to display the status of all the
network devices. The command does not require any arguments.
The syntax is as follows:

```nmstat```

## 4. Show Network List

The nmlist alias is used to display a list of all the network
connections that have been established. The command does not
require any arguments. The syntax is as follows:

```nmlist```

## Conclusion

Please note that these aliases are simplified versions of
nmcli commands and are intended to make the process of managing
network connections easier and more intuitive for users.

# Installation

# Installation

This section provides two methods for installing and setting up the Neovim configurations from this repository: a full installation via a single command, and a step-by-step installation process.

## Installation Prerequisites

Please note that these instructions assume you use a Unix-like operating system and a basic understanding of command-line operations. If you encounter any issues during the installation process, please refer to the documentation for further guidance.

Before proceeding with the installation, ensure that you have Git installed on your system. Git is a version control system that is essential for cloning and managing this repository.

If you do not have Git installed, you can do so using the package manager of your Linux distribution.

#### Arch Linux

For Arch Linux, you can install Git using the pacman package manager with the following command:

```
sudo pacman -S git
```

#### Debian/Mint/Ubuntu

For Debian, Mint, or Ubuntu, you can install Git using the apt package manager with the following command:

```
sudo apt install git
```

#### OpenSuse

For OpenSuse, you can install Git using the zypper package manager with the following command:

```
sudo zypper install git
```

#### Fedora

For Fedora, you can install Git using the dnf package manager with the following command:

```
sudo dnf install git
```

#### CentOS/RHEL

For CentOS or RHEL, you can install Git using the yum package manager with the following command:

```
sudo yum install git
```

#### Alpine Linux

For Alpine Linux, you can install Git using the apk package manager with the following command:

```
sudo apk add git
```

After installing Git, you can verify the installation by checking the Git version with the following command:

```
git --version
```

This command should return the installed version of Git. If Git is installed correctly, you can proceed with the installation of the Neovim configurations as described in the previous sections.

## Full Installation in a Single Command
To fully set up and install NMCLI-Simplified, execute the following command:

```sh
git clone https://github.com/TheAnonymousCrusher/NMCLI-Simplified.git
cd NMCLI-Simplified
chmod u+x setup.sh
./setup.sh
```
## Step-by-Step Installation

If you prefer to go through the installation process step-by-step, please follow the instructions below:

### Step 1: Cloning the Repository
Execute the following command to clone this project from the Github repository:<br>
```git clone https://github.com/TheAnonymousCrusher/NMCLI-Simplified.git```


### Step 2: Changing to the Project Directory
Next, navigate to the directory into which the project has been cloned. You can do this by running the following command:<br>
```cd NMCLI-Simplified```


### Step 3: Modifying the Script Permissions
After navigating to the correct directory, the next step is to modify the permissions of the .sh file to make it executable. This can be achieved by running the following command:<br>
```chmod u+x setup.sh```

### Step 4: Running the Installation Script
Finally, execute the installation script to begin the installation process. This can be done by running the following command:<br>
```./setup.sh```

# Final Note

This project has been meticulously developed, and it would be greatly appreciated if you could express your support through a  ❤️.<br>
Lastly, I sincerely hope that you have find the experience of using *NMCLI Simplified* convenient.
