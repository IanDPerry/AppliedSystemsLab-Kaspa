# IceRiver KS5L – New User Initialization

This SOP guides first-time setup for the IceRiver KS5L Kaspa miner. It covers inspection, power/network setup, configuration, and safety protocols.

---

## 1. Physical Inspection
- Check for damage to chassis, fans, and cables  
- Ensure airflow paths are clear  
- Confirm ambient temperature < 35°C and humidity < 90%  
- Verify power input: 180–285V AC, 50–60Hz

---

## 2. Power & Network Setup
- Connect Ethernet cable  
- Plug in power cord  
- LED behavior:
  - Boot: red and green steady
  - Success: L2 blinks, others off

---

## 3. Web Interface Access
- Use IP scanner to find miner  
- Login: `admin` / `12345678`  
- Change password  
- Configure pool and wallet  
- Save and reboot via interface

---

## 4. Firmware & Updates
- Check IceRiver site for latest firmware  
- Update only when stable  
- Avoid power-off during update

---

## 5. Power Cord & PDU Setup
- **Cord Type:** IEC320-C19 Female, 16A, rated up to 230V  
- **PDU Used:** Surge-protected PDU with individual per-outlet trip switches and a real-time voltage/amp consumption display (no remote or networked monitoring)  
- **Setup Tip:** Use labeled ports and log rig-to-outlet mapping for diagnostics

---

## 6. Logging
- Record setup time, firmware version, pool config  
- Note any errors or anomalies
