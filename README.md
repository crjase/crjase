<p align="center">
  <img src="assets/hero_hud.svg" width="100%" alt="CRJASE Unc0ver HUD" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CALLSIGN-CRJASE-0A84FF?style=for-the-badge&labelColor=0d1117" alt="Callsign" />
  <img src="https://img.shields.io/badge/AGE-19-5E5CE6?style=for-the-badge&labelColor=0d1117" alt="Age 19" />
  <img src="https://img.shields.io/badge/AUSTRALIA-ASD--ALIGNED-10B981?style=for-the-badge&labelColor=0d1117" alt="Australia" />
  <a href="https://crjase.net"><img src="https://img.shields.io/badge/WEB-CRJASE.NET-0A84FF?style=for-the-badge&logo=google-chrome&logoColor=white&labelColor=0d1117" alt="Website" /></a>
  <img src="https://img.shields.io/github/followers/crjase?style=for-the-badge&color=161b22&labelColor=0d1117&logo=github&logoColor=0a84ff" alt="Followers" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OS-ARCH%20HARDENED-1793D1?style=for-the-badge&logo=archlinux&logoColor=white&labelColor=0d1117" alt="Arch Linux" />
  <img src="https://img.shields.io/badge/CORE-C%2B%2B20%20%7C%20C%20%7C%20PYTHON-00599C?style=for-the-badge&logo=cplusplus&logoColor=white&labelColor=0d1117" alt="Core Stack" />
  <img src="https://img.shields.io/badge/RF%20%26%20HW-RP2040%20%7C%20HACKRF%20SDR-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white&labelColor=0d1117" alt="Hardware" />
  <img src="https://img.shields.io/badge/AI-OFFLINE%20INFERENCE-10B981?style=for-the-badge&logo=linux&logoColor=white&labelColor=0d1117" alt="Local AI" />
</p>

---

### `01 // OPERATOR BRIEFING & SOVEREIGN DOCTRINE`

> [!IMPORTANT]
> **FIRST-PRINCIPLES ENGINEERING (AGE 19 · AUSTRALIA):** Every core system is built to run locally, deterministically, and without cloud dependencies—from hardened Arch Linux workstations and self-hosted Debian VPS infrastructure to bare-metal RP2040 firmware, SDR/RF tooling, and from-scratch C++ neural networks.

```yaml
callsign: crjase
age: 19
location: Australia
core_languages: [C++, C, Python, Bash, Kotlin]
doctrine:
  - Sovereign Offline-First: Self-hosted Nginx, Syncthing, SFTPGo, offline llama-server
  - Bare-Metal to Kernel: RP2040 / AVR microcontrollers up through Arch linux-hardened
  - Signal Over Noise: AI-assisted prototypes (e.g. Rust/Svelte) excluded from language stats
```

| Engineering Pillar | Standard | Applied Focus |
| :--- | :--- | :--- |
| **Zero-Cloud Autonomy** | Deterministic, self-hosted, air-gap ready | Debian 13 VPS, Nginx, PHP-FPM, `llama-server`, local encrypted comms |
| **Hardened Systems** | Minimal attack surface, reproducible builds | Arch (`linux-hardened`), Hyprland, CMake, shell automation |
| **Physical-to-Cyber** | Bridging hardware, RF, and network layers | HackRF One SDR, Flipper Zero, RP2040 SDK, access control & IP video |

---

### `02 // CAPABILITY BENTO & ARCHITECTURE`

<p align="center">
  <img src="assets/capabilities_hud.svg" width="100%" alt="Capabilities Bento HUD" />
</p>

```mermaid
flowchart LR
    subgraph L1["01 // HARDWARE & RF"]
        HW1["RP2040 Pico SDK / AVR"]
        HW2["HackRF One + PortaPack"]
        HW3["Flipper Zero / SMD"]
    end
    subgraph L2["02 // HARDENED OS"]
        OS1["Arch linux-hardened"]
        OS2["Debian 13 VPS / Nginx"]
        OS3["Syncthing / SFTPGo"]
    end
    subgraph L3["03 // CORE CODE"]
        C1["C++20 / C"]
        C2["Python / Bash"]
        C3["Kotlin / Qt Android"]
    end
    subgraph L4["04 // SOVEREIGN OPS"]
        OP1["C++ Tensor ML & llama-server"]
        OP2["Network & OpSec Tools"]
        OP3["Audio DSP / Demucs"]
    end
    L1 --> L2 --> L3 --> L4
    style L1 fill:#111622,stroke:#10b981,color:#f8fafc
    style L2 fill:#111622,stroke:#0a84ff,color:#f8fafc
    style L3 fill:#111622,stroke:#5e5ce6,color:#f8fafc
    style L4 fill:#111622,stroke:#ff9f0a,color:#f8fafc
```

---

### `03 // HARDWARE, RF & TOOLCHAIN LOADOUT`

