# Michael | Gypsy-82

> *"Most people learn tools — I learn principles."*

[![Open to Work](https://img.shields.io/badge/Open%20to%20Work-IT%20Administrator-000000?style=for-the-badge&labelColor=000000&logoColor=white)](https://github.com/Gypsy-82)
[![Location](https://img.shields.io/badge/Based%20in-Canada%20🍁-000000?style=for-the-badge)]()

---

## 🧠 The Philosophy

Every system I build starts with the same questions:

- What permissions does this require — and can we scope them tighter?
- What's the blast radius if this fails or gets compromised?
- Has this been patched? When was it last audited?
- What does the upgrade path look like — and what breaks if we rush it?
- How do we stage the rollout, monitor the delta, and roll back clean if it goes wrong?
- How do we isolate it, log it, contain it, and keep it that way?

I work with AI. The thinking and architecture is always mine.

---

## 🖥️ Systems Administration

Where I live.

| Domain | Focus |
|--------|-------|
| **Linux (Ubuntu Server)** | VPS administration, service management, system hardening |
| **DNS & Networking** | Cloudflare, DNSSEC, A/CNAME/MX/TXT/SRV records, reverse proxy (Nginx) |
| **Auth & Security** | JWT, OAuth2, HMAC, bcrypt, MFA, SSH key management |
| **Containerization** | Docker, image builds, volumes, networks, compose stacks, container security |
| **Automation** | Cron jobs, Bash scripting, systemd services, patch management |
| **Firewall & Hardening** | ufw, fail2ban, rate limiting, zero-footprint principles |
| **CI/CD** | GitHub Actions, git workflows, automated deployment pipelines |

---

## 🛠️ Tech Stack

### In these repos

*Every badge below is demonstrated in one of the projects above — one click from proof.*

**Languages**

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=3776AB)
![PHP](https://img.shields.io/badge/PHP-000000?style=for-the-badge&logo=php&logoColor=777BB4)
![JavaScript](https://img.shields.io/badge/JavaScript-000000?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Bash](https://img.shields.io/badge/Bash-000000?style=for-the-badge&logo=gnu-bash&logoColor=4EAA25)
![HTML5](https://img.shields.io/badge/HTML5-000000?style=for-the-badge&logo=html5&logoColor=E34F26)
![CSS3](https://img.shields.io/badge/CSS3-000000?style=for-the-badge&logo=css3&logoColor=1572B6)

**Runtimes, Data & Infrastructure**

![Node.js](https://img.shields.io/badge/Node.js-000000?style=for-the-badge&logo=node.js&logoColor=339933)
![SQLite](https://img.shields.io/badge/SQLite-000000?style=for-the-badge&logo=sqlite&logoColor=003B57)
![Docker](https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=2496ED)
![Caddy](https://img.shields.io/badge/Caddy-000000?style=for-the-badge&logo=caddy&logoColor=1F88C0)
![Cloudflare](https://img.shields.io/badge/Cloudflare-000000?style=for-the-badge&logo=cloudflare&logoColor=F38020)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=F05032)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-000000?style=for-the-badge&logo=github-actions&logoColor=2088FF)

### Also work with

*From production and client work not published here.*

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-111111?style=for-the-badge&logo=postgresql&logoColor=336791)
![MySQL](https://img.shields.io/badge/MySQL-111111?style=for-the-badge&logo=mysql&logoColor=4479A1)
![Laravel](https://img.shields.io/badge/Laravel-111111?style=for-the-badge&logo=laravel&logoColor=FF2D20)
![FastAPI](https://img.shields.io/badge/FastAPI-111111?style=for-the-badge&logo=fastapi&logoColor=009688)
![Flask](https://img.shields.io/badge/Flask-111111?style=for-the-badge&logo=flask&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-111111?style=for-the-badge&logo=nginx&logoColor=009639)

---

## 🔐 Security Interests

Security isn't one-sided. I work both disciplines — because the best defense
is built by someone who understands the offense.

**Blue Team**
- Log analysis, anomaly detection, and incident response
- Firewall rule design, network segmentation, and access control
- Patch management, vulnerability auditing, and hardening
- SIEM concepts, forensic tooling, and evidence preservation

**Red Team**
- Reconnaissance, enumeration, and attack surface mapping
- Credential capture, honeypot design, and traffic interception
- Proxy chaining, anonymized operations, and evasion concepts
- Understanding exploit paths to build better defenses

> *The goal isn't to pick a side. It's to understand the whole board.*

---

## 🗂️ Featured Projects

Everything linked here is public and runnable. If it's in the table, it's in the repo.

| Project | What it is | Stack |
|---------|-----------|-------|
| [**cloakit**](https://github.com/Gypsy-82/cloakit) | Terminal file/folder cloaking — encrypts contents, filenames, **and the inventory itself** (item count hidden); XChaCha20-Poly1305 + Argon2id envelope key | Rust |
| [**deaddrop**](https://github.com/Gypsy-82/deaddrop) | **Store-and-forward** secret sharing — encrypt a message or file, hand off an unguessable link, it self-destructs on first read; zero-knowledge at rest | PHP, SQLite, Docker, Caddy |
| [**smsproxy**](https://github.com/Gypsy-82/smsproxy) | **Live** one-time terminal relay — bridges one authenticated browser to your shell over WebSocket (HMAC challenge/response); nothing stored, the link dies with the session | Node.js |
| [**ghstbsh**](https://github.com/Gypsy-82/ghstbsh) | Ghost shell — routes every shell history file to `/dev/null` so **nothing persists** after the session; zero crate dependencies, no daemon, no root | Rust |
| [**sysguard**](https://github.com/Gypsy-82/sysguard) | **Read-only** live terminal dashboard for a Linux host — resources, listeners & connections, processes, login/sudo activity, SUID binaries, services, cron | Python, Textual, psutil |

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Gypsy-82&show_icons=true&theme=dark&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Gypsy-82&layout=compact&theme=dark&hide_border=true&count_private=true)

---

## 📍 Based in Canada 🍁

> Available for **IT Administrator** roles — on-site, hybrid, or remote.
> Systems-focused. Security-minded. Ready to work.

[![GitHub](https://img.shields.io/badge/GitHub-Gypsy--82-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Gypsy-82)

---

```bash
$ whois Gypsy-82
> Faceless by default. Professional on request.
> But somewhere out there, we probably already follow each other.
> You just don't know it's me yet. 😏
```
