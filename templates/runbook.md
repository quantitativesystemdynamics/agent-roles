# Runbook: [Procedure Name]

**Document ID:** RUN-[Category]-[Sequence]
**Version:** [e.g., v1.0]
**Owner:** [Role/Team with authority to modify]
**Status:** [Stable / Under Review / Experimental]
**Last Verified:** [YYYY-MM-DD]

---

## 1. Goal & Objectives
**Goal:** [What this runbook achieves in 1-2 sentences.]

**Objective 1:** [Operational outcome]
**Objective 2:** [Security or reliability outcome]

---

## 2. Preconditions & Checklists
**Before starting:**
- [ ] [Requirement 1: e.g., VPN connection active]
- [ ] [Requirement 2: e.g., Write access to /your-org]
- [ ] [Input data validated via orientation.md standards]

**Authorized Role(s):** [Role A / Role B / Role C]

---

## 3. High-Fidelity Procedure (Step-by-Step)

### Step 1: [Step Name]
**Action/Command:**
```bash
# [Purpose of command]
[exact command to run]
```

**Expected Result/Output:**
```
[Success indicator]
```

**Troubleshooting Step 1:**
- **If failure occurs:** [Specific corrective action]
- **If timeout occurs:** [Specific corrective action]

---

### Step 2: [Step Name]
**Action/Command:**
```bash
# [Purpose of command]
[exact command to run]
```

**Expected Result/Output:**
```
[Success indicator]
```

**Rollback Command:**
```bash
# [Purpose of rollback]
[exact command to revert Step 2]
```

---

## 4. Verification & Validation
**Post-Procedure Checks:**
- [ ] [Check A: e.g., Service metric X is within normal range]
- [ ] [Check B: e.g., Logs have been produced and stored]
- [ ] [Verification query: `SELECT count(*) FROM table WHERE status='done'`]

---

## 5. Escalation Procedure
**Crisis Trigger:** [The point at which this runbook should be aborted and an Incident Report initiated.]

**Escalation Path:**
1. **[Primary Contact Role]:** [Contact Info/Channel] — **Response Time:** [< 15 mins]
2. **[Secondary Contact Role]:** [Contact Info/Channel]

---

## 6. Artifacts Produced
- **[Log File]:** [Path/Storage] — **Retention:** [Permanent]
- **[Snapshot]:** [Path/Storage] — **Retention:** [Ephemeral]

---

## 7. Quality Gate (DoD)
**Definition of Done:**
- [ ] [Criterion 1: Procedure fully completed]
- [ ] [Criterion 2: All verification checks passed]
- [ ] [Criterion 3: Stakeholders notified]

**Failure Detection Metrics:** [How we identify if the runbook caused a regression.]

---

*Template version: 2026-03-02 | Grounded in High-Fidelity Schema (orientation.md)*

