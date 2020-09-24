Download the OpenTAP distribution (.tar) from our homepage https://www.opentap.io/download.html.

`wget https://www.opentap.io/docs/OpenTAP.9.9.2+e9c70141.tar`{{execute}}


Untar the package in you home directory:

`tar -xf OpenTAP*.tar`{{execute}}


Change the permission of the INSTALL.sh file to be executable: 

`chmod u+x INSTALL.sh`{{execute}}


Run the INSTALL.sh script (remember to answer y):

`./INSTALL.sh`{{execute}}


Add OpenTAP to PATH:

`PATH=$PATH:$(pwd)/.tap`{{execute}}


Try running OpenTAP:

`tap`{{execute}}
