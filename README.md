### Kamailio installatio on Debian

OS Debian

Initial requirements:
`apt install gnupg2`

Ansible doesn't restart services, only installs pkgs and configs

Installation of Kamailio HA node in following sequence:

- kamailio
- rtpengine
- keepalived

# TODO:
- kamailio-cfg-apply
