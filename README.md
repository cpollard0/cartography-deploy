# cartography-deploy

Lyft cartography is super interesting to me. This repository is to deploy cartography to your AWS environment.

It's built to be deployed as a proof of concept and to explore the tool.

There's more resiliency to add in via ASGs, probably seperate the app from neo4j and persist the storage, add in some load balancers add in frequent refreshes of the data, and add in some more logic for handling multi-account environments.