# Incident Report: [Incident Name]

**Incident ID:** INC-[YYYY-MM-DD]-[Sequence]
**Severity:** [Crit-1 / High-2 / Med-3 / Low-4]
**Status:** [Investigating / Identified / Monitoring / Mitigated / Resolved / Closed]
**Incident Commander:** [Role/Person]

---

## 1. Executive Summary
**Date & Time of Occurrence:** [YYYY-MM-DD HH:MM UTC]
**Duration:** [Total outage/impairment time]
**Impact Summary:** [2-3 sentences: what happened, service impact, user impact]

**The Core Failure:** [1-sentence technical definition of the problem]

---

## 2. Affected Systems & Stakeholders
**System Inventory:**
- **System A:** [e.g., Database cluster] — Status: [Compromised]
- **System B:** [e.g., API Gateway] — Status: [Functional]

**Stakeholder Impact:**
- **External Users:** [% affected, duration of disruption]
- **Internal Ops:** [Manual effort required]
- **Compliance:** [Potential PII breach or SLA violation?]

---

## 3. Timeline (All times UTC)
| Time | Event Description | Source / Evidence |
|------|-------------------|-------------------|
| HH:MM | [First anomalous metric/alert] | [Link to Grafana/Logs] |
| HH:MM | [Triage started] | [Agent ID/Scribe] |
| HH:MM | [Incident declared, IC assigned] | [Communication channel] |
| HH:MM | [Root cause identified] | [Findings/Trace] |
| HH:MM | [Mitigation deployed] | [Command run] |
| HH:MM | [Service metrics normalized] | [Verification tool] |
| HH:MM | [Full recovery confirmed] | [Final check] |

---

## 4. Root Cause Analysis (Technical)
**The Trigger:** [Specific action or event that initiated the failure]

**The Mechanics:** [Step-by-step description of the internal system failure path]

**The Gap:** [What control or monitoring failed to prevent this?]

---

## 5. Resolution & Mitigation
**Short-term Fix:** [Immediate action taken to restore service]

**Containment Strategy:** [How we ensured the failure didn't spread]

**Verification Method:** [Specific tests or queries used to confirm resolution]

---

## 6. Lessons Learned (Blameless Review)
**What worked well:**
- [e.g., "The secondary load balancer handled 40% of traffic"]
- [e.g., "The scribe captured the timeline perfectly"]

**What could be improved:**
- [e.g., "Monitoring threshold for CPU was too high"]
- [e.g., "Handoff between shift agents took 15 minutes"]

---

## 7. Mandatory Follow-up Action Items
| ID | Action Category | Action | Owner | Due Date | Status |
|----|-----------------|--------|-------|----------|--------|
| 1 | [Preventative] | [Description of structural fix] | [Role] | [Date] | [Pending] |
| 2 | [Detection] | [New monitoring rule/alert] | [Role] | [Date] | [Pending] |
| 3 | [Process] | [Runbook update] | [Role] | [Date] | [Pending] |

---

## 8. Related Artifacts
- **Postmortem:** [Link to postmortem file]
- **Decision Log:** [Link to any architectural changes decided during IR]
- **Communication Log:** [Link to Slack/Journal]

---

*Template version: 2026-03-02 | Grounded in Blameless Operations (AGENTS.md Section 12.6)*

