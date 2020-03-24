Pull image `docker pull opentapio/opentap:rc-slim-ubuntu18.04`{{execute}}

Start OpenTAP `docker run -it -v $(pwd):/home -w /home opentapio/opentap:rc-slim-ubuntu18.04`{{execute}}

Test OpenTAP `tap`{{execute}}

Install the SDK package `tap package install SDK`{{execute}}

`tap sdk new project MyPlugin`{{execute}}


Open MyFirstTestStep.cs in the IDE:
`MyFirstTestStep.cs`{{open HOST1}}


Add `Log.Info("Hello");` in any of the methods.

`dotnet build`{{execute}}

`bin/Debug/tap run MyFirstTestPlan.TapPlan`{{execute}}

Concrats you have created your first teststep plugin.

Side note. To create a OpenTAP Package. Run `dotnet build -c Release`{{execute}}
