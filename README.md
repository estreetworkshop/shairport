This is a fork of Abrasive's Shairport code, with a few added lines to allow my PI-Relay to work properly.  The idea is the PI is a Airplay client, and when music is playing it flips a relay connected to GPIO 1.  This way you are not burning the power of your speakers when no music is playing.  Multiple devices can turn on the relay by writing to the /var/relay directory

Follow the commands here, but substitute my repository in git
http://raspberrypihq.com/how-to-turn-your-raspberry-pi-into-a-airplay-receiver-to-stream-music-from-your-iphone/

In the /etc/init.d/shairport file you can rename your PI for Airplay
