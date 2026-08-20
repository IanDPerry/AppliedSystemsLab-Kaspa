# Kaspa Mining Rigs – Power-Off Procedure (KS5L & KS5 Pro)

This SOP outlines the safe shutdown process for both the IceRiver KS5L and Bitmain KS5 Pro Kaspa miners. It includes pre-checks, PDU-based power-off steps, and post-event logging reminders.

---

## 1. Pre-Power-Off Checklist (All Rigs)

- Confirm mining activity is stable or paused  
- Check dashboard for:
  - Hash rate consistency  
  - Fan RPM within normal range  
  - No active error codes  
- Ensure no firmware updates are in progress  
- Notify lab team if shutdown affects shared pool performance

---

## 2. Power-Off Procedure

### IceRiver KS5L
- Locate the assigned PDU outlet (e.g., `C19-Outlet-04`)  
- Flip the **PDU switch to OFF**  
- Wait for all LEDs to turn off (L2 stops blinking)  
- Do **not** unplug the power cord unless necessary

### Bitmain KS5 Pro
- Locate the assigned PDU outlet(s)  
- Flip the **PDU switch to OFF**  
  - If using dual-input PSU, ensure both lines are switched off  
- Wait for dashboard to become unreachable and fans to stop  
- Do **not** unplug PSU cables unless required for maintenance

---

## 3. Post-Power-Off Reminder

After shutdown:
- Log the event in your maintenance log  
- Include rig ID, time, outlet ID, and reason for shutdown  
- Note any anomalies or irregular behavior  
- Update reliability tracking notes if applicable
