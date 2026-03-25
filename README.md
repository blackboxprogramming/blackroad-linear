<!-- BlackRoad SEO Enhanced -->

# ulackroad linear

> Part of **[BlackRoad OS](https://blackroad.io)** — Sovereign Computing for Everyone

[![BlackRoad OS](https://img.shields.io/badge/BlackRoad-OS-ff1d6c?style=for-the-badge)](https://blackroad.io)
[![BlackRoad Forge](https://img.shields.io/badge/Org-BlackRoad-Forge-2979ff?style=for-the-badge)](https://github.com/BlackRoad-Forge)
[![License](https://img.shields.io/badge/License-Proprietary-f5a623?style=for-the-badge)](LICENSE)

**ulackroad linear** is part of the **BlackRoad OS** ecosystem — a sovereign, distributed operating system built on edge computing, local AI, and mesh networking by **BlackRoad OS, Inc.**

## About BlackRoad OS

BlackRoad OS is a sovereign computing platform that runs AI locally on your own hardware. No cloud dependencies. No API keys. No surveillance. Built by [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc), a Delaware C-Corp founded in 2025.

### Key Features
- **Local AI** — Run LLMs on Raspberry Pi, Hailo-8, and commodity hardware
- **Mesh Networking** — WireGuard VPN, NATS pub/sub, peer-to-peer communication
- **Edge Computing** — 52 TOPS of AI acceleration across a Pi fleet
- **Self-Hosted Everything** — Git, DNS, storage, CI/CD, chat — all sovereign
- **Zero Cloud Dependencies** — Your data stays on your hardware

### The BlackRoad Ecosystem
| Organization | Focus |
|---|---|
| [BlackRoad OS](https://github.com/BlackRoad-OS) | Core platform and applications |
| [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc) | Corporate and enterprise |
| [BlackRoad AI](https://github.com/BlackRoad-AI) | Artificial intelligence and ML |
| [BlackRoad Hardware](https://github.com/BlackRoad-Hardware) | Edge hardware and IoT |
| [BlackRoad Security](https://github.com/BlackRoad-Security) | Cybersecurity and auditing |
| [BlackRoad Quantum](https://github.com/BlackRoad-Quantum) | Quantum computing research |
| [BlackRoad Agents](https://github.com/BlackRoad-Agents) | Autonomous AI agents |
| [BlackRoad Network](https://github.com/BlackRoad-Network) | Mesh and distributed networking |
| [BlackRoad Education](https://github.com/BlackRoad-Education) | Learning and tutoring platforms |
| [BlackRoad Labs](https://github.com/BlackRoad-Labs) | Research and experiments |
| [BlackRoad Cloud](https://github.com/BlackRoad-Cloud) | Self-hosted cloud infrastructure |
| [BlackRoad Forge](https://github.com/BlackRoad-Forge) | Developer tools and utilities |

### Links
- **Website**: [blackroad.io](https://blackroad.io)
- **Documentation**: [docs.blackroad.io](https://docs.blackroad.io)
- **Chat**: [chat.blackroad.io](https://chat.blackroad.io)
- **Search**: [search.blackroad.io](https://search.blackroad.io)

---

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/blackboxprogramming/blackroad-linear.svg?style=social&label=Star)](https://github.com/blackboxprogramming/blackroad-linear)
[![GitHub forks](https://img.shields.io/github/forks/blackboxprogramming/blackroad-linear.svg?style=social&label=Fork)](https://github.com/blackboxprogramming/blackroad-linear/fork)

# BlackRoad Linear Integration 🎯

Integrate BlackRoad with Linear for seamless project management!

## Features

- **Auto-issue Creation**
  - Failed deployments → Linear issues
  - Priority-based alerts
  - Complete error details

- **Deployment Tracking**
  - Sync all deployments to Linear
  - Track deployment status
  - Link to deployment dashboards

- **Bidirectional Integration**
  - Create deployments from Linear issues
  - Update issues with deployment URLs

## Installation

```bash
npm install @linear/sdk axios
```

## Setup

```bash
export LINEAR_API_KEY="your-linear-key"
export LINEAR_TEAM_ID="your-team-id"
export LINEAR_PROJECT_ID="your-project-id"
export BLACKROAD_API_KEY="your-api-key"
```

## Usage

```typescript
import { createIssueForFailedDeployment, syncDeploymentsToLinear } from './integration'

// Create issue for failed deployment
await createIssueForFailedDeployment(deployment)

// Sync all deployments
await syncDeploymentsToLinear()

// Create deployment from issue
await createDeploymentFromIssue('issue-id')
```

## Automatic Monitoring

The integration watches for failed deployments every 5 minutes and auto-creates urgent issues.

## License

MIT License

---

Part of the **BlackRoad Empire** 🚀
