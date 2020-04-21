## What is Atlas		
		- Atlas is MongoDB's database as a service solution.
		- It provides functionality to set up your database in the cloud without needing to configure the fine details yourself manually using the Shell.
		- Handles replication, which means your database maintains redundant copies of data to increase availability.
		
		## How Atlas works
		- Deploy by clusters, which are groups of servers that store your data.
		- Called a replica set, which is a cluster where each server stores the same data.
		- Each time you insert or update a document, redundant copies are stored within the set.
		- Ensures that if you lose access to a server in your cluster you're not going to lose your data.
		
		
		## Why use Atlas?
		- One main reason is the simplicity of setup.
		- Atlas manages the details of creating clusters for you, which simplifies the operational overhead of running a deployment.
		- The Atlas interface makes it easier to manage and deploy MongoDB across cloud providers and regions.
		- Allows you to configure users with different privileges levels in your database.
		
