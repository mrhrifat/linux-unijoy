## Linux Unijoy
Linux is an Operating System. An operating system is software that manages all of the hardware resources associated with your Desktop or Laptop.

Unijoy is input system (keyboard manager), setting the standard for typing Bengali Unicode! It's developed by **Ekushey** developer team.

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
3. Enter root password
4. **Note:** If you get error for `m17n-contrib`. Example
> package ‘m17n-contrib’ has no installation candidate, 

Then type
```
sudo apt install ibus-m17n m17n-db ibus-gtk 
```
5. Check is Unijoy has installed or not by type
```
sudo dpkg -L m17n-db | grep unijoy
```
6.  If Unijoy is installed the below message will be shown
```
/usr/share/m17n/bn-unijoy.mim
/usr/share/m17n/icons/bn-unijoy.png
```
7. Now type and **Enter** the following command. It’ll run the `ibus daemon ` to allow the Unijoy layout to appear in Keyboard settings.
```
ibus-daemon -xdr
```

## Setup on Keyboard Layout
1. Search **Settings** or follow `Show Application > Settings`
2. Then click **Region & Language**.  There you will see `Input & Sources`
3. Click the plus `+` button, below **English(US)**.
4. Click `⋮` or **More** 
5. Click on **Bangla**
6. Scroll down and select `Bangla (unijoy (m17n))`
7.  Click on right top corner `Add`

## How To Use
1. Now you can see `en` on desktop top right corner
2. Press `super/windows + space` to change keyboard layout
3. It will show `বা‌` at same position
4. ‌‌‌‌‌Now you can type **Bengali** on **Linux (Ubuntu)**

    * শীঘ্রই তোমার রব তোমাকে এত নিয়ামত দিবেন যে, তুমি খুশি হয়ে যাবে (সূরা আদ দুহা : আয়াত ০৫)
    * এ দুনিয়ার সাথে আমার কি সম্পর্ক? আমার দৃষ্টান্ত এক অশ্বারোহীর ন্যায়। যে গ্রীষ্মের একদিন বৃক্ষের ছায়ায় আশ্রয় নিয়ে ঈষৎ নিদ্রা গেলো, তারপর কিছুক্ষণ বিশ্রাম নিয়ে সেখান থেকে চলে গেলো। (রাসূল (সাঃ))
    * কষ্টের উপর ধৈর্যধারণই হলো ঈমান (ইমাম ইবনুল জাওযী রাহ.)
    * তোমার সাথে আমার মোহাব্বত থাকবে, যদি তুমি ঈমান চাও। যদি বারুদের সুগন্ধি এবং কুরআন কে চাও (আহমদ ফারুক রাহ.)

## Tested Ubuntu OS Version
1. Ubuntu 16.04 LTS (Xenial Xerus)
1. Ubuntu 18.04 LTS (Bionic Beaver)
2. Ubuntu 20.04 LTS (Focal Fossa)
