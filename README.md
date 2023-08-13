# lt01wifi-pmos
* unofficial repo with precompiled recovery zips for the samsung galaxy tab 3 sm-t310

* the zips here zre modified to include the 6.5 rc1 kernel as well as drivers for wifi.
* instructions for getting working audio:
* reboot your device, once it boots connect to it via SSH, we'll need to install some stuff:
  sudo apk add alsa-utils alsa-ucm-conf firmware-samsung-midas.
 after that copy over the contents of tab3-ucm.tar.gz to /usr/share/alsa/ucm2/conf.d/ using sftp
  # to knuxify
  if you want me to remove this repo for whaterver reason just ask me 
