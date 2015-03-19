To run this image on your system, enter the following into your terminal. 
 
`sudo docker run -ti --rm --env=DISPLAY=:0.0 -v /tmp/.X11-unix:/tmp/.X11-unix --privileged <nameofimage>` 
 
__NOTE__ You MAY have to change the display depending on your system and/or configuration.
