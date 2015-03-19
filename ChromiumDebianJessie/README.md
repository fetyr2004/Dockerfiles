To run the chromium docker container, run the following in your terminal: 
 
`sudo docker run -ti --rm --env=DISPLAY=:0.0 -v /tmp/.X11-unix:/tmp/.X11-unix -v /dev/snd:/dev/snd --privileged <nameofimage>` 
 
__NOTE__ You MAY have to change the display depending on your system and/or configuration
