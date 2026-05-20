<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Orbitron&size=28&pause=1000&color=00FF00&center=true&vCenter=true&width=750&lines=DEADPIXEL;Phishing+Simulation+Research+Toolkit;Cloudflare+%2B+Ngrok+Support;Linux+%7C+Kali+%7C+WSL2" />

</div>

```text
██████╗ ███████╗ █████╗ ██████╗ ██████╗ ██╗██╗  ██╗███████╗██╗     
██╔══██╗██╔════╝██╔══██╗██╔══██╗██╔══██╗██║╚██╗██╔╝██╔════╝██║     
██║  ██║█████╗  ███████║██║  ██║██████╔╝██║ ╚███╔╝ █████╗  ██║     
██║  ██║██╔══╝  ██╔══██║██║  ██║██╔═══╝ ██║ ██╔██╗ ██╔══╝  ██║     
██████╔╝███████╗██║  ██║██████╔╝██║     ██║██╔╝ ██╗███████╗███████╗
╚═════╝ ╚══════╝╚═╝  ╚═╝╚═════╝ ╚═╝     ╚═╝╚═╝  ╚═╝╚══════╝╚══════╝
```

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=FF003C&center=true&vCenter=true&width=850&lines=Phishing+Simulation+Research+Toolkit;Security+Awareness+Testing+Framework;Browser+Permission+Analysis+Lab;Controlled+Cybersecurity+Demonstration+Environment" />

</div>

---

# DEADPIXEL

**DEADPIXEL** is a phishing simulation and browser behavior research toolkit built for controlled cybersecurity demonstrations, awareness testing, and client-side attack surface analysis.

The project focuses on:
- browser permission workflows
- social engineering simulations
- client-side trust exploitation
- phishing infrastructure behavior
- awareness training methodologies
- tunnel-based hosting workflows

> DEADPIXEL is intended strictly for ethical security research, awareness demonstrations, and controlled lab environments.

---

# Overview

Modern phishing attacks increasingly rely on:
- browser trust abuse
- fake authentication flows
- social engineering techniques
- tunnel-based temporary infrastructure
- client-side interaction manipulation

DEADPIXEL was developed to safely simulate these behaviors for:
- cybersecurity education
- phishing awareness testing
- browser security analysis
- offensive security demonstrations
- red-team research workflows
- controlled penetration-testing labs

---

# Core Features

- Tunnel-based phishing simulation workflows
- Cloudflare and Ngrok support
- Localhost-to-public exposure automation
- Lightweight Bash-based execution
- Customizable HTML/PHP templates
- Browser permission interaction testing
- Client-side behavior observation
- Multi-template simulation environment
- Linux/Kali/WSL2 compatibility

---

# Architectural Workflow

```text
                ┌─────────────────────┐
                │  Operator Machine   │
                │ Linux / Kali / WSL │
                └─────────┬───────────┘
                          │
                          ▼
                ┌─────────────────────┐
                │   DEADPIXEL Core    │
                │ Bash + PHP Engine   │
                └─────────┬───────────┘
                          │
          ┌───────────────┴────────────────┐
          │                                │
          ▼                                ▼
┌───────────────────┐          ┌────────────────────┐
│ Local PHP Server  │          │ Tunnel Provider     │
│ localhost hosting │          │ Cloudflare / Ngrok  │
└─────────┬─────────┘          └─────────┬──────────┘
          │                              │
          └──────────────┬───────────────┘
                         ▼
              ┌────────────────────┐
              │ Simulated Web Page │
              │ Login/UI Template  │
              └─────────┬──────────┘
                        │
                        ▼
              ┌────────────────────┐
              │ Browser Interaction │
              │ Permission Handling │
              └─────────┬──────────┘
                        │
                        ▼
              ┌────────────────────┐
              │ Research & Analysis │
              │ Awareness Testing   │
              └────────────────────┘
```

---

# Internal Workflow

