Pull the OpenTAP docker image:

`docker pull opentapio/opentap:rc-slim-ubuntu18.04`{{execute}}


Run a docker container in interactive move (-i):

`docker run -it -v $(pwd):/home -w /home opentapio/opentap:rc-slim-ubuntu18.04`{{execute}}


Try running OpenTAP:

`tap`{{execute}}