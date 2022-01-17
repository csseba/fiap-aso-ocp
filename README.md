# fiap-aso-ocp

The file Deployment.yml will deploy everything needed in order to get Blog Django on Openshift.

Run:
oc create -f https://raw.githubusercontent.com/csseba/fiap-aso-ocp/main/Deployment.yml

Notes: Since we don't have permission to create a project via yml file, we are assuming the project with namespace Fiap already exists.

The blog will be exposed in the following route: fase4-grupo5-fiap.apps.na46.prod.nextcle.com
