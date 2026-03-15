1. run rsetup
2. choose Overlays
3. choose Install 3rd party overlay
4. select the overlay file
5. exit rsetup
6. run sudo reboot now

check whether the Hifiberry is seen:
aplay -l

test sound with: 
aplay -D plughw:1,0 /usr/share/sounds/alsa/Front_Center.wav

Njoy!
