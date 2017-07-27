# swift_stats_snmp

A script of how to use the openstack swift-recon script to extend SNMP to include this data

Add this to your /etc/snmp/snmpd.conf

extend swift-stats /usr/local/bin/swift_stats
