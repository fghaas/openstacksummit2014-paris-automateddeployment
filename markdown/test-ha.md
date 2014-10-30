# Testing high availability


### Retrieve
# Horizon URL
### from Crowbar

OpenStack Dashboard (admin)

`admin`/`crowbar`


### Select
# `openstack`
### Project
(a.k.a. tenant)


### Use as you normally would


### Doing
# bad things
### to services


`pkill openstack-keystone`

`pkill openstack-nova-api`


### Watch
# services
### recover automatically
`crm_mon`


Service recovery
<iframe src="https://asciinema.org/api/asciicasts/13356?size=medium&amp;speed=2&amp;loop=yes" id="asciicast-iframe-13356" name="asciicast-iframe-13356" scrolling="yes"></iframe>


### Doing
# bad things
### to nodes


`poweroff -f`

`echo o > /proc/sysrq-trigger`


### Watch
# services
### fail over automatically
`crm_mon`


Node recovery
<iframe src="https://asciinema.org/api/asciicasts/13355?size=medium&amp;speed=2&amp;loop=yes" id="asciicast-iframe-13356" name="asciicast-iframe-13356" scrolling="yes"></iframe>
