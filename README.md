## Sidra

Attacks for WPA and WEP, automated hash cracking, bluetooth hacking and etc.

- I recommend you to use alfa adapter: **Alfa AWUS036ACM**, which works really great with both, 2.4 and 5 Ghz

Tested and supported in **Kali Linux**, **Parrot OS**, **Arch Linux** and **Ubuntu**


If you're having any issues, contact me or create an issue!

## ⭕ SUPPORTED ATTACKS:

- Deauthentication Attack
- Authentication Attack
- Beacon Flood Attack
- PKMID Attack
- EvilTwin Attack 
- Passive/Stealthy Attack
- Pixie Dust Attack
- Null Pin Attack
- Chopchop Attack
- Replay Attack
- Michael Exploitation Attack
- Caffe-Latte Attack
- Jamming, Reading and Writing bluetooth connections
- GPS Spoofing with HackRF 

## ⭕ FEATURES:

:ballot_box_with_check: Log generator

:ballot_box_with_check: WPA/WPA2, WPS and WEP Attacks

:ballot_box_with_check: Auto handshake cracking

:ballot_box_with_check: Multiple templates for EvilTwin attack

:ballot_box_with_check: Check monitor mode and it status

:ballot_box_with_check: 2Ghz and 5Ghz attacks

:ballot_box_with_check: Custom wordlist selector

:ballot_box_with_check: Auto detect requirements

:ballot_box_with_check: Bluetooth support (Jamming, Reading, Writing)

## ⭕ USAGE:
> Common usage of the framework

```sh
wef -i wlan0 # Your interface name might be different
```
or
```sh
wef --interface wlan0
```

Once the application is running, type `help` to view more functions and useful info.

If you don't want to scan APs with every attack you can do something like this:

```bash
set name my-wifi # To especify the name to attack
set time 60 # To define the total duration of the attacks that ask for the time
set packets 15 # To define the amount of packets that some attacks will send
```

## ⭕ REQUIREMENTS:
> Don't install them manually, Sidra will take care of have them 

    aircrack-ng
    reaver
    mdk4
    macchanger
    hashcat
    xterm
    hcxtools
    pixiewps
    python3
    btlejack
    crackle
    php
    hostadp
    dnsmasq

> Extra

**If you are using bspwm, you can add this line to your bspwmrc for launching the *xterm* windows always beeing in floating mode** (for a prettier design)

    bspc rule -a XTerm state=floating
    
**If you consider this project has been useful, I would really appreciate supporting me by giving this repo a star or buying me a coffee.**

Copyright © 2022, *MahmoodDzay*
