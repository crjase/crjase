[readme_raw.txt](https://github.com/user-attachments/files/35030550/readme_raw.txt)


[](https://crjase.net)

   [](https://crjase.net)  

   

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

[](https://skillicons.dev)

---

### `04 // SELECTED FIELD SYSTEMS`

| System | Language | Stars | Operational Focus |
| :--- | :---: | :---: | :--- |
| [**JJ-Spoofer**](https://github.com/crjase/JJ-Spoofer) |  |  | Low-level IPv4/IPv6 ARP & NDP network spoofing utility |
| [**GoDaddyDDNS**](https://github.com/crjase/GoDaddyDDNS) |  |  | Self-hosted dynamic DNS server for local infrastructure |
| [**OpenChatServer**](https://github.com/crjase/OpenChatServer) |  |  | Lightweight self-hosted open-source chat server |
| [**GHome**](https://github.com/crjase/GHome) |  |  | Automated local network discovery & device control |
| [JC-Time](https://www.google.com/search?q=https://github.com/crjase/JC-Time) |  |  | Native Android utility built from scratch |

---

### `05 // LIVE TELEMETRY (AI-FILTERED)`



[](https://github.com/crjase) [](https://github.com/crjase)

[](https://github.com/crjase)


[assets/hero_hud.svg]

[[[invalid URL]]](https://crjase.net)

[https://img.shields.io/badge/CALLSIGN-CRJASE-0A84FF?style=for-the-badge&labelColor=0d1117] [https://img.shields.io/badge/AGE-19-5E5CE6?style=for-the-badge&labelColor=0d1117] [https://img.shields.io/badge/AUSTRALIA-ASD--ALIGNED-10B981?style=for-the-badge&labelColor=0d1117] [[https://img.shields.io/badge/WEB-CRJASE.NET-0A84FF?style=for-the-badge&logo=google-chrome&logoColor=white&labelColor=0d1117]](https://crjase.net) [https://komarev.com/ghpvc/?username=crjase&color=0a84ff&style=for-the-badge&label=VIEWS] [https://img.shields.io/github/followers/crjase?style=for-the-badge&color=161b22&labelColor=0d1117&logo=github&logoColor=0a84ff]

[https://img.shields.io/badge/OS-ARCH%20HARDENED-1793D1?style=for-the-badge&logo=archlinux&logoColor=white&labelColor=0d1117] [https://img.shields.io/badge/CORE-C%2B%2B20%20%7C%20C%20%7C%20PYTHON-00599C?style=for-the-badge&logo=cplusplus&logoColor=white&labelColor=0d1117] [https://img.shields.io/badge/RF%20%26%20HW-RP2040%20%7C%20HACKRF%20SDR-C51A4A?style=for-the-badge&logo=raspberrypi&logoColor=white&labelColor=0d1117] [https://img.shields.io/badge/AI-OFFLINE%20INFERENCE-10B981?style=for-the-badge&logo=linux&logoColor=white&labelColor=0d1117]

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

[assets/capabilities_hud.svg]

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

[[https://skillicons.dev/icons?i=cpp,c,py,kotlin,bash,linux,arch,debian,cmake,nginx,qt,raspberrypi,arduino,git,vscode&theme=dark&perline=8]](https://skillicons.dev)

---

### `04 // SELECTED FIELD SYSTEMS`

| System | Language | Stars | Operational Focus |
| :--- | :---: | :---: | :--- |
| [**JJ-Spoofer**](https://github.com/crjase/JJ-Spoofer) | [https://img.shields.io/badge/C%2B%2B-0A84FF?style=flat-square&logo=cplusplus&logoColor=white] | [https://img.shields.io/github/stars/crjase/JJ-Spoofer?style=flat-square&color=0a84ff&labelColor=0d1117] | Low-level IPv4/IPv6 ARP & NDP network spoofing utility |
| [**GoDaddyDDNS**](https://github.com/crjase/GoDaddyDDNS) | [https://img.shields.io/badge/Python-30D158?style=flat-square&logo=python&logoColor=white] | [https://img.shields.io/github/stars/crjase/GoDaddyDDNS?style=flat-square&color=0a84ff&labelColor=0d1117] | Self-hosted dynamic DNS server for local infrastructure |
| [**OpenChatServer**](https://github.com/crjase/OpenChatServer) | [https://img.shields.io/badge/Python-30D158?style=flat-square&logo=python&logoColor=white] | [https://img.shields.io/github/stars/crjase/OpenChatServer?style=flat-square&color=0a84ff&labelColor=0d1117] | Lightweight self-hosted open-source chat server |
| [**GHome**](https://github.com/crjase/GHome) | [https://img.shields.io/badge/Python-30D158?style=flat-square&logo=python&logoColor=white] | [https://img.shields.io/github/stars/crjase/GHome?style=flat-square&color=0a84ff&labelColor=0d1117] | Automated local network discovery & device control |
| [**JC-Time**](https://github.com/crjase/JC-Time) | [https://img.shields.io/badge/Kotlin-5E5CE6?style=flat-square&logo=kotlin&logoColor=white] | [https://img.shields.io/github/stars/crjase/JC-Time?style=flat-square&color=0a84ff&labelColor=0d1117] | Native Android utility built from scratch |

---

### `05 // LIVE TELEMETRY (AI-FILTERED)`

[assets/telemetry_hud.svg]

[[https://github-readme-stats-fast.vercel.app/api?username=crjase&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=0a84ff&icon_color=30d158&text_color=e5e7eb]](https://github.com/crjase) [[https://github-readme-stats-fast.vercel.app/api/top-langs/?username=crjase&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=0a84ff&text_color=e5e7eb&exclude_repo=TransparentTorProxy-GUI,crjase.github.io&hide=rust,svelte,html]](https://github.com/crjase)

[[https://streak-stats.demolab.com?user=crjase&theme=tokyonight&hide_border=true&background=0d1117&stroke=1f2937&ring=0a84ff&fire=30d158&currStreakLabel=0a84ff]](https://github.com/crjase)

[https://github-readme-activity-graph.vercel.app/graph?username=crjase&bg_color=0d1117&color=0a84ff&line=5e5ce6&point=30d158&area=true&hide_border=true]
