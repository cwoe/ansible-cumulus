# Archive Notice
I haven't had access to a Nvidia/Cumulus switch in the last couple of years, so this playbook is unlikely to work with current OS versions. 

---

# ansible-cumulus
Full setup for Cumulus Linux using ansible
This playbook is designed for a EVPN VXLAN topology using external routing.

The following features are configured:
- NTP
- DNS
- Proxy access
- LLDP
- SNMP
- Network Interfaces
- BGP & EVPN
- RADIUS authentication
- SSH Keys

Parts of the config are taken from:

<https://github.com/pgkehle/ansible-proxy-setup>

<https://github.com/IPvZero/EVPN-VXLAN-Cumulus>
