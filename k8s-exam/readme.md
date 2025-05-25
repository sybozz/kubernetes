# task 1
- create a kubernetes configmap
	- where data is name = yourname

- create a deployment
	- 1 replica
	- image: alpine
	- add custom command : 
		- run a infinite loop
		- echo the name variable from the configmap
		- sleep 5 second
		- loop continues forever
	
**submit the yaml file**




# task 2
- Create a deployment named shared-empty-dir
- should have 3 containers
	- container1
		- name: container1
		- image: alpine
		- command to sleep 1 hour
	- container2
		- name: container2
		- image: alpine
		- command to sleep 1 hour
	- container3
		- name: container3
		- image: alpine
		- command to sleep 1 hour
- every container should share volume with empty directory mechanism.

**submit the yaml file**




# task 3
- write a deployment file with httpd image
- write a clusterip service for it
- write a ingress file for service

**submit the yaml file**


