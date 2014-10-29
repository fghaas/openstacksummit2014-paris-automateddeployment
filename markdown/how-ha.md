# How do vendors approach High Availability?
Note: When we talk about the approach vendors take with providing high
availability for OpenStack, we really need to talk about 3 different
things:


## Deployment
Note: What does the vendor support/recommend to deploy OpenStack in
the first place?

(This is normally also their choice of deployment facility for an HA
manager, as everything else would be braindead.)


## HA Management
Note: Which high availability manager(s) does the vendor support for
ensuring service availability?


## State management
## Data availability
Note: What does the vendor support to ensure state sharing, or data
replication, between the backend stores of stateful services?


![SUSE logo](images/suse-logo.svg)


### Crowbar deployment
### Pacemaker/HAProxy
### Shared Storage/DRBD
