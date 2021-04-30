# Signal K user configuration for MV Beatrice

This repository contains the Signal K configuration used to operate
Beatrice of Hull.

A vanilla Signal K installation can be restored to this configuration
by cloning the directory into ```/root/.signalk```:
```
$> sudo su -
$> git clone --recursive https://github.com/preeve9534/beatrice-signalk-configuration 
$> mv beatrice-signalk-configuration .signalk
```

Under Venus OS, the configuration folder is a different place, so
better to do:
```
$> cd /data/conf
$> git clone --recursive https://github.com/preeve9534/beatrice-signalk-configuration 
$> mv beatrice-signalk-configuration signalk
```
