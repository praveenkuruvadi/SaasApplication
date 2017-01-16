# SaasApplication
Created a custom cluster on 3 nodes, each running multiple VMs (using KVM for virtualization) where the stand alone Robocode web application (created in JSP) was deployed. 
All the instances of the application connect to a central database on the Azure cloud. A load balancer was designed to handle the traffic by multiple users. Currently developing access control/security schemes to secure the cloud.
