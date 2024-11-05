## WifiHack-joy
### Hack WIfi Using Kali-Linux! (Requires Root)

<p align="center"><img src="https://i.ibb.co/K74g0SC/hulu.jpg"></p>

### Installation :

```bash
$ apt update && apt upgrade
$ apt install -y root-repo
$ apt install -y git tsu python wpa-supplicant pixiewps iw
$ git clone https://github.com/Joy43/WifiHack-joy.git
$ cd WifiHack-joy
$ chmod +x joy.py
$ sudo python joy.py --help
```
* Run joy.py with python3
    * On kali linux
        ```bash
        python3 joy.py -i wlan0 -K
        ```

#### Example : `python3 joy.py -i wlan0 -K`

#### Note: 
**First turn off your Wifi.**
- Show avaliable networks and start Pixie Dust attack on a specified network.
- `sudo python joy.py -i wlan0 -K`
- - Start Pixie Dust attack on a specified BSSID:
`sudo python joy.py -i wlan0 -b 00:91:4C:C3:AC:28 -K`
- Launch online WPS bruteforce with the specified first half of the PIN:
- `sudo python joy.py -i wlan0 -b 00:90:4C:C1:AC:21 -B -p 1234`
### Troubleshooting
**"Device or resource busy (-16)" - Turn on Wifi and Then Turn off Wifi.**

<div align="center">

<img height="120" alt="Thanks for visiting me" width="100%" src="https://raw.githubusercontent.com/BrunnerLivio/brunnerlivio/master/images/marquee.svg" />

<div/>