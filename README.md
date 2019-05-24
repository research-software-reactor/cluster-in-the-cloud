# Cluster-in-the-cloud/HPC

## Background

[Cluster-in-the-cloud](https://github.com/acrc/cluster-in-the-cloud) allows users to submit jobs to a slurm scheduler which then spins up requested instances in a heterogeneous HPC environment.  

Launch a small VM instance
Launch permanenet shared, scalable (parallel) storage 
Install cluster-in-the-cloud, with profile downloaded from organisation template.
Given sufficient budget each job should set up an instance with budget controls and authentication, through AD.  Spin up research instances as in research-compute-instance, or otherwise.
Lainch shared

Auto spin down dormant instances.
Persist storage but connect to Blob so users can move data onto/off instance.

# Sprint objectives 
* Create Blueprints and learning path to ensure security of a cluster-in-the-cloud: data, access and cost

### Learning prerequisites

As part of the RSE Reactor Sprint a deployment of HPC Services in the cloud was developed using Azure Cycle Cloud

Azure CycleCloud is a tool for creating, managing, operating, and optimizing HPC & Big Compute clusters in Azure. With Azure CycleCloud, users can dynamically provision HPC Azure clusters and orchestrate data and jobs for hybrid and cloud workflows. Azure CycleCloud provides alerting, monitoring, and automatically scales HPC infrastructure to ensure your jobs run efficiently at any scale. Azure CycleCloud offers advanced policy and governance features such as: cost reporting and controls, usage reporting, AD/LDAP integration, monitoring and alerting, and audit/event logging to give users full control over who runs what, where, and at what cost within Azure. see more details [here](https://docs.microsoft.com/en-us/azure/cyclecloud/overview) 

RSEs wishing to use Cycle Cloud to deploy HPC cluster on campus should follow the guidance at https://github.com/research-software-reactor/cyclecloud/tree/master/arm-templates and follow the inital setup guidance at https://github.com/research-software-reactor/cyclecloud/blob/master/QuickStarts/SettingUpCycleCloud.md

You can follow the Quick Start tutorial at https://github.com/research-software-reactor/cyclecloud/tree/master/QuickStarts which include Slurm Cluster Deployments.



