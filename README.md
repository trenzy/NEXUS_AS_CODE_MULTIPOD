# Nexus-as-Code for Multi-Pod

This repo covers the Data Model files for using Multi-Pod with Nexus-as-Code. There are 
three files (which can be combined) that create the necessary infrastructure:

- multi_pod_access_policies.yaml - Creates the associated Access Policies for the L3Out in the infra Tenant.
- multi_pod_tenant.yaml - Creates the necessary policies for the 'infra' Tenant needed for 
Multi-Pod.
- multi_pod_pod_policies.yaml - Creates the required Tunnel Endpoint Address (TEP) needed for each site.

For each of the values, you will need to modify this for your environment.