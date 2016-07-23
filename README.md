# Sonarqube for OpenShift Enterprise 3

This is instant sonarqube application for OpenShift Enterprise 3.

```
oc new-project sonarqube --display-name="Sonarqube" --description="Sonarqube"
oc new-app -f https://raw.githubusercontent.com/eformat/openshift-nexus/master/sonarqube.yaml
```
