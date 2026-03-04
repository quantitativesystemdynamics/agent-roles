# Agent Roles

> **IMPORTANT: Start with `orientation.md`** — Before assigning any roles, read `orientation.md` first. It provides the critical context for how to properly select and implement roles for AI agents. This is the fundamental key to using this library effectively.

A comprehensive, role-based protocol library for AI agent collaboration. This library provides 194 distinct roles organized by domain, enabling AI agents to adopt specific professional personas with clear purposes, responsibilities, and deliverables.

## What Is This?

This is a **role-based collaboration framework** for AI agents. Instead of treating AI as a generic assistant, you assign it a specific professional role—security engineer, compliance manager, product counsel, etc.—with defined boundaries, expertise areas, and operational protocols.

**Who is this for?**
- Developers using AI coding assistants (Claude, ChatGPT, Cursor, etc.)
- Teams building AI agents or autonomous systems
- Organizations implementing AI governance frameworks
- Anyone wanting structured AI collaboration

---

> **IMPORTANT:** Read `orientation.md` before using this library. It explains how to properly orient an AI agent to a specific role.

## Quick Start

### Option 1: Reference a Specific Role File

Direct your AI to read `orientation.md` first, then select a specific role:

```
Read ./agent-roles/orientation.md first, then use the security-engineer role defined in ./agent-roles/security/security-engineer.md
```

### Option 2: Include in Your Agents.md or Context File

Add this to your `AGENTS.md`, `claude.md`, or similar configuration:

```markdown
## Role Selection Protocol

Before executing substantive work, read `orientation.md` first.
This will provide the critical context for role selection and implementation.
```



### Option 3: Add as a Skill

Copy the `agent-roles` directory to your AI's skills or context directory:

```bash
cp -r agent-roles/ ~/your-ai-config/skills/
```

Then read orientation.md first:

```
Read ./agent-roles/orientation.md first, then select an appropriate role for this task.
```

---

## Role Library Overview

### Executive & Strategy (11 roles)
| Role | Purpose |
|------|---------|
| `ceo-strategist` | Sets organizational vision, strategic direction, and resource allocation priorities |
| `chief-of-staff` | Operating rhythm architect and cross-functional coordinator for executive leadership |
| `executive-communications` | Crafts calibrated messaging for internal and external executive communications |
| `strategy-analyst` | Conducts market analysis and competitive intelligence |
| `strategic-planning-lead` | Orchestrates annual/quarterly planning cycles |
| `org-systems-designer` | Designs organizational structures and accountability systems |
| `operating-rhythm-designer` | Optimizes meeting cadence and decision forums |
| `partnerships-executive` | Develops and manages strategic external partnerships |
| `investor-relations` | Manages communications with the investment community |
| `corporate-development` | Leads M&A and strategic transactions |
| `board-secretary` | Governance officer for board operations |

### Governance & Oversight (14 roles)
| Role | Purpose |
|------|---------|
| `security-governance-lead` | Oversees information security governance framework |
| `privacy-officer` | Accountability for global privacy program |
| `compliance-program-owner` | Operates compliance management program |
| `policy-author` | Develops and maintains organizational policies |
| `business-continuity-owner` | Ensures organizational resilience |
| `internal-controls-lead` | Designs internal control framework |
| `enterprise-risk-manager` | Operates enterprise risk management |
| `audit-liaison` | Primary interface for audits |
| `ethics-officer` | Operates ethics and integrity program |
| `decision-rights-steward` | Maintains decision authority framework |
| `model-risk-manager` | Governs AI and decision-making model risks |
| `safety-governance` | Oversees workplace health and safety |
| `records-retention-manager` | Manages records retention lifecycle |

### Legal & Contracts (19 roles)
| Role | Purpose |
|------|---------|
| `general-counsel` | Chief legal strategist and risk officer |
| `commercial-contracts-counsel` | Negotiates commercial agreements |
| `product-counsel` | Legal guidance throughout product lifecycle |
| `privacy-counsel` | Ensures privacy law compliance |
| `regulatory-counsel` | Navigates regulatory landscapes |
| `ip-counsel` | Protects patents, trademarks, copyrights |
| `patent-strategist` | Develops patent portfolios |
| `trademark-manager` | Protects trademark portfolio |
| `licensing-specialist` | Manages IP licensing |
| `open-source-compliance` | Manages open source compliance |
| `litigation-manager` | Oversees litigation and disputes |
| `employment-counsel` | Employer-employee legal matters |
| `terms-of-service-curator` | Maintains customer-facing agreements |
| `export-controls-counsel` | Ensures export regulation compliance |
| `legal-operations` | Optimizes legal function efficiency |
| `legal-researcher` | Conducts legal research and analysis |
| `paralegal` | Document preparation and administrative support |
| `contract-lifecycle-manager` | Oversees contract lifecycle |
| `policy-and-government-affairs` | Government relations |

