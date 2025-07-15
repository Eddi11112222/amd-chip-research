# AMD Chip Research

This repository contains research, reverse engineering, and documentation on a wide range of AMD hardware — including GPUs, APUs, and CPUs — for the purpose of enabling and improving open-source support.

The project is part of my contribution to the open-source ecosystem, including the Mesa 3D graphics stack, Coreboot, and Linux kernel-level development.

## 🔬 Scope of Research

### 🖥️ GPU / APU Architectures

- **Carrizo** (e.g., FX-8800P APU): GPU internals and register maps  
- **Vega10** (e.g., RX Vega 56/64): Command streams, GCN5 shader core  
- **Renoir** (Ryzen 4000U APU): Unified memory access, iGPU block structure  

### 🧠 CPU Architectures

- **Zen 1**: Microarchitecture layout, MSRs, power management  
- **Zen 3**: CCX analysis, SMT, System Management Interface (SMI)  
- Firmware analysis (PSP, SMU)

## 🧩 Repository Structure

amd-chip-research/

├── gpu/

│ └── carrizo/, vega10/, renoir/

├── cpu/

│ └── zen1/, zen3/

├── firmware/

│ └── psp/, smu/, vcn/

├── bios-dumps/

├── mesa-contrib/

├── LICENSE (MIT)


## 🎯 Goals

- Help Mesa 3D and kernel devs support AMD platforms
- Contribute reverse engineering documentation for hardware-level understanding
- Encourage collaboration and transparency in GPU/CPU research

## 🧑‍💻 Maintainer

Erik Thurmann  
GitHub: [eddi11112222](https://github.com/eddi11112222)  
Discord: `Zero`  
Open for collaboration and contributions.

---

> This repository is intended for educational and research purposes only. No proprietary code is included.

