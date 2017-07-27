# swift_stats_snmp

A script of how to use the openstack swift-recon script to extend SNMP to include this data

Add this to your `/etc/snmp/snmpd.conf`

```
extend swift-stats /usr/local/bin/swift_stats
```

To poll: 
```#snmpwalk -v2c -c _community_ _host_ .1.3.6.1.4.1.8072.1.3.2.4.1.2.11.115.119.105.102.116.45.115.116.97.116.115 ```