### Finance & Accounting (17 roles)
| Role | Purpose |
|------|---------|
| `controller` | Chief accounting officer |
| `fp-and-a-analyst` | Financial analysis and forecasting |
| `accounting-ops` | Day-to-day accounting transactions |
| `revenue-recognition-analyst` | Ensures ASC 606/GAAP compliance |
| `tax-specialist` | Tax compliance and planning |
| `treasury-manager` | Cash and liquidity management |
| `unit-economics-analyst` | CAC, LTV, profitability analysis |
| `pricing-analyst` | Pricing strategy analysis |
| `financial-systems-admin` | ERP and financial systems |
| `billing-and-collections` | Invoicing and accounts receivable |
| `receivables-specialist` | Customer account records |
| `payables-specialist` | Vendor invoice processing |
| `procurement-finance` | Financial aspects of purchasing |
| `payroll-specialist` | Payroll processing |
| `expense-auditor` | Business expenditure validation |
| `grant-and-funding-analyst` | Grant financial compliance |
| `fraud-analyst` | Financial fraud detection |

### IT & Identity (9 roles)
| Role | Purpose |
|------|---------|
| `systems-admin` | Server and infrastructure management |
| `network-admin` | LAN, WAN, internet connectivity |
| `identity-admin` | IAM, SSO, user accounts |
| `endpoint-management` | Laptop and device lifecycle |
| `saas-admin` | SaaS application management |
| `device-provisioning` | End-user computing deployment |
| `asset-inventory-admin` | IT asset records |
| `it-support` | L2/L3 technical support |
| `helpdesk-triage` | First-line support routing |

### Reliability & SRE (9 roles)
| Role | Purpose |
|------|---------|
| `sre` | Applies engineering to service reliability |
| `observability-engineer` | Metrics, logs, tracing systems |
| `release-reliability` | Code transition to production |
| `infrastructure-maintainer` | Physical and virtual substrate |
| `capacity-planner` | Infrastructure scaling |
| `performance-engineer` | Responsiveness and efficiency |
| `chaos-engineer` | Fault injection testing |
| `oncall-coordinator` | On-call rotation management |
| `incident-communications` | Disruption communications |

### Security (16 roles)
| Role | Purpose |
|------|---------|
| `security-architect` | Global security blueprint |
| `security-engineer` | Security controls deployment |
| `application-security` | SDLC security integration |
| `cloud-security-engineer` | Cloud-native security |
| `iam-engineer` | Identity lifecycle and access |
| `threat-modeler` | Design-phase threat identification |
| `secure-code-reviewer` | Source code vulnerability analysis |
| `vulnerability-manager` | Vulnerability lifecycle |
| `incident-responder` | Security incident investigation |
| `forensics-analyst` | Digital evidence analysis |
| `red-teamer` | Adversarial simulations |
| `blue-teamer` | Defensive posture improvement |
| `secrets-manager` | Credential lifecycle |
| `bug-bounty-triage` | External vulnerability reports |
| `security-awareness` | Security culture training |

### Trust & Safety (8 roles)
| Role | Purpose |
|------|---------|
| `trust-and-safety-lead` | Community guidelines oversight |
| `content-policy-specialist` | Content guidelines translation |
| `user-safety-analyst` | Proactive safety assessments |
| `abuse-investigator` | Anomalous activity analysis |
| `fraud-and-spam-analyst` | Deceptive activity mitigation |
| `moderation-ops` | Day-to-day content enforcement |
| `crisis-response` | High-impact safety incidents |
| `contractor` | High-volume moderation support |

### People & Culture (16 roles)
| Role | Purpose |
|------|---------|
| `head-of-people` | People function leadership |
| `hr-generalist` | Versatile HR support |
| `recruiter` | Talent attraction and hiring |
| `talent-sourcer` | Passive talent identification |
| `onboarding-specialist` | New hire experience |
| `learning-and-development` | Training program design |
| `performance-coach` | Manager coaching support |
| `culture-steward` | Organizational values |
| `employee-relations` | Conflict and investigation management |
| `org-design-specialist` | Structural analysis |
| `workforce-planning` | Talent need forecasting |
| `internal-mobility-manager` | Internal career moves |
| `compensation-analyst` | Pay and equity programs |
| `benefits-admin` | Benefits program administration |
| `hr-analytics` | People data analysis |
| `dei-program-manager` | Diversity and inclusion |

### Operations (12 roles)
| Role | Purpose |
|------|---------|
| `incident-commander` | Critical disruption coordination |
| `ops-generalist` | Versatile operational support |
| `change-manager` | Structural modification governance |
| `process-engineer` | Workflow optimization |
| `knowledge-manager` | Intellectual capital curation |
| `documentation-engineer` | Documentation-as-Code |
| `session-scribe` | Narrative and operational memory |
| `quality-systems-manager` | Quality standards oversight |
| `vendor-ops` | Third-party partnerships |
| `automation-architect` | Cross-project automation |
| `business-continuity-planner` | Disaster recovery |
| `operations-analytics` | Operational insights |

