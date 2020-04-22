# What is Atlas 
    - Atlas is MongoDB's database as a service solution.
    - It provides functionality to set up your database in the cloud without needing to configure the fine details yourself manually using the Shell.
    - Handles replication, which means your database maintains redundant copies of data to increase availability.

# How Atlas Works

    - Deploy by clusters, which are groups of servers that store your data.
    - Called a replica set, which is a cluster where each server stores the same data.
    - Each time you insert or update a document, redundant copies are stored within the set.
    - Ensures that if you lose access to a server in your cluster you're not going to lose your data.
		
# Why Use Atlas

    - One main reason is the simplicity of setup. 
    - Atlas manages the details of creating clusters for you, which simplifies the operational overhead of running a deployment. 
    - The Atlas interface makes it easier to manage and deploy MongoDB across cloud providers and regions. 
    - Allows you to configure users with different privileges levels in your database.
		
# Databases, Collections, and Documents

    - Databases are contained in cluster. 
    - A database serves as a namespace for collections.
    - Collections store individual records called documents.

This graphic illustrates the relationship between databases, collections, and documents.
![image]()

This hierarchy allows us to group together records of similar items within collections, and group collections required for the same application within the same database.

We can also establish security policies that authorize users with different roles and different levels of access at the database, or collection, level.

We typically reference a specific collection by expressing the name of the database, followed by a dot, followed by the name of the collection.

Example: city.neighborhood