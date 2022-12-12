## Linux Unijoy
Linux is an Operating System. An operating system is software that manages all of the hardware resources associated with your Desktop or Laptop.

Unijoy is input system (keyboard manager), setting the standard for typing Bengali Unicode! It's developed by **Ekushey** developer team.

## Motive
It will help any Person, who want to write Bengali Unicode in Linux OS.

## Requirements
- Ubuntu OS
- Internet Connection
- Terminal

## Installation
1. Press `ctrl + alt + t` or search **Terminal**
2. Type & press **Enter**
```
sudo apt install ibus-m17n m17n-db ibus-gtk m17n-contrib
```
3. Enter root password (root user)

**Note:** If you get error for `m17n-contrib`. Example
> package ‘m17n-contrib’ has no installation candidate, 

Then type
```
sudo apt install ibus-m17n m17n-db ibus-gtk 
```
4. Check is **Unijoy** has been installed or not by type
```
sudo dpkg -L m17n-db | grep unijoy
```
5.  If Unijoy is installed, the below message will be shown
```
/usr/share/m17n/bn-unijoy.mim
/usr/share/m17n/icons/bn-unijoy.png
```
6. Now type and **Enter** the following command. It’ll run the `ibus daemon ` to allow the Unijoy layout to appear in Keyboard settings.
```
ibus-daemon -xdr
```

## Setup on Keyboard Layout
1. Search **Settings** or follow `Show Application > Settings`
2. Then click **Region & Language**. For Ubuntu 22.04, **Keyboard**.
3. There you will see `Input & Sources`. 
4. Click the plus `+` button, below **English(US)**.
5. Click `⋮` or **More**. For Ubuntu 22.04, **Bangladesh** && Skip option `6`.
6. Click on **Bangla**
7. Scroll down and select `Bangla (unijoy (m17n))`
8.  Click on right top corner `Add`

## How To Use
1. Now you can see `en` on desktop top right corner. If not `restart` your system.
2. Press `super/windows + space` to change keyboard layout
3. It will show `বা‌` at same position
4. ‌‌‌‌‌Now you can type **Bengali** on **Linux (Ubuntu)**

    * শীঘ্রই তোমার রব তোমাকে এত নিয়ামত দিবেন যে, তুমি খুশি হয়ে যাবে (সূরা আদ দুহা : আয়াত ০৫)
    * এ দুনিয়ার সাথে আমার কি সম্পর্ক? আমার দৃষ্টান্ত এক অশ্বারোহীর ন্যায়। যে গ্রীষ্মের একদিন বৃক্ষের ছায়ায় আশ্রয় নিয়ে ঈষৎ নিদ্রা গেলো, তারপর কিছুক্ষণ বিশ্রাম নিয়ে সেখান থেকে চলে গেলো। (রসূল (সাঃ))
    * কষ্টের উপর ধৈর্যধারণই হলো ঈমান (ইমাম ইবনুল জাওযী রহ.)
    * তোমার সাথে আমার মোহাব্বত থাকবে, যদি তুমি ঈমান চাও। যদি বারুদের সুগন্ধি এবং কুরআন কে চাও (আহমদ ফারুক রহ.)

## Tested Ubuntu OS Version
1. Ubuntu 16.04 LTS (Xenial Xerus)
2. Ubuntu 18.04 LTS (Bionic Beaver)
3. Ubuntu 20.04 LTS (Focal Fossa)



## How To Contribute
I will be open to any contribution. If you have any idea, please let me know. I will be happy to help you.
1. Fork this repository
2. Clone on your local environment with IDE.
3. Makes your changes to code.
4. Commit your changes.
5. Create a new pull request
6. Wait for the pull request to be merged.

**Note:** If you want to do a major changes than first create an Issue.


## License
This project is licensed under [GPL-3.0](https://github.com/mrhrifat/linux-unijoy/blob/master/LICENSE.md).