### Data Privacy (4 roles)
| Role | Purpose |
|------|---------|
| `data-lineage-analyst` | Personal data journey mapping |
| `data-protection-impact-assessor` | GDPR Article 35 assessments |
| `privacy-engineer` | Technical privacy implementation |
| `subject-rights-handler` | DSR fulfillment |

### Compliance (10 roles)
| Role | Purpose |
|------|---------|
| `compliance-manager` | Enterprise-wide compliance coordination |
| `gdpr-program-lead` | GDPR compliance leadership |
| `hipaa-program-lead` | HIPAA compliance leadership |
| `pci-program-lead` | PCI DSS compliance leadership |
| `iso27001-lead` | ISO/IEC 27001:2022 implementation |
| `soc2-lead` | SOC 2 program management |
| `vendor-risk-manager` | Third-party risk assessment |
| `export-controls-coordinator` | Export compliance |
| `sanctions-screening` | OFAC/ sanctions compliance |
| `risk-control-tester` | Control effectiveness verification |

### Weird but Useful (39 roles)
Specialized cognitive roles for specific challenges:

- `ambiguity-killer` — Eliminates vague language
- `assumptions-auditor` — Identifies implicit assumptions
- `assumption-stress-tester` — Tests assumptions under pressure
- `cognitive-bias-catcher` — Detects thinking flaws
- `complexity-translator` — Bridges technical and stakeholder understanding
- `conflict-mediator` — Resolves interpersonal conflicts
- `consensus-builder` — Guides groups to genuine agreement
- `contradiction-detector` — Identifies logical inconsistencies
- `contrarian-reviewer` — Challenges prevailing views
- `dependency-cartographer` — Maps interdependence webs
- `devil-advocate` — Argues opposite position
- `edge-case-hunter` — Identifies boundary conditions
- `failure-mode-engineer` — Applies FMEA thinking
- `glossary-curator` — Maintains authoritative terminology
- `incident-poet` — Crafts post-incident narratives
- `launch-referee` — Impartial launch readiness decision
- `meeting-facilitator` — Guides productive meetings
- `meeting-summarizer` — Distills meeting content
- `metaphor-engineer` — Designs explanatory analogies
- `narrative-debugger` — Fixes project story inconsistencies
- `operationalizer` — Transforms goals into steps
- `postmortem-facilitator` — Guides blameless reviews
- `prompt-forensics` — Analyzes AI prompts
- `question-smith` — Crafts insightful questions
- `requirements-linter` — Analyzes requirements quality
- `requirements-triangulator` — Reconciles conflicting needs
- `risk-whisperer` — Articulates quiet concerns
- `rubber-duck-debugger` — Enables problem-solving through listening
- `sanity-checker` — Provides common-sense reality checks
- `scope-bouncer` — Protects project boundaries
- `scribe-of-record` — Creates durable records
- `second-brain-curator` — Organizes knowledge systems
- `simplifier` — Strips non-essentials
- `spec-lawyer` — Analyzes specifications precisely
- `stakeholder-empath` — Represents overlooked perspectives
- `terminology-guardian` — Enforces consistent terms
- `timebox-enforcer` — Protects time boundaries
- `tone-calibrator` — Adjusts communication tone
- `changelog-surgeon` — Crafts user-focused changelogs

---

## File Structure

```
agent-roles/
├── compliance/           # Regulatory compliance roles
├── data-privacy/        # Privacy engineering roles
├── executive/           # C-suite and strategy roles
├── finance/             # Finance and accounting roles
├── governance/          # Governance and oversight roles
├── it/                  # IT operations roles
├── legal/               # Legal and contracts roles
├── operations/          # Operational support roles
├── people/              # HR and culture roles
├── reliability/         # SRE and reliability roles
├── security/            # Security engineering roles
├── trust-and-safety/   # Content moderation roles
├── weird-but-useful/    # Specialized cognitive roles
├── templates/           # Documentation templates
├── orientation.md       # Role selection guide
└── role-template.md     # Template for new roles
```

---

## Creating a New Role

Use `role-template.md` as a starting point. Each role file should include:

1. **Role name** — Canonical identifier (e.g., `security-engineer`)
2. **Purpose** — One sentence on what this role achieves
3. **Domain** — Primary area of responsibility
4. **Key responsibilities** — 5-10 core duties
5. **Deliverables** — Tangible outputs
6. **Cross-role relationships** — Dependencies and interfaces
7. **Decision authority** — What this role can decide independently

---

## License

This project is provided as a framework. Customize and use it as needed for your organization.

---

## Contributing

When adding new roles:
1. Use `role-template.md` as the template
2. Place in the appropriate domain directory
3. Follow the naming convention: `kebab-case.md`
4. Include a clear **Purpose** statement in the first 50 lines

---

*Build as if the next reader is a colleague you respect. Because they are.*
