
# Hi there 👋 

## About Me
I'm **srNima** — an engineer who lives through technology, repair, teaching, and building new chapters in the digital world.

## 🎧 MicroSpy Player — Autonomous Audio Recorder (2014)

This device was designed and assembled by **srNima** in 2014, long before many modern low‑power audio modules existed. At first glance it looks like a simple MP3 player, but internally it is a fully independent audio‑recording system with the following capabilities:

- **USB-powered operation** for both energy input and data transfer to the internal 8GB storage  
- **Automatic microphone activation** when connected to a charger or USB power source  
- **Hands‑free audio recording** in AMR format with efficient file size  
- **3.5mm audio output jack** for headphone playback or signal monitoring  
- **Fully hand‑assembled PCB**, including ICs, diodes, and supporting components  
- **Stealth-friendly design**, intentionally shaped like a standard music player for compactness and portability  

### Purpose of the Project
This build was created as a **technical experiment**, demonstrating how a self-contained embedded system can record audio without an operating system, user interface, or external software. It showcases early work in low-power electronics, embedded logic, and hardware miniaturization.

> This project is for educational and archival purposes. Recording audio without consent is unethical and may be illegal depending on jurisdiction. The creator does not endorse misuse of this device.

## 🧠 Computer & Creative Skills

A combination of engineering, repair, and digital creativity:

### 🔧 Technical & Engineering
- Hardware repair (Samsung, iPhone, laptops, desktops)
- Power engineering (built custom voltage‑stabilizing transformer)
- Receiver repair (iClass, StarSat, Strong, StarMax)
- Samsung 32‑bit board diagnostics
- Bootloader analysis & system recovery
- Custom OS installation (LineageOS, AndroidOS, Linux)
- CPU & fan optimization on laptops/desktops

### 💻 Software & Digital Skills
- HTML / CSS (certified)
- Flash 8 (advertising & animation)
- Basic scripting for testing & automation
- Technical documentation for global communities

### 🎨 Creative & Advertising
- Designed promotional concepts for **Dunhill Silver**
- Received appreciation gift + payment for design proposal
- Experience in branding, layout, and visual concepts

---

## 💈 Barbering & Human Skills

Before engineering, I worked as a **professional barber** in Tehran:

- Pasdaran – Borj Sefid – Rose Siah Salon  
- Ferdowsi Square – Bahar Street  
- Trained at **Midlen Enghelab** (professional certification)

✂ 💇‍♀️I continue cutting hair today — even after my accident — with the same precision and care.

---

## 🛠️ Life Journey

I live with a wheelchair and T5–T6 spinal implants, but I’ve never stopped building, repairing, or teaching.  
My path includes:

- Transition from standing work to seated technical work  
- Supporting elderly, blind, and vulnerable customers  
- Combining engineering + creativity + human connection  
- Building **Season XboX** as a new chapter of exploration  
- Planning to travel across Europe to teach kids & engineers
- 
With deep experience in repairing mobile phones, laptops, and desktop systems, my work includes installing custom operating systems (AndroidOS, LineageOS, Linux), optimizing CPU and fan performance, and documenting full boot and repair processes.  
Beyond technical skills, my mission is to make technology understandable, accessible, and inspiring — for children, beginners, and professional engineers alike, in every country.

I live with a wheelchair and artificial spinal implants (T5–T6), but I've never been limited. For me, technology is not just a tool — it's a shared language for building, teaching, and connecting with the world.

I plan to travel across Europe — including Germany — to teach children and engineers how to repair, optimize, and understand technology. Every project you see here is part of that journey: chapters written with precision, care, and hope.

---

## Areas of Expertise
- Repairing and restoring Android and iOS devices  
- Installing custom operating systems (LineageOS, AndroidOS, Linux)  
- Developing boot test scripts and performance reports  
- Optimizing CPU and fan control on laptops and desktops  
- Teaching technology to kids, teens, and engineers  
- Technical documentation for GitHub and global communities  

---

## My Mission
To build chapters of technology that not only restore devices — but empower people.  
Every line of code, every repair, and every lesson is part of that mission.

