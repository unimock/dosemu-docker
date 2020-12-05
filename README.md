
# dosemu image with lpr support

The content is copied from https://hub.docker.com/r/jgoerzen/dosemu

Many thanks to "jgoerzen" !!!

The following changes were made:

* changed base-image to debian stretch
* print support
* add docker-compose.yml file


Installation:
```
cp docker-compose.yml-template docker-compose.yml
vi docker-compose.yml
docker-compose up -d
# point your vnc-viewer to vnc://localhost:5901
```



