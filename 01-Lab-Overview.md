# Applied Systems Lab – Kaspa Mining Infrastructure Overview

## Purpose

The **Applied Systems Lab** serves as a test environment for research, tuning, and reliability evaluation of **Kaspa (KAS) mining systems**.  
Its focus is on **hardware optimization**, **system performance**, and **operational resilience**, using open-source monitoring and structured experimental methodology.

---

## Objectives

The lab was decommissioned before every objective below reached completion; each is noted with its actual status.

1. **Monitor Mining Performance**
   - Tracked hash rate, uptime, and per-rig health for **Iceriver KS5L** and **Bitmain KS5 Pro** miners via F2Pool and each miner's local web interface.
   - Formal hash-per-watt tuning and pool-side parameter experimentation were planned but not carried out before the project ended.

2. **Reliability & Uptime Tracking**
   - Informally tracked uptime and downtime incidents per rig using F2Pool data and external temperature-probe alerts.
   - A formal **MTBF**/**MTTR** metrics framework was planned but never implemented before decommissioning.

3. **Standardize Operational SOPs**
   - Maintained reproducible **startup, shutdown, and maintenance procedures** (documented in this repository).
   - Diagnostics and troubleshooting checklists were developed for field consistency.

4. **Cooling & Environmental Management**
   - Operated a DIY cooling setup built around a two-panel window: a window-mounted A/C unit on one panel and a shutter exhaust fan on the other, sealed with insulation foam board. The rig rack pulled cold air from the A/C intake and exhausted hot air out through the shutter fan.

---

## Infrastructure Summary

| Component Type | Description | Notes |
|----------------|--------------|-------|
| **Mining Rigs** | Iceriver KS5L & Bitmain KS5 Pro | Dedicated Kaspa ASICs; decommissioned and sold following project completion |
| **Monitoring Stack** | F2Pool dashboard, per-rig local web GUI, ICERIVER monitoring tool, external temperature probes | F2Pool provided individual and combined (24hr) hash rate, daily revenue, and offline detection (~10 min delay); per-rig web GUI used for hashboard avg temp and runtime; ICERIVER tool used for individual chip-level temps on the KS5L; external temperature probes used to help identify offline incidents |
| **Power Systems** | 240V line with surge-protected PDUs | PDUs had per-outlet trip switches and a real-time voltage/amp consumption display; no remote or networked PDU monitoring |
| **Cooling Setup** | DIY window-mounted setup | Two-panel window: A/C unit on one panel, shutter exhaust fan on the other, sealed with insulation foam board; rack pulled cold air from the A/C side and exhausted hot air through the fan side |
| **Networking** | Direct connection to F2Pool | Optimized for low latency and link reliability |

---

## Reliability & Maintenance Framework

The lab intended to build a structured **reliability framework** to quantify performance and system resilience, but this was not finalized before decommissioning:

- **MTBF (Mean Time Between Failures):** Planned metric to estimate average operational lifespan between outages; not formally implemented.
- **MTTR (Mean Time To Repair):** Planned metric to track recovery duration after downtime; not formally implemented.
- **Uptime Tracking:** Based on F2Pool data, per-rig web GUI checks, and external temperature-probe alerts.
- **Failure Mode Categorization:** Distinguished between hardware, network, and environmental faults on an ad hoc basis.
  
---

## Methodology

1. **Experimentation** – Controlled operational testing of cooling, configuration, and environmental variables.  
2. **Data Collection** – Aggregated from **F2Pool** and **open-source monitoring**.  
3. **Analysis** – Efficiency, stability, and reliability assessments from external data.  
4. **Documentation** – Version-controlled SOPs and findings maintained in this repository.

---



---