---

# Project Testing – Changelog (Note 4 N910C)

This file documents all backup and analysis steps for the Note 4 (N910C).

### Template Entry
- **Date:** 2025-11-03  
- **Action:** Describe what was done (e.g. "Created EFS backup via TWRP")  
- **Location:** Path on SD card or GitHub folder  
- **Notes:** Observations (CSC code, file size differences, hash verification)  

### Example Entries
- **2025-10-17**  
  - **Action:** Initial EFS backup created via TWRP  
  - **Location:** `/storage/2B4B-69C9/EFS N910C 2025-10-17`  
  - **Notes:** Backup verified, CSC code observed as `XSG`

- **2025-11-29**  
  - **Action:** Manual copy of EFS folder added  
  - **Location:** `/storage/2B4B-69C9/efs`  
  - **Notes:** Hashes generated, compared with initial backup, no differences found

- **2025-11-30**  
  - **Action:** TWRP backup folder confirmed and indexed  
  - **Location:** `/storage/2B4B-69C9/Backups_N910C`  
  - **Notes:** Full system + EFS partitions included

---

# Season: XboX 🎮
Focus exclusively on **Xbox Series X|S**

## 🛠️ Goals of the Season
- Document and analyze Xbox Series S/X hardware  
- Record thermal and performance tests before/after cleaning and repair  
- Archive emergency and creative tricks  
- Compare with older consoles (Xbox 360)  
- Buildsupportingg tools and scripts  

## 🔧 Emergency Trick – Replacing Thermal Paste
- **Issue:** Consoletempperatree before cleaning reached 60–65°C.  
- **Action:** Full disassembly, cleaning, and reassembly.  
- **Challenge:** No proper thermal paste available.  
- **Solution:** Folded medium-thickness aluminum foil (~1×0.5 cm) placed between APU and heatsink.  
- **Result:** Temperature dropped by ~30°C, with no contact to the board or sensitive components.  

⚠️ This method is only an **emergency workaround** and not a permanent replacement for thermal paste.  
A reliable product such as **DeepCool Z5** is recommended for long-term stability.

## 📊 Next Tests
- Run heavy games (Resident Evil, Forza Horizon) to check stable temperatures  
- Record thermal logs before and after applying proper paste  
- Compare fan behavior and noise levels

## 🎮 Xbox GamePass Library – Installed Titles  

### 🟩 AAA Titles
- **Hogwarts Legacy**  
- **Grand Theft Auto V (GTA 5)**  
- **Red Dead Redemption 2**  
- **Assassin’s Creed: Valhalla**  
- **Shadow of the Tomb Raider**

### 🟦 Racing & Open‑World
- **Forza Horizon 5 – Premium Edition**  
- **Microsoft Flight Simulator 2024**

### 🟪 Action / Adventure
- **Batman: Arkham Knight**  
- **Crash Bandicoot**  
- **Stray**

### 🟥 Fighting & Family Games
- **Tekken 8**  
- **Ben 10: Power Trip**
---

## 📂 Suggested Repository Structure

Updated README with new structure and Season: XboX

# MOBILE — Mobile Kernel Engineering & Hardware Analysis  
Created, documented and engineered by **srNima**  
Advanced Documentation • Deep Kernel Tuning • Visual Technical Resume

---

## 1. Device Profile (J700H)
| Component | Specification |
|----------|---------------|
| Owner / Engineer | **srNima** |
| Model | Samsung Galaxy J700H |
| SoC | Exynos 7580 (8× Cortex-A53) |
| GPU | Mali-T720 MP2 |
| RAM | 1.5–2GB LPDDR3 |
| Storage | eMMC 5.0 |
| Kernel Base | Linux 3.10.x |
| ROM | LineageOS |
| CCustomKernel | kernel-final+ |

---

## 2. Kernel Feature Overview (kernel-final+)
Maintained, tuned and tested by **srNima**

