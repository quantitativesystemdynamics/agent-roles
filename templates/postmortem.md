# Postmortem: [Incident/Project Name]

**Document ID:** PM-[YYYY]-[Sequence]
**Status:** [Proposed / Review in Progress / Finalized]
**Facilitator:** [Role/Person]
**Date of Meeting:** [YYYY-MM-DD]

---

## 1. Executive Summary & Narrative
**Context:** [2-3 sentences: what was happening before the failure occurred.]

**Chronological Summary:**
[A high-level story of the incident. Describe the detection, the initial confusion, the key findings, the resolution, and the restoration of calm.]

**Impact Statement:**
- **Duration:** [Total outage time]
- **Severity Score:** [1-5 scale]
- **Users affected:** [% affected, duration of disruption]

---

## 2. Technical Root Cause Analysis (5 Whys)
**Problem Statement:** [The visible failure]

1. **Why?** [Immediate technical cause] → **A:** [Answer]
2. **Why?** [The cause of that cause] → **A:** [Answer]
3. **Why?** [Deeper logic failure] → **A:** [Answer]
4. **Why?** [Process or architectural gap] → **A:** [Answer]
5. **Why?** [The ultimate root cause] → **A:** [The formal technical/process root cause]

---

## 3. What Went Well (Lessons to Preserve)
**System Successes:**
- [e.g., "The fallback server activated in 2 seconds"]
- [e.g., "Automated backups were verified intact"]

**Process Successes:**
- [e.g., "The incident report scribe kept a perfect timeline"]
- [e.g., "Decision logs clearly documented the triage path"]

---

## 4. What Could Be Improved (Lessons to Learn)
**Technical Gaps:**
- [e.g., "Monitoring threshold was too low for the spike"]
- [e.g., "Secrets manager timeout during heavy load"]

**Operational Gaps:**
- [e.g., "Handoff took too long between timezones"]
- [e.g., "IC role was ambiguous during the first 10 minutes"]

---

## 5. Formal Corrective Actions (Next Steps)
| ID | Action Category | Specific Action | Owner | Due Date | Status |
|----|-----------------|-----------------|-------|----------|--------|
| A-1 | [Technical Fix] | [Detailed description of structural fix] | [Role] | [Date] | [Pending] |
| A-2 | [Monitoring] | [New alert or dashboard requirement] | [Role] | [Date] | [Pending] |
| A-3 | [Process] | [Playbook/Runbook update] | [Role] | [Date] | [Pending] |

---

## 6. Stakeholder Update Summary
**For [Stakeholder Group 1]:** [3-sentence summary of findings and fixes.]
**For [Stakeholder Group 2]:** [3-sentence summary of findings and fixes.]

---

## 7. Follow-up Review Schedule
- **30-day Review:** [Check on P0 action items]
- **60-day Review:** [Verify long-term stability]
- **90-day Closure:** [Formally close the postmortem]

---

## 8. Related Artifacts
- **Incident Report:** [Link to report file]
- **Decision Log:** [Link to any changes decided during PM]
- **Communication Log:** [Link to journal entry]

---

*Template version: 2026-03-02 | Grounded in Blameless Operations (AGENTS.md Section 12.6)*