```text
1. DEADPIXEL initializes a local PHP server
2. Tunnel provider establishes a temporary public endpoint
3. Public URL is generated dynamically
4. Selected simulation template is deployed
5. Browser/client interaction occurs
6. Permission and interaction behavior are analyzed
7. Research observations are collected in controlled environments
```

---

# Directory Structure

```text
DEADPIXEL/
├── templates/
│   ├── login-pages/
│   ├── browser-prompts/
│   └── simulation-ui/
├── tunnels/
│   ├── ngrok/
│   └── cloudflare/
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── logs/
├── payloads/
├── server/
├── deadpixel.sh
└── README.md
```

---

# Technical Stack

| Component | Technology |
|---|---|
| Scripting | Bash |
| Backend | PHP |
| Frontend | HTML/CSS/JavaScript |
| Hosting | PHP Local Server |
| Tunneling | Cloudflare / Ngrok |
| Environment | Linux / Kali Linux / WSL2 |
| Automation | Shell Scripts |

---

# Research Areas

## Browser Permission Analysis
- Notification prompts
- Browser trust behavior
- User permission timing
- Permission fatigue analysis

## Social Engineering Simulation
- Authentication-flow replication
- UI impersonation concepts
- Client-side manipulation vectors

## Tunnel Infrastructure Research
- Reverse tunneling workflows
- Temporary public endpoint exposure
- Remote-access simulation behavior

## Client-Side Security
- Form interaction behavior
- Session simulation concepts
- Browser-side attack surfaces

---

# Installation

## Clone Repository

```bash
git clone https://github.com/vkumxr/DEADPIXEL
cd DEADPIXEL
```

---

# Requirements

Ensure the following tools are installed:

```bash
php
curl
wget
unzip
```

For Debian/Kali/Ubuntu:

```bash
sudo apt update
sudo apt install php curl wget unzip -y
```

---

# Usage

```bash
chmod +x deadpixel.sh
bash deadpixel.sh
```

The toolkit will:
1. Start a local PHP server
2. Generate a public tunnel endpoint
3. Deploy the selected simulation template
4. Wait for interaction events
5. Provide controlled testing workflow output

---

# Example Terminal Output

```text
[+] Initializing DEADPIXEL Framework...
[+] Starting Local PHP Server...
[+] Establishing Secure Tunnel...
[+] Tunnel Generated Successfully
[+] Public Endpoint Ready
[+] Waiting For Client Interaction...
```

---

# Screenshots

## Terminal Workflow
```text
Tunnel Provider : Cloudflare
Server Status   : Active
Public URL      : https://xxxxx.trycloudflare.com
```

## Simulation Interface
- Login portal simulations
- Browser permission prompts
- Awareness-testing workflows

---

# Challenges Faced

- Tunnel reliability management
- Cross-browser behavior inconsistencies
- Lightweight Bash automation design
- Localhost-to-public exposure workflows
- Browser permission handling differences
- Maintaining modular template architecture

---

# Future Improvements

- Real-time telemetry dashboard
- AI-assisted interaction analysis
- Dockerized deployment workflows
- Browser fingerprint analysis
- Multi-user simulation support
- Advanced event logging
- Detection-evasion research sandbox
- Expanded awareness-training modules

---

# Project Goals

DEADPIXEL aims to help researchers and students:
- understand phishing infrastructure
- analyze browser trust behavior
- study social engineering workflows
- improve cybersecurity awareness training
- explore ethical offensive-security concepts
- simulate controlled phishing scenarios safely

---

# Ethical Scope

DEADPIXEL is developed strictly for:
- cybersecurity education
- awareness demonstrations
- authorized testing
- defensive security research
- controlled lab simulations

This project must never be used against:
- unauthorized systems
- public infrastructure
- real-world victims
- production environments

---

# Disclaimer

This repository is provided strictly for:
- educational use
- ethical security research
- authorized demonstrations
- cybersecurity awareness training

The developer assumes no responsibility for misuse or unauthorized activities performed using this project.

---

<div align="center">

### "Understanding attack surfaces is essential to defending them."

</div>
