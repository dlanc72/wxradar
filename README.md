![17ca96c1-4ab8-4dc1-98a6-db098afb3b08~1](https://github.com/user-attachments/assets/0501e9b4-508f-4641-b8a8-f55c17e3f7d2)

Weather Radar displayed on a Waveshare epd7in3e eink display using a Raspberry Pi Zero WH. Pulls the map from Geoapify (with free API key) and weather radar from NOAA. Allows for adjustable lat/long/zoom, and weather is displayed in color depending on severity. 

I have this running every 10 minutes via cron. More extreme longitudes may require adjustment on how the radar and map matches up (denoted in the code).

Waveshare fresh install instructions:
https://www.waveshare.com/wiki/7.3inch_e-Paper_HAT_(E)_Manual#Working_With_Raspberry_Pi
