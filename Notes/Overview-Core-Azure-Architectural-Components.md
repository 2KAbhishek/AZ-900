# Azure Architectural Components

## Regions

The global map is divided into 60+ regions, these are physical locations in which the servers exist.
Not all regions are available to everyone, some of them have restrictions on them.

> e.g - China and Germany regions are not available to everyone. Some government regions are also hidden.

## Region Pairs

Each region has one other region which is treated as it's pair.
They are mostly in the same geographic location, for higher speed access.
Deployments are done in only one part of the pair, other is untouched.
In case of disaster one of them is treated as priority.

> e.g - North Europe - West Europe

## Availablity Zones

These are zones which reside inside the regions, these are physically seperate data centers and have their own power, internet etc.

## Resource Groups

They are basically the tree structure of all the logically related resources.
These are logically seperated depending upon projects, accounts etc.

## Subscriptions

Subscriptions is generally the billing unit, all the resources in that subscription are billed to it.
One user can have multiple subscriptions.

> e.g - Seperate subscription for HR, Marketing and Finance

## Management Groups

Useful for setting up policies on subscriptions.

## Resources

Instances of services, created by the user.

## Azure Resource Manager

There are many different ways to access azure

> Like Web Portal, Azure Shell, Visual Studio

These are all handled by Azure Resource Manager API, It can handle public and hybrid cloud models.
