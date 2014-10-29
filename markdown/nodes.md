# Database
### barclamp
Note: Switch back and forth to and from Crowbar browser tab


### Installs
# PostgreSQL
### in high-availability mode


## High Availability
**Storage mode:** DRBD

**Size to Allocate for DRBD Device:** 1


# RabbitMQ
### barclamp
Note: Switch back and forth to and from Crowbar browser tab


### Installs
# RabbitMQ
### in high-availability mode


## High Availability
**Storage mode:** DRBD

**Size to Allocate for DRBD Device:** 1


# Keystone
### barclamp
Note: Switch back and forth to and from Crowbar browser tab


### Installs
# Keystone
### under Pacemaker management


# Glance
### barclamp
Note: Switch back and forth to and from Crowbar browser tab


### Installs
# Glance
### under Pacemaker management


# Cinder
### barclamp
Note: Switch back and forth to and from Crowbar browser tab


### Installs
# Cinder
### under Pacemaker management


### Stores volumes on
# Compute nodes
(for purposes of this tutorial)

**Type of volume:** Local file


### Also supports
# SAN storage
### and
# Ceph


# Neutron
### barclamp
Note: Switch back and forth to and from Crowbar browser tab


### Installs
# Neutron
### under Pacemaker management


## neutron-l3-agent
# OCF RA
`neutron-ha-tool.py`

Note:
- `monitor` action checks for dead l3-agents
- `start` action
  - replicates DHCP agents
  - migrates routers onto healthy agents

OpenStack Juno adds *experimental* support for DVR and HA L3
agents. It is expected that `neutron-ha-tool.py` will no longer be
necessary once this feature has stabilized (targeted for Kilo).


## Networking Plugin
ML2 with OVS/GRE


# Nova
### barclamp
Note: Switch back and forth to and from Crowbar browser tab


### Installs
# Nova
### under Pacemaker management


# Horizon
### barclamp
Note: Switch back and forth to and from Crowbar browser tab

### Installs
# Horizon
### under Pacemaker management
