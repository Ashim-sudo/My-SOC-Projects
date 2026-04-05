# 08 - Windows Logging for SOC

## What I Learned
- Importance of Windows Event Logs in SOC
- Main Windows Event Logs:
  - Security Log (most important for security)
  - System Log
  - Application Log
- How to view and filter events using Event Viewer
- Common suspicious events (failed logins, privilege escalation, new user creation, etc.)
- Event IDs that SOC analysts commonly look for

## Key Takeaways
- Understood that Windows Security Log is the most valuable for detecting attacks
- Learned how to find suspicious login attempts, account changes, and service creations
- Realized the difference between Linux and Windows logging

## Most Important Event IDs Learned
- 4624 → Successful Logon
- 4625 → Failed Logon
- 4720 → User Account Created
- 4672 → Special Privileges Assigned

## Tools / Concepts Covered
- Windows Event Logs
- Event Viewer
- Security Auditing
- Common Attack Detection in Windows

---
