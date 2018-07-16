# Home Assistant config files

My Home Assistant configuration.
Home Assistant is running in a Python virtual environment on an Intel NUC running Ubuntu.

## Intergrations you'll find in my config files:

House Mode:
  - basis for all time of day events
  - set based on luminance or time or Sunset
  - Holiday mode for reduced functionality when away (with appearance of still being at home)

Presence Detection/Device tracking:
  - GPS via HASS iOS Frontend
  - IP address recognition via asuswrt
  - iBeacon via OwnTracks and MQTT
  - BMW ConnectedDrive
  - Lights based on motion sensors
  - Gate opening based on iBeacons
  - Select lights based on iBeacons
  - Bedtime House Mode based on iBeacons

Z-wave:
  - HASS OpenZave intergation (default)
  - lights
  - ceiling fans
  - temp/light/movement sensors
  - switches

Lights:
  - Light control, on/off, dimming
  - Automated via House Mode
  - Automated via luminance
  - Automated via Doorbell
  - Automated via time
  - Automated via Presence (iBeacons and OwnTracks)
  - Automated via Media Player state

Watering:
  -  Automated with with adjustable timer

SolarEdge Solar:
  - inverter power generation data (via Rest Sensor)
  - daily power generated

emoncms:
  - several sensors covering Solar Prod, House and Grid usage
  - onewire temp sensor

Dyson:
  - fan, controls
  - temp, air quality and humidity sensors

Sonos:
  - Media Player control
  - Doorbell sound (based on time of day)

Media Players:
  - Sonos
  - Plex
  - Samsung tv
  - Chromecast

Google maps:
   - travel time to home
   - travel time from home to multiple locations

Google Calendar:
    - next family appointment
    - bin night, changing icon

Uber:
  - UberX pickup time
  - UberX travel times
  - UberX estimated cost

BMW ConnectedDrive:
  - Odometer/fuel data
  - Car location trackers
  - Secure Status
  - Windows Status
  - Doors Status

NSW Transport:
  - Live Bus times

MQTT:
  - OwnTracks
  - Device testing

IT Device Sensors:
  - Qnap NAS
  - APC ups
  - HASS server HW and version monitoring
  - Speedtest - internet speed

Weather/Sun:
  - DarkSky weather
  - Sun tracking

Cameras:
  - Hikvision (MPEG) video feeds and motion detection
  - Doorbird (Live, Cloud recent images)

Doorbird (multi-function video intercom):
  - Video feed
  - Last visitors images
  - IR light control
  - Magnetic gate latch open (via intergrated relay)
  - Doorbell played via Sonos based on time of day

Other features:
  - iOS Frontend theme changes based on time of day
  - Actionable notifications to iOS Frontend
  - Logbook entries
  - File size (checking HASS DB)
  - Web Scrape (checking for latest HASS version)
  - Templates for data conversion, data formatting and conditions

Roadmap:
  - MQTT - micro-controllers
  - Front gate sensors
  - Window control
  - Roller blinds control
  - Extendable sun shade control
  - Automated weather based watering control
