# Joseph P. Joseph

**AI-Assisted Support Automation | CI/CD Reliability | Python**

I build reliable support and operations workflows with Python, APIs, CI/CD,
human approval, and evidence-driven escalation.

My background combines enterprise technical support, Linux infrastructure,
incident ownership, and developer-platform troubleshooting. My public projects
use synthetic data and standalone implementations so I can demonstrate product
thinking and engineering practices without exposing employer or customer
information.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Joseph_P._Joseph-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/josephpjoseph/)

## Selected Projects

### [Runner Fleet Reliability Platform](https://github.com/jjoseph456/runner-fleet-reliability-platform)

A production-shaped SRE and developer-platform project for ephemeral GitHub
Actions runner fleets:

- OpenTofu configuration for a temporary AWS EKS lab
- Kubernetes, Helm, and Actions Runner Controller configuration
- Queue, startup, cleanup, and maximum-age SLOs
- Prometheus metrics and alert rules
- Capacity, cost, and incident evidence
- Read-only MCP tools for fleet inspection and recommendations
- Deterministic burst, capacity-loss, image-failure, and API-degradation tests

**Current status:** validated local and infrastructure scaffold; cloud
deployment evidence has not yet been captured.

### [Support Composer Assistant + Support Operations Agent](https://github.com/jjoseph456/support-composer-assistant)

A clean-room Zendesk editor with an opt-in Python agent service:

- Multi-step support analysis with registered knowledge and status tools
- Durable SQLite case memory and an auditable event history
- Clear separation of observations, hypotheses, and confirmed facts
- Human approval with stale-revision protection
- Deterministic and OpenAI-compatible providers
- Token, latency, and estimated-cost reporting
- API tests, 20 synthetic evaluations, Docker, CI, and a threat model

**Current status:** pilot-stage portfolio product; not yet validated with
production customer data or paying users.

### [Support Engineering Portfolio](https://github.com/jjoseph456/support-engineering-portfolio)

Tested Python tools and synthetic case-study patterns for:

- Evidence-led incident triage and next diagnostic steps
- Engineering-ready escalation quality checks
- Clear separation of observations, hypotheses, and root cause
- Incident communication, postmortems, and operational documentation

### [Linux Fleet Readiness](https://github.com/jjoseph456/linux-fleet-readiness)

A read-only Python CLI that converts Linux fleet inventory into repeatable
operational checks and guarded server-decommission plans:

- Patching, backup, monitoring, encryption, and OS-support readiness checks
- Explicit validation, prioritized findings, and JSON output
- Safety gates for approvals, dependencies, recovery evidence, and production
- Synthetic infrastructure data, unit tests, and CI-friendly exit codes

### [GitHub Actions Workflow Auditor](https://github.com/jjoseph456/github-actions-workflow-auditor)

A Python CLI for repeatable CI/CD security and reliability reviews:

- Least-privilege permissions and immutable action references
- Unsafe untrusted-input and privileged pull-request patterns
- Timeouts, concurrency, OIDC, and reusable-workflow boundaries
- Human-readable and JSON output for local checks and CI

## How I Work

- **Make the problem testable.** Start with immutable evidence, define the
  failure boundary, and distinguish facts from hypotheses.
- **Keep people in control.** Require explicit review before generated content
  changes a customer-facing workflow.
- **Build for reuse.** Convert recurring investigations into tested tools,
  small reproductions, and practical documentation.
- **Measure reliability.** Evaluate expected behavior, unsafe claims, latency,
  and cost rather than relying on a polished demonstration alone.
- **Improve the handoff.** Give engineering a focused question, the evidence
  needed to answer it, and a clear customer-impact statement.
- **Communicate uncertainty honestly.** A useful outcome can be a bounded next
  step, not a premature root-cause claim.

## Technical Focus

`Python` · `FastAPI` · `OpenTofu` · `Kubernetes` · `Helm` · `Prometheus` ·
`MCP` · `SLOs` · `GitHub Actions` · `CI/CD` · `Linux` · `Docker` · `APIs` ·
`Incident Response`

## Design-partner invitation

I am seeking three support or DevTools teams willing to review a controlled
pilot using synthetic or appropriately sanitized data. The goal is to measure
diagnostic-plan speed, reviewer edits, unsafe-claim rate, workflow completion,
and model cost. Contact me through LinkedIn if that matches your environment.

## Writing and Case Studies

- [Secure and Reliable GitHub Actions Workflows](https://github.com/jjoseph456/support-engineering-portfolio/blob/main/best-practices/github-actions-secure-reliable-workflows.md)
- [GitHub Enterprise Server Operational Readiness](https://github.com/jjoseph456/support-engineering-portfolio/blob/main/best-practices/ghes-operational-readiness.md)
- [GitHub Advanced Security Rollout and Operations](https://github.com/jjoseph456/support-engineering-portfolio/blob/main/best-practices/github-advanced-security-rollout.md)
- [From Symptom to Engineering-Ready Escalation](https://github.com/jjoseph456/support-engineering-portfolio/blob/main/docs/engineering-ready-escalations.md)
- [Synthetic Support Engineering Case Studies](https://github.com/jjoseph456/support-engineering-portfolio/blob/main/docs/synthetic-case-study-patterns.md)

> These are personal, unofficial projects. Public examples use synthetic data
> and do not contain employer source code, customer information, support-case
> data, or internal documentation.
