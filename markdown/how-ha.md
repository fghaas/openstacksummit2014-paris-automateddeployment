# How do vendors approach High Availability?
Note: When we talk about the approach vendors take with providing high
availability for OpenStack, we really need to talk about 3 different
things:


## Deployment
Note: What does the vendor support/recommend to deploy OpenStack in
the first place?

(This is normally also their choice of deployment facility for an HA
manager, as everything else would be braindead.)

It is important to note that the deployment facility is a key
differentiator between vendors' OpenStack products. As a general rule,
you should **always** go with what your vendor supports, rather than
roll your own or, even worse, deploy OpenStack without automation.


## HA Management
Note: Which high availability manager(s) does the vendor support for
ensuring service availability?


## State management
## Data availability
Note: What does the vendor support to ensure state sharing, or data
replication, between the backend stores of stateful services?


<!-- .slide: data-background="images/geeko.svg" data-background-size="contain" -->
### Crowbar deployment
### Pacemaker/HAProxy
### Shared Storage/DRBD
