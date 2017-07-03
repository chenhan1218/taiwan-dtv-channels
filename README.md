# taiwan-dtv-channels
DVB-T channels list for Digital television in Taiwan.

## Usage
Insert dvt-t usb stick into PC. Download channels.conf and open channels.conf with VLC
```
sudo apt-get install vlc
vlc channels.conf
```

## Re-scan channel
```
sudo apt-get install -y dvb-apps
scan /usr/share/dvb/dvb-t/tw-All >channels.conf
```
