# Propel Labs — propel-ai Organization

Repository index organized by customer and product line.

**Quick filters:**
- [Production repos](https://github.com/propel-ai?q=topic:production) — all active work
- [Archived repos](https://github.com/propel-ai?q=topic:archived) — reference/POC/legacy

---

## Novamera

| Repo | Type | Description |
|------|------|-------------|
| [novamera.svc-gpr](https://github.com/propel-ai/novamera.svc-gpr) | Service | GPR Processor — ECS Fargate worker + API + Sync Lambda |
| [novamera.fe-gpr-dashboard](https://github.com/propel-ai/novamera.fe-gpr-dashboard) | Frontend | GPR Dashboard — React + Vite SPA |
| [novamera.svc-qc](https://github.com/propel-ai/novamera.svc-qc) | Service | QC Checker — Lambda SQS worker |
| [novamera.lib-qc](https://github.com/propel-ai/novamera.lib-qc) | Library | QC algorithms — Python package |
| [novamera.svc-datahub](https://github.com/propel-ai/novamera.svc-datahub) | Service | DataHub Backend — Express + TypeScript + PostgreSQL |
| [novamera.fe-datahub](https://github.com/propel-ai/novamera.fe-datahub) | Frontend | DataHub Frontend — React + Vite |
| [novamera.svc-comms-portal](https://github.com/propel-ai/novamera.svc-comms-portal) | Service | Comms Portal — geological EDMS |
| [novamera.svc-borehole-labelling](https://github.com/propel-ai/novamera.svc-borehole-labelling) | Service | Borehole Labelling backend |
| [novamera.fe-borehole-labelling](https://github.com/propel-ai/novamera.fe-borehole-labelling) | Frontend | Borehole Labelling UI |
| [novamera.svc-sim](https://github.com/propel-ai/novamera.svc-sim) | Service | SIM Backend — field device mock API |
| [novamera.fe-sim](https://github.com/propel-ai/novamera.fe-sim) | Frontend | SIM Frontend — React |
| [novamera.fe-ncu](https://github.com/propel-ai/novamera.fe-ncu) | Frontend | Nova Control Unit frontend |
| [novamera.ncu-sim](https://github.com/propel-ai/novamera.ncu-sim) | Infrastructure | NCU + mock QA Docker Compose environment |
| [novamera.theme](https://github.com/propel-ai/novamera.theme) | Design System | Novamera component library + design tokens |
| [novamera.infra-iac](https://github.com/propel-ai/novamera.infra-iac) | Infrastructure | Terraform/CDK for AWS deployment |
| [novamera.roadmap](https://github.com/propel-ai/novamera.roadmap) | Reference | Internal roadmap artifacts |
| [novamera.developer](https://github.com/propel-ai/novamera.developer) | Reference | Local development environment setup |

**Archived:** [novamera.svc-ncs](https://github.com/propel-ai/novamera.svc-ncs) (reference copy), [novamera.orebody-anim](https://github.com/propel-ai/novamera.orebody-anim), [novamera.poc-*](https://github.com/propel-ai?q=topic:archived+novamera.poc) (6 POCs)
- `novamera.svc-nsd` (Spencer's Nov 2025 POC, unmaintained)

---

## Propel Internal

| Repo | Type | Description |
|------|------|-------------|
| [propel.scenarios](https://github.com/propel-ai/propel.scenarios) | Knowledge Base | Holdout scenario store for AI-Native Software Factory |
| [propel-gtm](https://github.com/propel-ai/propel-gtm) | Tools | GTM toolkit — artifacts and mini apps |
| [propel.ai-agents](https://github.com/propel-ai/propel.ai-agents) | Infrastructure | AI agent framework |
| [propel.ai-generator](https://github.com/propel-ai/propel.ai-generator) | Tools | Code generator for agents |
| [propel.docs-knowledge-base](https://github.com/propel-ai/propel.docs-knowledge-base) | Knowledge Base | Internal documentation |
| [propel.poc-design-system](https://github.com/propel-ai/propel.poc-design-system) | Reference | Design system spec generation POC |

---

## Other Customers

| Repo | Type | Description |
|------|------|-------------|
| [prople.investors_dd](https://github.com/propel-ai/prople.investors_dd) | Product | Investor Due Diligence Platform — Prople Labs |
| [ip-transferability-dashboard](https://github.com/propel-ai/ip-transferability-dashboard) | Tool | Novamera IP Transferability Analysis Agent |

---

## Naming Convention

Repos follow the pattern: `<customer>.<type>-<name>`

- `novamera.*` — Novamera customer repos
- `propel.*` — Propel Labs internal repos
- `prople.*` — Prople Labs customer repos
- `<customer>.*` — future customer repos

**Topics:** Every repo is tagged with `production` or `archived`. Novamera repos also tagged with `customer:novamera`, `prd:*`, etc. for discovery.

**For details:** See [novamera repo registry](https://github.com/propel-ai/propel.scenarios/blob/main/customers/novamera/repos.md) in propel.scenarios.
