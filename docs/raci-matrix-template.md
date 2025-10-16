# RACI Matrix Template

A RACI matrix clarifies roles and responsibilities for key project activities. Use this template to ensure everyone knows who is **Responsible** for doing the work, **Accountable** for the outcome, **Consulted** for input, and **Informed** of progress.

## RACI Definitions

- **R - Responsible**: Does the work to complete the task
- **A - Accountable**: Ultimately answerable for the completion and approval (only one A per activity)
- **C - Consulted**: Provides input and must be consulted before decisions or actions
- **I - Informed**: Kept up-to-date on progress, but not actively involved

---

## Project Initiation & Planning

| Activity | Product Manager | Project Manager | Developer | UX Designer | DevOps Engineer | Data Analyst | Customer Support |
|----------|----------------|-----------------|-----------|-------------|-----------------|--------------|------------------|
| Define problem statement & goals | **A/R** | C | C | C | - | C | I |
| Define success metrics | **A** | C | C | - | - | **R** | C |
| Create project charter | C | **A/R** | C | - | - | - | - |
| Initial scope & requirements | **A/R** | C | C | C | - | - | C |
| Resource planning | C | **A/R** | I | I | I | I | I |
| Risk assessment | C | **A/R** | C | - | C | - | - |
| Budget approval | **A** | R | - | - | - | - | - |

---

## Design & User Experience

| Activity | Product Manager | Project Manager | Developer | UX Designer | DevOps Engineer | Data Analyst | Customer Support |
|----------|----------------|-----------------|-----------|-------------|-----------------|--------------|------------------|
| User research | C | I | - | **A/R** | - | C | C |
| Create wireframes & mockups | C | I | C | **A/R** | - | - | - |
| Usability testing | C | I | C | **A/R** | - | - | C |
| Design system updates | C | I | C | **A/R** | - | - | - |
| Accessibility review | C | I | C | **A/R** | - | - | - |
| Design approval | **A** | I | C | R | - | - | - |

---

## Development & Implementation

| Activity | Product Manager | Project Manager | Developer | UX Designer | DevOps Engineer | Data Analyst | Customer Support |
|----------|----------------|-----------------|-----------|-------------|-----------------|--------------|------------------|
| Technical design | C | I | **A/R** | - | C | - | - |
| Code implementation | C | I | **A/R** | C | - | - | - |
| Unit testing | - | I | **A/R** | - | - | - | - |
| Code reviews | - | I | **A**/R | - | C | - | - |
| Documentation | C | I | **A/R** | C | - | - | C |
| Integration testing | C | I | **A/R** | - | C | - | - |
| Performance testing | C | I | R | - | **A** | - | - |
| Instrumentation & tracking | C | I | R | - | - | **A** | - |

*Note: For code reviews, the reviewer is Accountable for approval, original developer is Responsible for implementation.

---

## Infrastructure & Operations

| Activity | Product Manager | Project Manager | Developer | UX Designer | DevOps Engineer | Data Analyst | Customer Support |
|----------|----------------|-----------------|-----------|-------------|-----------------|--------------|------------------|
| Infrastructure setup | - | I | C | - | **A/R** | - | - |
| CI/CD pipeline configuration | - | I | C | - | **A/R** | - | - |
| Deployment to staging | - | I | C | - | **A/R** | - | - |
| Production deployment | C | C | I | - | **A/R** | - | - |
| Monitoring & alerting setup | - | I | C | - | **A/R** | - | - |
| Incident response | I | I | R | - | **A/R** | - | C |
| Security & compliance | C | I | C | - | **A/R** | - | - |
| Backup & disaster recovery | - | I | - | - | **A/R** | - | - |

---

## Data & Analytics

