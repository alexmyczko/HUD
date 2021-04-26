# HUD
head up display for car or airplane

# Objective
Replace your cheap plastic car or airplane sun visor with a non transparent display.

# WARNING / SAFETY
BEWARE, MESSING AROUND OR BEING NOT FOCUSED TO DRIVING IS DANGEROUS
AND MOST PROBABLY NOT LEGAL. YOU HAVE BEEN WARNED.

# Hardware Ingredients

Minimum
- 1 x [MacBook Air](https://next.com) (preferably M1 for long battery times)
  Open System Preferences, hold down your Command + Option keys and click Display to rotate the screen 90
- 1 x iPhone with [SensorLog](http://sensorlog.berndthomas.net) and INTERNET

Roof mount
- Swiss army knife
- Electric tape
- Measure band
- Piece of metal that can be bent (0.5 - 1.0 mm thick)

Optional add ons
- 1 x [Car charger](https://www.digitec.ch/de/search?filter=t_15988%3D304316%7C304317&q=car+charger+30w&so=5)
- 1 x RTL-SDR USB stick for extra sensor data (rtl-433, dump1090, welle.io)
- 1 x [SHT31](https://www.digitec.ch/de/s1/product/sensirion-sht31-entwicklungsboard-kit-9717948?gclid=Cj0KCQjwyN-DBhCDARIsAFOELTm_26hck6XTyOt3p1EEpUqPWCujMSZ_YCDyusBeKREwiLQG-pnhbqgaArZ-EALw_wcB&gclsrc=aw.ds)

# Software Ingredients
- On iPhone install SensorLog
- On macOS install [brew](https://brew.sh), fnt, corelocationcli, thttpd or nginx, [gps distance](https://github.com/alexmyczko/GPS-distance)
- [POI databases](http://slipo.eu/?p=1551)
- [Fonts that are suitable for HUD](https://github.com/NR74W/WipEout-Fonts)
- `curl -s https://freegeoip.app/csv/ | awk -F ',' '{print $(NF-2) " " $(NF-1)}'`
