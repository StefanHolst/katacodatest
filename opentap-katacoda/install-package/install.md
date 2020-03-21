Pull the OpenTAP docker image:

`docker pull opentapio/opentap:9.6-ubuntu18.04`{{execute}}


Run a docker container in interactive move (-i):

`docker run -it opentapio/opentap:9.6-ubuntu18.04`{{execute}}


Try running OpenTAP:

`tap`{{execute}}


List installed OpenTAP packages:

`tap package list --installed`{{execute}}


Install the Demonstration package:

`tap package install Demonstration`{{execute}}


Check the new list of installed packages:

`tap package list --installed`{{execute}}
