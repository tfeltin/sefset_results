# SEFSET benchmark results

The following selections are the detailed results for the method described in *SEFSET: Semantic Feature Selection for fault diagnosis in Telemetry data*. Details on the lab topology can be found [here](https://github.com/cisco-ie/telemetry/tree/master/11).

## Routing loop

### leaf8

```
- Cisco-IOS-XR-ipv4-io-oper:ipv4-network/nodes/node/statistics/traffic[node-name=0/RP0/CPU0]received
- Cisco-IOS-XR-ipv4-io-oper:ipv4-network/nodes/node/statistics/traffic[node-name=0/RP0/CPU0]output
- Cisco-IOS-XR-ipv4-io-oper:ipv4-network/nodes/node/statistics/traffic[node-name=0/RP0/CPU0]echo-request-received
- Cisco-IOS-XR-ipv4-io-oper:ipv4-network/nodes/node/statistics/traffic[node-name=0/RP0/CPU0]echo-reply-sent
- Cisco-IOS-XR-ipv4-io-oper:ipv4-network/nodes/node/statistics/traffic[node-name=0/0/CPU0]output
- Cisco-IOS-XR-ipv4-io-oper:ipv4-network/nodes/node/statistics/traffic[node-name=0/0/CPU0]hopcount-sent
```

### dr02

```
- Cisco-IOS-XR-ipv4-io-oper:ipv4-network/nodes/node/statistics/traffic[node-name=0/0/CPU0]output
- Cisco-IOS-XR-infra-statsd-oper:infra-statistics/interfaces/interface/latest/protocols/protocol[interface-name=HundredGigE0/1/0/23 protocol-name=IPV4_UNICAST]bytes-received
- Cisco-IOS-XR-infra-statsd-oper:infra-statistics/interfaces/interface/latest/protocols/protocol[interface-name=HundredGigE0/0/0/22 protocol-name=IPV4_UNICAST]bytes-received
- Cisco-IOS-XR-infra-statsd-oper:infra-statistics/interfaces/interface/latest/protocols/protocol[interface-name=HundredGigE0/0/0/35 protocol-name=IPV4_UNICAST]bytes-received
- Cisco-IOS-XR-infra-statsd-oper:infra-statistics/interfaces/interface/latest/protocols/protocol[interface-name=HundredGigE0/0/0/34 protocol-name=IPV4_UNICAST]bytes-received
- Cisco-IOS-XR-infra-statsd-oper:infra-statistics/interfaces/interface/latest/protocols/protocol[interface-name=HundredGigE0/1/0/34 protocol-name=IPV4_UNICAST]bytes-received
- Cisco-IOS-XR-infra-statsd-oper:infra-statistics/interfaces/interface/latest/protocols/protocol[interface-name=HundredGigE0/1/0/22 protocol-name=IPV4_UNICAST]bytes-received
- Cisco-IOS-XR-infra-statsd-oper:infra-statistics/interfaces/interface/latest/protocols/protocol[interface-name=HundredGigE0/0/0/23 protocol-name=IPV4_UNICAST]bytes-received
```

### dr03

```
- Cisco-IOS-XR-ipv4-io-oper:ipv4-network/nodes/node/statistics/traffic[node-name=0/1/CPU0]output
- Cisco-IOS-XR-ipv4-io-oper:ipv4-network/nodes/node/statistics/traffic[node-name=0/1/CPU0]hopcount-sent
- Cisco-IOS-XR-infra-statsd-oper:infra-statistics/interfaces/interface/latest/protocols/protocol[interface-name=HundredGigE0/1/0/34 protocol-name=IPV4_UNICAST]bytes-sent
- Cisco-IOS-XR-infra-statsd-oper:infra-statistics/interfaces/interface/latest/interfaces-mib-counters[interface-name=HundredGigE0/1/0/34]bytes-sent
- Cisco-IOS-XR-infra-statsd-oper:infra-statistics/interfaces/interface/latest/generic-counters[interface-name=HundredGigE0/1/0/34]bytes-sent
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/interface-xr/interface[interface-name=HundredGigE0/1/0/34]bytes-sent
```

## Black hole

### leaf3
```
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/0:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/11:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/15:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/9:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/16:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/12:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/18:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/10:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/13:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/19:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/4:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/14:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/5:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/6:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/7:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/8:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/21:rfc2819-ether-stats-oversized-pkts
- n58:Cisco-IOS-XR-ip-tcp-oper:tcp-connection_nodes_node_statistics_pcbs_pcb.csv:7f8c1401f528:1610612736:read-io-counts/arm-count
- n59:Cisco-IOS-XR-ip-tcp-oper:tcp-connection_nodes_node_statistics_summary.csv:0/RP0/CPU0:connections-accepted
- n59:Cisco-IOS-XR-ip-tcp-oper:tcp-connection_nodes_node_statistics_summary.csv:0/RP0/CPU0:connections-established
- n68:Cisco-IOS-XR-ipv4-io-oper:ipv4-network_nodes_node_statistics_traffic.csv:0/RP0/CPU0:icmp-stats/admin-unreachable-received
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/30:total-bytes-transmitted
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/1:rfc2819-ether-stats-oversized-pkts
- n0:Cisco-IOS-XR-drivers-media-eth-oper:ethernet-interface_statistics_statistic.csv:HundredGigE0/0/0/30:total-good-bytes-transmitted
```

## Interface Shutdown

### spine2

```
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/node-type-sets/node-type-set/interface-summary[type-set-name=hardware-interfaces]down-interface-count
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/node-type-sets/node-type-set/interface-summary[type-set-name=hardware-interfaces]up-interface-count
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/node-type-sets/node-type-set/interface-summary[node-name=0/0/CPU0 type-set-name=hardware-interfaces]down-interface-count
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/node-type-sets/node-type-set/interface-summary[node-name=0/0/CPU0 type-set-name=hardware-interfaces]up-interface-count
- Cisco-IOS-XR-ip-tcp-oper:tcp/nodes/node/statistics/ipv6-traffic[node-name=0/RP0/CPU0]tcp-retransmitted-packets
- Cisco-IOS-XR-ip-bfd-oper:bfd/ipv6-single-hop-node-location-summaries/ipv6-single-hop-node-location-summary[location=0/0/CPU0]up-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/ipv4-single-hop-node-location-summaries/ipv4-single-hop-node-location-summary[location=0/0/CPU0]up-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/ipv6-single-hop-node-location-summaries/ipv6-single-hop-node-location-summary[location=0/0/CPU0]down-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/ipv4-single-hop-node-location-summaries/ipv4-single-hop-node-location-summary[location=0/0/CPU0]down-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/summary[]up-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/ipv6-single-hop-summary[]down-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/ipv6-single-hop-summary[]up-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/summary[]down-count
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/interface-summary[]up-interface-count
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/interface-summary[]down-interface-count
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/inventory-summary[]up-interface-count
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/inventory-summary[]down-interface-count
```

### leaf4

```
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/node-type-sets/node-type-set/interface-summary[type-set-name=hardware-interfaces]up-interface-count
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/node-type-sets/node-type-set/interface-summary[type-set-name=hardware-interfaces]admin-down-interface-count
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/node-type-sets/node-type-set/interface-summary[node-name=0/0/CPU0 type-set-name=hardware-interfaces]up-interface-count
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/node-type-sets/node-type-set/interface-summary[node-name=0/0/CPU0 type-set-name=hardware-interfaces]admin-down-interface-count
- Cisco-IOS-XR-ip-tcp-oper:tcp/nodes/node/statistics/ipv6-traffic[node-name=0/RP0/CPU0]tcp-retransmitted-packets
- Cisco-IOS-XR-ip-bfd-oper:bfd/ipv4-single-hop-node-location-summaries/ipv4-single-hop-node-location-summary[location=0/0/CPU0]down-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/ipv6-single-hop-node-location-summaries/ipv6-single-hop-node-location-summary[location=0/0/CPU0]down-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/ipv4-single-hop-node-location-summaries/ipv4-single-hop-node-location-summary[location=0/0/CPU0]up-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/ipv6-single-hop-node-location-summaries/ipv6-single-hop-node-location-summary[location=0/0/CPU0]up-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/ipv6-single-hop-summary[]up-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/summary[]up-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/summary[]down-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/ipv6-single-hop-summary[]down-count
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/inventory-summary[]admin-down-interface-count
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/inventory-summary[]up-interface-count
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/interface-summary[]admin-down-interface-count
- Cisco-IOS-XR-pfi-im-cmd-oper:interfaces/interface-summary[]up-interface-count
```

## BFD Failure

### leaf7
```
- Cisco-IOS-XR-ip-bfd-oper:bfd/ipv4-single-hop-node-location-summaries/ipv4-single-hop-node-location-summary[location=0/0/CPU0]down-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/ipv4-single-hop-node-location-summaries/ipv4-single-hop-node-location-summary[location=0/0/CPU0]up-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/summary[]up-count
- Cisco-IOS-XR-ip-bfd-oper:bfd/summary[]down-count
- Cisco-IOS-XR-ipv4-bgp-oper:bgp/instances/instance/instance-active/default-vrf/process-info[instance-name=default]established-neighbors-count-total
- Cisco-IOS-XR-ipv4-bgp-oper:bgp/instances/instance/instance-active/default-vrf/process-info[instance-name=default]established-neighbors-count
- Cisco-IOS-XR-ipv4-bgp-oper:bgp/instances/instance/instance-active/default-vrf/process-info[instance-name=default]edm-requests-count
- Cisco-IOS-XR-ipv4-bgp-oper:bgp/instances/instance/instance-active/default-vrf/process-info[instance-name=default]path-count
- Cisco-IOS-XR-ipv4-bgp-oper:bgp/instances/instance/instance-active/default-vrf/process-info[instance-name=default]update-messages-sent
```