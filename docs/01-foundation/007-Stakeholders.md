# Stakeholders

| Document Information | |
|----------------------|------------------------------------------------|
| **Document ID** | FDN-007 |
| **Document Name** | Stakeholders |
| **Version** | 1.0.0 |
| **Status** | Draft |
| **Project** | BhoomiAI – AI-Native Agriculture Intelligence Platform |
| **Owner** | Kamalsankar |
| **Last Updated** | 2026-06-30 |

---

# 1. Purpose

This document identifies all stakeholders involved in BhoomiAI and defines their responsibilities, expectations, and level of involvement.

Stakeholders include individuals, teams, and organizations that influence or are affected by the platform.

---

# 2. Stakeholder Objectives

The stakeholder model ensures:

- Clear responsibilities
- Better communication
- Proper access control
- Accurate requirements
- Scalable governance

---

# 3. Primary Stakeholders

## Project Owner

Current

- Kamalsankar

Responsibilities

- Product vision
- Product roadmap
- Feature approval
- Final decision maker
- Architecture approval

---

## Farm Owner

Responsibilities

- Farm configuration
- Business decisions
- Financial approvals
- Performance monitoring

Needs

- Dashboard
- Reports
- Financial overview
- AI insights

---

## Farm Manager

Responsibilities

- Daily operations
- Task assignment
- Worker supervision
- Crop planning
- Livestock management

Needs

- Planning tools
- Notifications
- Reports
- Mobile access

---

## Supervisor

Responsibilities

- Monitor daily work
- Verify completed tasks
- Record field observations

Needs

- Task management
- Mobile application
- Offline support

---

## Worker

Responsibilities

- Execute assigned tasks
- Record completed work
- Capture photos
- Update progress

Needs

- Simple mobile interface
- Local language support
- Offline capability

---

# 4. Secondary Stakeholders

## Accountant

Responsibilities

- Expenses
- Income
- Budget
- Financial reporting

---

## Inventory Manager

Responsibilities

- Purchase
- Stock
- Warehouse
- Material issue

---

## Veterinarian

Responsibilities

- Goat health
- Vaccination
- Medical records
- Disease tracking

---

## Agronomist

Responsibilities

- Crop planning
- Fertilizer recommendations
- Pest management

---

# 5. Technical Stakeholders

## System Administrator

Responsibilities

- User management
- Backup
- Security
- Configuration

---

## Developer

Responsibilities

- Platform development
- Bug fixes
- Feature implementation

---

## Solution Architect

Responsibilities

- Platform architecture
- Standards
- Technical review

---

## AI Engineer

Responsibilities

- AI agents
- Prompt engineering
- Knowledge base
- AI evaluation

---

# 6. External Stakeholders

Future integrations may involve:

- Weather providers
- SMS gateways
- WhatsApp services
- Government portals
- GIS providers
- IoT device vendors
- Financial institutions

---

# 7. Stakeholder Matrix

| Stakeholder | Interest | Influence |
|-------------|----------|-----------|
| Project Owner | High | High |
| Farm Owner | High | High |
| Farm Manager | High | Medium |
| Supervisor | Medium | Medium |
| Worker | Medium | Low |
| Accountant | Medium | Medium |
| Developer | High | High |
| AI Engineer | High | Medium |

---

# 8. Permissions Overview

| Role | Read | Create | Update | Delete | Approve |
|------|------|--------|--------|--------|---------|
| Project Owner | ✔ | ✔ | ✔ | ✔ | ✔ |
| Farm Owner | ✔ | ✔ | ✔ | Limited | ✔ |
| Farm Manager | ✔ | ✔ | ✔ | Limited | Limited |
| Supervisor | ✔ | ✔ | ✔ | ✖ | ✖ |
| Worker | Assigned Data | Assigned Data | Assigned Data | ✖ | ✖ |

Detailed permissions will be defined later in the Authorization documentation.

---

# 9. AI Interaction

AI agents will assist stakeholders based on their permissions.

Examples:

- Farm Owner → Business insights
- Farm Manager → Task recommendations
- Worker → Daily task guidance
- Veterinarian → Health summaries
- Agronomist → Crop recommendations

AI must respect user permissions and never expose unauthorized information.

---

# 10. Related Documents

- FDN-003 – Project Charter
- FDN-006 – Scope
- FDN-008 – Success Metrics
- Platform Authorization Design (Future)

---

# 11. Change History

| Version | Date | Description |
|---------|------|-------------|
| 1.0.0 | 2026-06-30 | Initial Stakeholders document |

---

# Approval

| Role | Name | Status |
|------|------|--------|
| Project Owner | Kamalsankar | Pending |
| Solution Architect | Kamalsankar | Pending |

---

**Next Document:** FDN-008 – Success Metrics