- Custom CPU hotplug driver (Lazypug)
- Advanced I/O scheduler tuning
- ZRAM compression support (lz4, lzo, zstd)
- TCP congestion control suite (Westwood, Cubic, Reno, BIC, HTCP)
- Power Suspend modes (Kernel, Hybrid, LCD Hooks)
- Fsync toggle
- VM tuning hooks
- Misc block-layer optimizations

---

## 3. CPU Management (Lazypug)

### Recommended Configuration (Performance-Balanced)
Optimized and validated by **srNima**

| Setting | Value | Reason |
|--------|--------|--------|
| Profile | Balanced | Best balance between responsiveness and battery |
| Touch Boost | Enabled | Faster touch response |
| Hysteresis Value | 1–2 | Faster reaction to load changes |
| CPU Threshold | 6 | Activates cores at the right time |
| Max CPU Online | 8 | Full use of all A53 cores |

### Technical Notes
- Lower threshold → cores activate sooner → better performance  
- Higher threshold → lower battery usage but possible micro-lag  
- Lazypug replaces MPDecision with more stable behavior

---

## 4. Virtual Memory (ZRAM)

### Recommended Configuration
| Setting | Value |
|--------|--------|
| ZRAM Disksize | 1024MB |
| Compression Algorithm | lz4 |

### Technical Notes
- lz4 is the fastest algorithm for low-RAM devices  
- 1024MB is the sweet spot between performance and RAM pressure  
- Higher than 1.5GB may cause stalls on J700H

---

## 5. Network Stack (TCP Congestion Control)

### Recommended Algorithm: Westwood
| Algorithm | Use-Case | Notes |
|-----------|----------|-------|
| Westwood | Mobile/Wi-Fi | Best for unstable networks |
| Cubic | Stable networks | Default in modern kernels |
| Reno | Legacy | Only for testing |
| BIC | Aggressive | Not recommended |
| HTCP | Datacenter | Not suitable for mobile |

---

## 6. Power Suspend

### Recommended Mode: Hybrid
- Smart balance between Kernel Mode and LCD Hooks  
- Lower idle consumption  
- No lag on wake-up

---

## 7. Filesystem & I/O

| Setting | Recommended | Notes |
|---------|-------------|-------|
| Fsync | OFF | Faster I/O (small risk on crash) |
| I/O Stats | ON | For monitoring |
| Rotational Storage | OFF | Device uses eMMC |
| Add Random | OFF | Only useful for HDD |
| RQ Affinity | 2 | Best for multi-core |
| No-Merges | 1 | More accurate block-layer behavior |
| NR Requests | 256 | Good for eMMC 5.0 |

---

## 8. Visual Resume (Gallery Template)

### Screenshot Template  
Documented by **srNima**

- Device: J700H  
- ROM: LineageOS  
- Kernel: kernel-final+  
- Section: (Lazypug / ZRAM / Misc / I/O / Power Suspend)  
- Active Settings:  
  - CPU Threshold: 6  
  - ZRAM: 1024MB (lz4)  
  - TCP: Westwood  
  - Power Suspend: Hybrid  
- Technical Description:  
  Explain what the screenshot shows and why it matters.  
- Notes:  
  - Reason for choosing the setting  
  - Test results  
  - Effect on performance/battery

---

## 9. Benchmark & Stress Testing

| Test | Result | Notes |
|------|--------|--------|
| CPU Scaling | Pending | Needs screenshot |
| RAM Pressure | Pending | With ZRAM enabled |
| I/O Throughput | Pending | With Fsync OFF |
| Boot Time | Pending | After final tuning |

---

## 10. Hardware Diagnostics (J700H)

### Repair Template  
Performed by **srNima**

- Issue:  
- Diagnosis:  
- Fix Steps:  
- Result:  
- Photos: Linked in Gallery

---

## 11. Folder Structure

```
MOBILE/
├── Kernels/
│   └── Kernel-final  ├── Screenshots/
│       └── README.md
├── ROMs/
│   └── LineageOS/
├── Repairs/
├── Gallery/
│   └── J700H/
```

---

## Status
This season is actively updated with kernel tests, VM tuning, I/O analysis, and visual documentation by **srNima**.
