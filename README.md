[readme (1).md](https://github.com/user-attachments/files/35029282/readme.1.md)
```
flowchart LR
    HW["RF & Embedded Hardware\nRP2040 • AVR • HackRF One • Flipper Zero"] --> OS["Hardened OS & Infra\nArch linux-hardened • Debian • Nginx"]
    OS --> CORE["Hand-Written Core\nC++20 • C • Python • Kotlin • Bash"]
    CORE --> OPS["Sovereign Systems & AI\nCustom C++ ML • llama-server • Audio DSP"]
    style HW fill:#0b101b,stroke:#10b981,color:#f8fafc
    style OS fill:#0b101b,stroke:#00a8ff,color:#f8fafc
    style CORE fill:#0b101b,stroke:#6366f1,color:#f8fafc
    style OPS fill:#0b101b,stroke:#f59e0b,color:#f8fafc

```

<details>
<summary><b>EXPAND HARDWARE, RF &amp; INFRASTRUCTURE LOADOUT</b></summary>

| Category | Hardware / Platform | Operational Role | 
| ----- | ----- | ----- | 
| **Workstation** | Arch Linux (`linux-hardened`), Hyprland, KDE Plasma | Daily hardened dev & signal-processing environment | 
| **Servers** | Debian 13 VPS, Nginx, PHP-FPM, Syncthing, SFTPGo | Self-hosted sovereign web & encrypted file infra | 
| **Microcontrollers** | Raspberry Pi 4B, Raspberry Pi Pico (RP2040 SDK), Arduino Uno R4 | Bare-metal C/C++ firmware & embedded tooling | 
| **RF & Field Gear** | HackRF One + PortaPack Mayhem, Flipper Zero, FNIRSI HS-02 | Spectrum analysis, RF prototyping & hardware debugging | 
| **Local AI** | `llama-server`, Hermes Agent, Custom C++ Tensor Engine | Offline inference & from-scratch neural network R&D | 

</details>

| System | Language | Operational Focus | 
| ----- | ----- | ----- | 
| [**JJ-Spoofer**](https://github.com/crjase/JJ-Spoofer) |  | Low-level IPv4/IPv6 ARP & NDP network spoofing utility | 
| [**GoDaddyDDNS**](https://github.com/crjase/GoDaddyDDNS) |  | Self-hosted dynamic DNS server for local infrastructure | 
| [**OpenChatServer**](https://github.com/crjase/OpenChatServer) |  | Lightweight self-hosted open-source chat server | 
| [**GHome**](https://github.com/crjase/GHome) |  | Automated local network discovery & device control | 
| [JC-Time](https://www.google.com/search?q=https://github.com/crjase/JC-Time) |  | Native Android utility built from scratch | 
