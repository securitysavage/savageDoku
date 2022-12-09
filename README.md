# savageDoku
A simple Docker personal wiki container using the Dokuwiki image from linuxserver.io.

First, run ```docker volume create savageDoku``` to create the volume.

Next, run ```sudo mkdir /var/lib/docker/volumes/savageDoku/config```.

Now, run ```docker-compose up -d``` (using docker-compose from AUR) or ```docker compose up -d``` (other platforms) and navigate to http://localhost:8080/install.php to set up the wiki. Too easy.

TODO:
Actually spin this up and start putting my notes in it lol rekt
