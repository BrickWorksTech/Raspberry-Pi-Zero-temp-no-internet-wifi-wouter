Simple Raspberry pi W Hot-spot (still testing)

ORIGINAL SOURCE: https://github.com/quangthanh010290/RPI3_HOTSPOTS
WHERE I GOT IT FROM: https://www.youtube.com/watch?v=u_I2mVsrxB4&t=68s
https://github.com/PNPtutorials/PNP_RPi3_AP

Overview:
In several of my other projects i needed a WiFi network. For my next one i need a mobile network. I’ve decided that using a Raspberry pi zero was the best choice since its cheap and easy to move. I wont be needing it to connect to another router so i’m ignoring that part but it is in the origenal link.

Notes:

Steps:

1. From inside user directory:
git clone https://github.com/quangthanh010290/RPI3_HOTSPOTS.git

2. Go into “PNP_RPi3_AP” folder:
cd PNP_RPi3_AP

3. Run install.sh:
sudo ./install.sh

5. Make station
sudo ap my_ssid 12345678

4. Make hot-spot by running sudo ap “Wifi_Name” “password”
sudo ap Mlabviet_wifi
or
sudo ap my_ssid 12345678

5. Two know complete 2 blue arrows should be in the upper right hand corner where the wifi signal used to be.

Further help:
The youtoub link