| Category | Hardware / Platform | Operational Role |
| :--- | :--- | :--- |
| **Workstation** | Arch Linux (`linux-hardened`), Hyprland, KDE Plasma | Daily hardened dev & signal-processing environment |
| **Servers** | Debian 13 VPS, Nginx, PHP-FPM, Syncthing, SFTPGo | Self-hosted sovereign web & encrypted file infra |
| **Microcontrollers** | Raspberry Pi 4B, Raspberry Pi Pico (RP2040 SDK), Arduino Uno R4 | Bare-metal C/C++ firmware & embedded tooling |
| **RF & Field Gear** | HackRF One + PortaPack Mayhem, Flipper Zero, FNIRSI HS-02 | Spectrum analysis, RF prototyping & hardware debugging |
| **Local AI** | `llama-server`, Hermes Agent, Custom C++ Tensor Engine | Offline inference & from-scratch neural network R&D |
| **Audio & Signal Lab** | REAPER, Bitwig Studio, Demucs | Low-latency Linux audio routing & stem isolation |

* **Compilers & Build Systems:** `gcc`/`g++` (C++20), `clang`, `CMake`, Raspberry Pi Pico SDK, Android SDK + Qt
* **Network & Server Ops:** Nginx, PHP-FPM, dynamic DNS tooling, IPv4/IPv6 packet-level diagnostics, self-hosted chat/file relays
* **Physical Security & Field:** Electrical assembly, technical cabling, access control hardware, IP camera network architecture

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=cpp,c,py,kotlin,bash,linux,arch,debian,cmake,nginx,qt,raspberrypi,arduino,git,vscode&theme=dark&perline=8" alt="Core Tech Stack" />
  </a>
</p>

---

### `04 // SELECTED FIELD SYSTEMS`

| System | Language | Stars | Operational Focus |
| :--- | :---: | :---: | :--- |
| [**JJ-Spoofer**](https://github.com/crjase/JJ-Spoofer) | <img src="https://img.shields.io/badge/C%2B%2B-0A84FF?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" /> | <img src="https://img.shields.io/github/stars/crjase/JJ-Spoofer?style=flat-square&color=0a84ff&labelColor=0d1117" alt="Stars" /> | Low-level IPv4/IPv6 ARP & NDP network spoofing utility |
| [**GoDaddyDDNS**](https://github.com/crjase/GoDaddyDDNS) | <img src="https://img.shields.io/badge/Python-30D158?style=flat-square&logo=python&logoColor=white" alt="Python" /> | <img src="https://img.shields.io/github/stars/crjase/GoDaddyDDNS?style=flat-square&color=0a84ff&labelColor=0d1117" alt="Stars" /> | Self-hosted dynamic DNS server for local infrastructure |
| [**OpenChatServer**](https://github.com/crjase/OpenChatServer) | <img src="https://img.shields.io/badge/Python-30D158?style=flat-square&logo=python&logoColor=white" alt="Python" /> | <img src="https://img.shields.io/github/stars/crjase/OpenChatServer?style=flat-square&color=0a84ff&labelColor=0d1117" alt="Stars" /> | Lightweight self-hosted open-source chat server |
| [**GHome**](https://github.com/crjase/GHome) | <img src="https://img.shields.io/badge/Python-30D158?style=flat-square&logo=python&logoColor=white" alt="Python" /> | <img src="https://img.shields.io/github/stars/crjase/GHome?style=flat-square&color=0a84ff&labelColor=0d1117" alt="Stars" /> | Automated local network discovery & device control |
| [**JC-Time**](https://github.com/crjase/JC-Time) | <img src="https://img.shields.io/badge/Kotlin-5E5CE6?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" /> | <img src="https://img.shields.io/github/stars/crjase/JC-Time?style=flat-square&color=0a84ff&labelColor=0d1117" alt="Stars" /> | Native Android utility built from scratch |

---

### `05 // LIVE TELEMETRY (AI-FILTERED)`

<p align="center">
  <img src="assets/telemetry_hud.svg" width="100%" alt="Telemetry Integrity HUD" />
</p>

<p align="center">
  <a href="https://github.com/crjase">
    <img height="170" src="https://github-readme-stats-fast.vercel.app/api?username=crjase&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=0a84ff&icon_color=30d158&text_color=e5e7eb" alt="GitHub Stats" />
  </a>
  <a href="https://github.com/crjase">
    <img height="170" src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=crjase&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=0a84ff&text_color=e5e7eb&exclude_repo=TransparentTorProxy-GUI,crjase.github.io&hide=rust,svelte,html" alt="Core Languages" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/crjase">
    <img src="https://streak-stats.demolab.com?user=crjase&theme=tokyonight&hide_border=true&background=0d1117&stroke=1f2937&ring=0a84ff&fire=30d158&currStreakLabel=0a84ff" alt="GitHub Streak" />
  </a>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=crjase&bg_color=0d1117&color=0a84ff&line=5e5ce6&point=30d158&area=true&hide_border=true" width="96%" alt="Contribution Graph" />
</p>
