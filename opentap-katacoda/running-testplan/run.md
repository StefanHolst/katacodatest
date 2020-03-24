Pull the OpenTAP docker image:

`docker pull opentapio/opentap:rc-slim-ubuntu18.04`{{execute}}


Run a docker container in interactive move (-i):

`docker run -it opentapio/opentap:rc-slim-ubuntu18.04`{{execute}}


Try running OpenTAP:

`tap`{{execute}}


Take a look at the test plan:

`cat plan.TapPlan`{{execute}}


Run the tap plan:

`tap run plan.TapPlan`{{execute}}
