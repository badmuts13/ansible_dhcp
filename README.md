## ansible_DHCP
Simple role to configure DHCP server and safeguard the configuration. 

## Requirements
This role is tested on RHEL and CentOS 7.7.
DHCP version used: 4.2.5-77

## Role Variables
This role uses no variables in file. It does use with_items for the FW config.

## Dependencies
None

Example Playbook
	# YAML file for dhcp roles
	#
	# Keep this file as clean as possible! 
	#
	- hosts: dhcp
	  become: true
	  roles:
	    - ansible_dhcp

License
-------

MIT

Author Information
------------------
Bernhard Muts
https://github.com/badmuts13/
