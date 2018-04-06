# Gitea kubernetes deployment for GCE

Based on the gitea deployment of jmreffer, a kubernetes deployment has been created with:

* GCE PV config provided;
* Config in a configmap so that the application can be updated without container rebuild
