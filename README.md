# KALI linux android Nethunter Version 1 2005



This is a script to install Kali Nethunter (Kali Linux) on your Android Phone with termux without rooting your phone.

STEP 1: Setup Termux
Download and Install Termux from Google Playstore

First setup storage with: termux-setup-storage and allow permission.

```
termux-setup-storage
```

Change repo with: termux-change-repo and select mirrors by Albatross

```
termux-change-repo 
```


Update and Upgrade packages with: pkg update -y && pkg upgrade -y (select yes and proceed with any prompt you get).

```
pkg update -y && pkg upgrade -y 
```


Lastly, install wget with: pkg install wget -y

```
pkg install wget -y
```

STEP 2: Install Kali Nethunter

There are three versions of Kali Linux you can install. Full, Minimal and Nano.

Full: This is the complete version of Kali Linux. Includes all the pre-installed tools.

Minimal: A stripped-down version of Kali Linux. Includes only the essential tools.

Nano: Designed for extremely lightweight installations with minimal storage and resource usage. Comes with only the core system 
components and very few pre-installed tools.

## Kali Nethunter Full

Download Script: wget https://etechbox.com/nethunter/install-nethunter-full

Give Execution Permission: chmod +x install-nethunter-full

Run Script: ./install-nethunter-full

```
wget https://etechbox.com/nethunter/install-nethunter-full
chmod +x install-nethunter-full
./install-nethunter-full
```



## Kali Nethunter Minimal
Download Script: wget https://etechbox.com/nethunter/install-nethunter-min

## Kali Nethunter Nano
Download Script: wget https://etechbox.com/nethunter/install-nethunter-nano
