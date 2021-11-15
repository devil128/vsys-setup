## Basic Setup Project: 
- Installiere Kubectl (Windows: https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/, https://kubernetes.io/de/docs/tasks/tools/install-kubectl/) 
- Intelji Installiere Kubernetes Support 
- Intelji CloudCode (https://plugins.jetbrains.com/plugin/10485-kubernetes, https://plugins.jetbrains.com/plugin/8079-cloud-code)  
- Importiere Kubectl / Kopiere diese in ~/.kube/config

- Clone Repos
- Build Project


## Skaffold
Skaffold ermöglicht es schnell einen Service auf Kubernetes zu laden und diesen zu debuggen.
Dafür ist Cloud Code erforderlich. Intelji stellt dazu Run Configurations bereit.
Um aber mit JIB gebaute Images auf Kubernetes zu laden ist zugang zu dem Docker Registry
erforderlich. Dafür muss in der Commandline 
einmal ``docker login registry.projectdw.de`` ausgeführt werden.
Mit den Login Daten:
User: admin
Password:d&6RQ>bf*S)JRbKJ

## CI / CD 
Deployments werden gegen den Main Branch werden automatisch gebuildet und deployt (falls kein Fehler auftritt)


