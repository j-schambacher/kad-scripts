# kad-scripts
HBOS startup and control scripts for KAD WiSA implementation etc.

Scripts:
--------
system_startup.py -> executed once after boot through systemd

system_shutdown.py -> potential shutdown/reset procedure - not yet implemented

stereo_start.py, tx_start.py -> scripts for testing

Config(Map) files:
-------------
room.cfg -> used by system_startup.py (correct MAC addresses need to be inserted)
mono.cfg -> example configuration for mono
myroom2.0-I2S.cfg -> stereo configuration


Joerg Schambacher, 2020-07-21
joerg@i2audio.com