| Activity | Product Manager | Project Manager | Developer | UX Designer | DevOps Engineer | Data Analyst | Customer Support |
|----------|----------------|-----------------|-----------|-------------|-----------------|--------------|------------------|
| Define KPIs & metrics | **A** | I | - | - | - | R | - |
| Implement event tracking | C | I | R | - | - | **A** | - |
| Create dashboards | C | I | - | - | - | **A/R** | - |
| Analyze experiment results | **A** | I | - | C | - | R | - |
| Data quality validation | C | I | C | - | C | **A/R** | - |
| Insight reporting | **A** | I | - | - | - | R | - |

---

## Release & Launch

| Activity | Product Manager | Project Manager | Developer | UX Designer | DevOps Engineer | Data Analyst | Customer Support |
|----------|----------------|-----------------|-----------|-------------|-----------------|--------------|------------------|
| Release planning | **A** | R | C | - | C | - | C |
| Create release notes | R | C | C | - | - | - | C |
| Pre-release testing | C | C | **A/R** | C | C | - | - |
| Go/no-go decision | **A** | R | C | - | C | - | - |
| Production deployment | C | C | C | - | **A/R** | - | - |
| Post-deployment verification | C | I | R | - | **A** | - | - |
| Support documentation | C | R | C | - | - | - | **A** |
| Customer communication | **A/R** | C | - | - | - | - | C |

---

## Support & Maintenance

| Activity | Product Manager | Project Manager | Developer | UX Designer | DevOps Engineer | Data Analyst | Customer Support |
|----------|----------------|-----------------|-----------|-------------|-----------------|--------------|------------------|
| Customer inquiries | I | I | - | - | - | - | **A/R** |
| Bug triage | C | I | C | - | - | - | **A** |
| Bug investigation | C | I | **A/R** | - | C | - | C |
| Bug fixes | C | I | **A/R** | - | - | - | I |
| Knowledge base updates | C | I | C | - | - | - | **A/R** |
| Feature requests | **A** | I | - | - | - | - | R |
| Support metrics tracking | I | I | - | - | - | C | **A/R** |

---

## Project Closure & Retrospective

| Activity | Product Manager | Project Manager | Developer | UX Designer | DevOps Engineer | Data Analyst | Customer Support |
|----------|----------------|-----------------|-----------|-------------|-----------------|--------------|------------------|
| Impact measurement | **A** | I | - | - | - | R | I |
| Retrospective facilitation | C | **A/R** | I | I | I | I | I |
| Document lessons learned | C | **A/R** | C | C | C | C | C |
| Archive project documentation | C | **A/R** | I | I | I | I | I |
| Celebrate success | **A/R** | R | I | I | I | I | I |

---

## How to Use This Template

### For Project Managers
1. Copy this template at project kickoff
2. Review and adjust based on your team structure
3. Clarify any cells where accountability is unclear
4. Share with the team and get agreement
5. Reference during planning to ensure coverage

### For Team Members
1. Find your column to understand your responsibilities
2. Look for your "A" cells - you own these outcomes
3. Check your "R" cells - you do this work
4. Note your "C" cells - you'll be asked for input
5. Track your "I" cells - you'll receive updates

### Best Practices
- **One A per row**: Only one role should be Accountable for each activity
- **At least one R per row**: Someone must be Responsible for doing the work
- **Avoid too many C's**: Consult only those who truly need to provide input
- **Keep it updated**: Review quarterly or when team structure changes
- **Use for conflict resolution**: When unclear, refer back to the RACI

### Common Pitfalls to Avoid
- ❌ Multiple people Accountable (creates confusion)
- ❌ No one Accountable (work falls through cracks)
- ❌ Too many people Consulted (slows decisions)
- ❌ Not updating when roles change (becomes outdated)

---

## Customization Notes

This is a template. Customize it based on:
- Your team size and structure
- Project complexity and risk
- Organizational culture and decision-making style
- Phase of the project (early vs. late)

Remember: The goal is clarity and accountability, not bureaucracy. If a cell is empty (-), that's intentional - not every role needs to be involved in every activity.
