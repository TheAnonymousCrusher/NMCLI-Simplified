# NetworkManager Command Line Interface (nmcli) Simplified
### (Created by TheAnonymousCrusher on Github)

The following article provides a simple documentation for the
nmcli aliases used to simplify the process of managing network
connections in a system.

# Basic Use
## 1. Connect to a Network

The nmcon alias is used to connect to a WiFi network.The
command requires the name of the WiFi network and the password
as arguments. The syntax is as follows:

```zsh
nmcon 'WIFI_NAME' password 'PASSWORD'
```

For example, to connect to a WiFi network named 'Office_Wifi'
with the password 'password1234', you would use:

```zsh
nmcon 'Office_Wifi' password 'password1234'
```

## 2. Disconnect from a Network

The nmdis alias is used to disconnect from a WiFi network. The
command requires the name of the WiFi network as an argument.
The syntax is as follows:

```zsh
nmdis 'WIFI_NAME'
```

For example, to disconnect from a WiFi network named
'Office_Wifi', you would use:

```zsh
nmdis 'Office_Wifi'
```

## 3. Show Network Status

The nmstat alias is used to display the status of all the
network devices. The command does not require any arguments.
The syntax is as follows:

```zsh
nmstat
```

## 4. Show Network List

The nmlist alias is used to display a list of all the network
connections that have been established. The command does not
require any arguments. The syntax is as follows:

```zsh
nmlist
```

Please note that these aliases are simplified versions of
nmcli commands and are intended to make the process of managing
network connections easier and more intuitive for users.

# Installation

### Step 1: Clone this Respository
Run the following command to *git clone* this project:
```git clone https://github.com/TheAnonymousCrusher/NMCLI-Simplified.git```


### Step 2: Execute the Installion Script 
Run the following command to go to the directory where the project will cloned to:
```cd NMCLI-Simplified```

After that, make the .sh file executable:
```chmod setup.sh```

Now, actually run the script:
```./setup.sh```
