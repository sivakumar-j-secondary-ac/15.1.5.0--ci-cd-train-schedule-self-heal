# cicd-pipeline-train-schedule-kubernetes

This is a simple train schedule app written using nodejs. It is intended to be used as a sample application for a series of hands-on learning activities.


# Things needed for this Phase-4

## Pipeline:
 
  * Multibranch pipeline

## Plugins: 

 * Kubernetes Continuous Deploy


## Credentials ID Needed:
	* Docker hub : kind: uwp,un,pwd,ID: docker_hub_login
	* Github:      kind: uwp,un,pwd: Github API token,ID: github_key
	* K8:          kind: k8config,id: kubeconfig,kubeconfig~enter directly: master's cat ~/.kube/config 

## Files changed from perv version:
	*  new - train-schdule-kube.yml
	*  mod - Jenkins file for k8 deployment

## Acronym : 
	* uwp  : username with password
	* un   : username
	* pwd  : password
	* mod  : modified
	* k8   : kubernetes
	* k8config : kubernetes configuration  




