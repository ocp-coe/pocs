Proof of Concepts
------------------

* Steps for POC
	* Qualify the need for a POC and sync with AE's to ensure an opportunity is registered in SalesForce
	* Open the OpenShift SF opportuity and select the "Create Proof of Concept" tab near the Opportunity Detail section.  
	
	** If the tab does not show up on your opportunity you probably don't have the right SF permissions.  You will need to go through the pain of updating your SF license to include this functionaltiy by opening a <a href="https://redhat.service-now.com/rh_ess/home.do" target="blank">ticket</a> 

        * Fill out the following [form](https://docs.google.com/a/redhat.com/forms/d/e/1FAIpQLSecXn-DoF4zGf-TQe8BWirNN3Sn7NwSSE1aUNi9FuByYTaZ8w/viewform) to engage the Tiger team. 

* PreReqs for POC's
	* Prior to any installation the customers need to make sure they perform the prereqs outline in these installs.
		* [3.9 prereqs](docs/OCP-prereqs-v3.9?raw=true)
		* [3.7 prereqs](docs/OCP-prereqs-v3.7?raw=true)
		* [3.6 prereqs](docs/OCP-prereqs-v3.6?raw=true)

	** Official documentation for 3.9 is located here --> https://docs.openshift.com/container-platform/3.9/getting_started/install_openshift.html#install-prerequisites

Success criteria
------------------

As part of the POC process it is alwasy a good idea to get a written success criteria agreed to by both Red Hat and the customer to ensure that the proper expectations are set and met for the engagement.  Below is a simple example.

	* Success Criteria:
		* Install OpenShift using the “Advanced” method (leveraging Ansible)
		* Deploy, Configure, and understand the following components/concepts
		* Routing using HAProxy and SDN networking
		* Docker Registry for application image storage
		* Understand Templates
		* Understand Security Context Constraints
		* Understand how DNS is used within OpenShift
		* Understand how to use oc tools
		* Understand how Cluster Metrics are used
		* Become familiar with how Aggregated Logging works

