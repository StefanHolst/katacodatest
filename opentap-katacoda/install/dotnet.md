# Install Dependencies

On Linux, OpenTAP has a few dependencies that must be manually installed, namely libc6, libunwind, unzip, and git. On Debian derivatives, these can be installed by running the following command:

`apt install libc6-dev, libunwind8, unzip, git`{{execute}}

Note that the packages may have different names on other distributions. OpenTAP should still work if you install the equivalent packages for your distribution.


# Install OpenTAP

Download the OpenTAP distribution (.tar) from our homepage https://www.opentap.io/download.html.

`wget https://www.opentap.io/docs/OpenTAP.9.6.4+6f53deb9.tar`{{execute}}

Install the downloaded distribution:

Untar the package in you home directory:
`tar -xf OpenTAP*.tar`{{execute}}

Change the permission of the INSTALL.sh file to be executable: 
`chmod u+x INSTALL.sh`{{execute}}

Run the INSTALL.sh script: ./INSTALL.sh.
`./INSTALL.sh`{{execute}}
