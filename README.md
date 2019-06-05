# SRv6 topology
### Requirements
All nodes in the topology are running Ubuntu 18.04
The networks must be set up according to the topology_logical.png
A heat_template is provided for Openstack environments
### Steps to reproduce topolgy in presentation
1. If using the heat_template, modify values to match your environment (keys, network names, etc...)
2. On Seattle and Madrid follow the steps in All_VPP_Nodes.txt
3. On all other nodes (excluding Host_A and Host_B) follow the isntructions in All_LinuxKernel_Nodes.txt
4. Go into each device folder and move the appropriate configs to their location
    * Execute any instructions within the files