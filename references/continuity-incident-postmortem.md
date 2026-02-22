# Continuity Incident Postmortem (Human-Triggered)

Use this only when the human/operator explicitly calls a continuity incident.

## Definition of Done for Recovery
Recovery is not complete until all are true:
1. Postmortem section written
2. Regression/hack log references added
3. One preventive rule recorded
4. Postmortem status changed from OPEN -> CLOSED

## Workflow
- At split detection: create OPEN stub immediately.
- Before recovery execution: update stub with diagnosis/fix state.
- After recovery verification: complete fields and set CLOSED.

## Template

### Continuity Incident Postmortem — YYYY-MM-DD
- **Status:** OPEN | CLOSED
- **Incident window:**
- **Symptom (what failed):**
- **Human trigger prompt:**
- **Read-only snapshot:**
  - Current session (id/size/start):
  - Prior session (id/size/end):
  - Gateway status:
  - Log window notes:
- **Path chosen by human:**
  - A) Diagnose/fix first, recover later
  - B) Recover now
- **Triggering action/event:**
- **Root cause (1-2 lines):**
- **Fix applied:**
- **Verification result:**
- **Preventive rule (single sentence):**
- **Logged in:**
  - Regressions:
  - Hacks:
  - Behavioral log (if applicable):
- **Follow-up date:**
