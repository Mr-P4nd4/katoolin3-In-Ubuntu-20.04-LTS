# Katoolin3 In Ubuntu 20.04-LTS

Katoolin3 brings all programs available in Kali Linux to Debian and Ubuntu.


### Description

small fix in old code
old code >> https://github.com/s-h-3-l-l/katoolin3#warning-for-ubuntu-users

### Warning for Ubuntu users

Installing programs from repositories for different operating systems is generally considered dangerous!
Some packages might (and probably will) break your system. Be careful when installing the tools and don't blame katoolin3 for any inconveniences.
The optimal solution is to install specific tools from tools.kali.org.
It is not recommended to install all tools.

### Requirements

● apt as a package manager

● Python >= 3.5

● Root privileges

● sh, bash

● python3-apt

### Installation
```
git clone
chmod +x ./katoolin3.sh
sudo./katoolin3.sh
```

### Usage

The program flow of katoolin3 is realized by presenting a list of options that you can choose from. These lists look like that:
```
0) ...  
1) ...  
2) ...
```
### Something doesn't work?

Hit me up on Github.

### Uninstalling

To uninstall katoolin3 execute

```
chmod +x ./uninstall.sh;
sudo ./uninstall.sh;
```

Uninstalling the Kali tools can be done inside katoolin3.
