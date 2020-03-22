Pull the OpenTAP docker image:

`docker pull opentapio/opentap:9.6-ubuntu18.04`{{execute}}


Run a docker container in interactive move (-i):

`docker run -it opentapio/opentap:9.6-ubuntu18.04`{{execute}}


Try running OpenTAP:

`tap`{{execute}}


Take a look at the test plan:

`cat plan.TapPlan`{{execute}}


Run the tap plan:

`tap run plan.TapPlan`{{execute}}
