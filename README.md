# Cisco SNMP Monitoring System

ระบบมอนิเตอร์ Traffic ของ Cisco Router (R1) โดยใช้ Prometheus, Grafana และ SNMP Exporter

## Architecture
- **Target Device:** Cisco Router R1 (`192.168.200.254`)
- **Monitoring Server:** Prometheus / Grafana / SNMP Exporter (`192.168.200.130`)
- **Monitored Interface:** FastEthernet1/1 (`ifIndex=3`)

## Services & Ports
- **Prometheus UI:** `http://192.168.200.130:9090`
- **Grafana Dashboard:** `http://192.168.200.130:3000`
- **SNMP Exporter:** `http://192.168.200.130:9116`

## Key Metrics
- `ifInOctets`: Inbound Traffic (Mbps)
- `ifOutOctets`: Outbound Traffic (Mbps)

## How to Run
