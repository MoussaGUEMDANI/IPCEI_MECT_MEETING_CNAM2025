![CNAM LOGO](pics/cnam_logo.png)

Welcome! This page serves as the central hub for our demo, where you’ll find all the essential resources and instructions consolidated for the session.


## Repository Clone

```bash 
git clone https://github.com/MoussaGUEMDANI/IPCEI_MECT_MEETING_CNAM2025.git
```

## Hardware Requirements

1. Networking equipment (Ethernet cables, switches, etc.)
2. COTS host machines (for CU/DU and 5G Core) (TBD)
3. N77 band-compatible antennas
4. Commercial Off-The-Shelf (COTS) 5G/NR UEs
5. USRP X310 SDR (with UBX daughterboards)

## Software Prerequisites

1. Ubuntu 22.04 LTS (recommended)
2. srsRAN Project (latest release)
3. OpenAirInterface (latest release)
4. Open5GS (latest release) (5G Core)
5. Monitoring tools (Grafana, InfluxDB, Telegraf)

## What do we cover in the demo?

The aim of this tutorial is to demo:

1. Deployment of an end-to-end 5G/NR Standalone (SA) setup using srsRAN and OAI with USRP X310 and COTS UEs on band N77.
2. Real-time monitoring and comparison of system performance (throughput, latency, jitter, CPU usage, etc.).
3. MAC Scheduler and PHY layer PRB allocation (to discuss) 

## Estimated Demo Replication Time
~xx mins (subject to environment setup)

# Setup Instructions

## 1. Build and Install Open5GS (5G Core)

Clone the repository and install dependencies:



run the script to install dependencies and packages

clone open5GS

```bash
git clone https://github.com/open5gs/open5gs.git
```


##  

## Build and Install srsRAN Project 

## 3.Build and Install OpenAirInterface (OAI)

