# Azure Role Based Access Control

Microsoft's preferred solution for access control.
Creates different roles that represent common tasks for a job.
Then assigns granular permissions to each role.
Finally assigns individual users to each role.

## Pre Defined Roles

Top Level Roles

- Reader: Can read, but cannot modify it.
- Contributor: Has all permissions except for granting access.
- Owner: Can grand and revoke access.

## Azure Resource Locks

Azure provides locks to protect certain resources bu putting on locks, which turn the resources read only.
Useful for protecting production resources and resource groups from being deleted.

## Resource Tags

Useful for providing metadata for resources for easier identification and grouping.
