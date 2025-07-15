










         _    __  __   ____ 
        / \  |  \/  | |  _ \ 
       / _ \ | |\/| | | | | |
      / ___ \| |  | | | |_| |
     /_/   \_\_|  |_| |____/ 




# AMD Chip Research

This repository contains research, reverse engineering, and documentation on a wide range of AMD hardware — including GPUs, APUs, and CPUs — for the purpose of enabling and improving open-source support.

The project is part of my contribution to the open-source ecosystem, including the Mesa 3D graphics stack, Coreboot, and Linux kernel-level development.

## 🔬 Scope of Research

### 🖥️ GPU / APU Architectures

- **Carrizo** (e.g., FX-8800P APU): GPU internals and register maps, driver development  
- **Vega10** (e.g., RX Vega 56/64): Command streams, GCN5 shader core, driver development  
- **Renoir** (Ryzen 4000U APU): Unified memory access, iGPU block structure, driver development  

### 🧠 CPU Architectures

- **Zen 1**: Microarchitecture layout, MSRs, power management, driver development  
- **Zen 3**: CCX analysis, SMT, System Management Interface (SMI), driver development  
- **Ryzen 9 9950X/9950X36**: Driver development, analysis
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
E-Mail: zerodayzone1111@gmail.com
Open for collaboration and contributions.

---

> This repository is intended for educational and research purposes only. No proprietary code is included.
> This projekt is mostly intendet for research and behavior of the Mesa 3d library.
> All drivers for graphics can be found in the Mesa 3d library.


