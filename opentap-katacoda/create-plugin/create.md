Pull image `docker pull opentapio/opentap:9.6-ubuntu18.04`{{execute}}

Start OpenTAP `docker run -it -v $(pwd):/home -w /home opentapio/opentap:9.6-ubuntu18.04`{{execute}}

Test OpenTAP `tap`{{execute}}

List installed OpenTAP packages `tap package list --installed`{{execute}}

Install a package `tap package install TUI --version any`{{execute}}

Try the TUI `tap tui`{{execute}}

Try creating a test plan.

Run the test plan `tap run plan.TapPlan`{{execute}}