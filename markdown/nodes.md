# Database
### barclamp
Note: Switch back and forth to and from Crowbar browser tab


### Installs
# PostgreSQL
### in high-availability mode


## High Availability
**Storage mode:** DRBD

**Size to Allocate for DRBD Device:** 1


PostgreSQL/DRBD deployment
<iframe src="https://asciinema.org/api/asciicasts/13361?size=medium&amp;speed=2" id="asciicast-iframe-13361" name="asciicast-iframe-13361" scrolling="yes"></iframe>


# RabbitMQ
### barclamp
Note: Switch back and forth to and from Crowbar browser tab


### Installs
# RabbitMQ
### in high-availability mode


## High Availability
**Storage mode:** DRBD

**Size to Allocate for DRBD Device:** 1


RabbitMQ/DRBD deployment
<iframe src="https://asciinema.org/api/asciicasts/13368?size=medium&amp;speed=2" id="asciicast-iframe-13368" name="asciicast-iframe-13368" scrolling="yes"></iframe>


# Keystone
### barclamp
Note: Switch back and forth to and from Crowbar browser tab


### Installs
# Keystone
### under Pacemaker management


Keystone deployment
<iframe src="https://asciinema.org/api/asciicasts/13390?size=medium&amp;speed=2" id="asciicast-iframe-13390" name="asciicast-iframe-13390" scrolling="yes"></iframe>


# Glance
### barclamp
Note: Switch back and forth to and from Crowbar browser tab


### Installs
# Glance
### under Pacemaker management


Glance deployment
<iframe src="https://asciinema.org/api/asciicasts/13362?size=medium&amp;speed=2" id="asciicast-iframe-13362" name="asciicast-iframe-13362" scrolling="yes"></iframe>


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


Cinder deployment
<iframe src="https://asciinema.org/api/asciicasts/13360?size=medium&amp;speed=2" id="asciicast-iframe-13360" name="asciicast-iframe-13360" scrolling="yes"></iframe>


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


Neutron deployment
<iframe src="https://asciinema.org/api/asciicasts/13365?size=medium&amp;speed=2" id="asciicast-iframe-13365" name="asciicast-iframe-13365" scrolling="yes"></iframe>


# Nova
### barclamp
Note: Switch back and forth to and from Crowbar browser tab


### Installs
# Nova
### under Pacemaker management


Neutron deployment
<iframe src="https://asciinema.org/api/asciicasts/13366?size=medium&amp;speed=2" id="asciicast-iframe-13366" name="asciicast-iframe-13366" scrolling="yes"></iframe>


# Horizon
### barclamp
Note: Switch back and forth to and from Crowbar browser tab


### Installs
# Horizon
### under Pacemaker management


Horizon deployment
<iframe src="https://asciinema.org/api/asciicasts/13364?size=medium&amp;speed=2" id="asciicast-iframe-13364" name="asciicast-iframe-13364" scrolling="yes"></iframe>
