# 🧪 Examples — Module 2 Hardware


## 🖥️ Computer Assembly Checklist

### 1. Preparing the Case and Motherboard
- Install the I/O shield in the case.  
- Ensure standoffs are correctly placed for the motherboard form factor (ATX, Micro-ATX, etc.).  
- Carefully position and screw the motherboard into the case.  

### 2. Installing the CPU
- Open the CPU socket lever.  
- Align the CPU notches with the socket (triangle marker as guide).  
- Place the CPU gently, without force.  
- Close the socket lever.  
- Apply a small amount of thermal paste.  
- Install and secure the CPU cooler, connect its fan cable to the CPU_FAN header.  

### 3. Installing RAM
- Open the DIMM slot latches.  
- Align the RAM module notch with the slot.  
- Firmly press until the latches click into place.  
- Repeat for multiple modules, following dual-channel or quad-channel configurations (check manual).  

### 4. Installing the GPU
- Locate the PCIe x16 slot on the motherboard.  
- Remove the case expansion slot cover.  
- Insert the GPU firmly until it clicks into place.  
- Secure the GPU with a screw to the case.  
- Connect PCIe power cables from the PSU if required.  

### 5. Installing Storage Devices
- **HDD/SSD (SATA):** Mount in drive bay, connect SATA data cable to motherboard and SATA power cable from PSU.  
- **SSD NVMe (M.2):** Insert into M.2 slot at an angle, press down, and secure with screw.  

### 6. Power Supply and Cabling
- Install the PSU into the case (bottom or top mount).  
- Connect 24-pin ATX cable to the motherboard.  
- Connect 8-pin (or 4+4 pin) CPU power cable near the processor socket.  
- Connect PCIe power cables to GPU if required.  
- Connect SATA power cables to drives.  

### 7. Final Steps
- Connect front panel connectors (power switch, reset switch, USB, audio).  
- Organize cables for proper airflow (use cable ties).  
- Close the case panels.  
- Connect monitor, keyboard, and mouse.  
- Power on the system and enter BIOS/UEFI to check if all components are detected.

## Example: Data Bus Width
- An 8-bit External Data Bus (EDB) can transfer 1 byte at a time.  
- A 64-bit bus can transfer 8 bytes at a time.  
- Wider buses = higher throughput, but require more physical connections.

## Example: Memory Limit
- A 32-bit CPU can address 2^32 = 4,294,967,296 bytes (~4 GB).  
- A 64-bit CPU can address 2^64 = ~16 exabytes (limited by OS, usually TBs).  

## Example: CPU Cache
- L1 Cache: ~32 KB, fastest, inside each core.  
- L2 Cache: ~256 KB – 2 MB, per core or shared.  
- L3 Cache: 8 MB – 64 MB, shared among all cores.  
- Access order: CPU checks L1 → L2 → L3 → RAM (slower).

## Example: Motherboard Sizes
| Form Factor | Dimensions     | Expansion Slots | Typical Use Case      |
|-------------|----------------|-----------------|-----------------------|
| ATX         | 305 x 244 mm   | Up to 7 slots   | Gaming, workstation   |
| Micro-ATX   | 244 x 244 mm   | Up to 4 slots   | Budget PCs, offices   |
| Mini-ITX    | 170 x 170 mm   | 1 slot          | Compact builds        |

## Example: Video Interfaces
| Interface |      Signal      | Max Resolution  | Audio | Status         |
|-----------|------------------|-----------------|-------|----------------|
| VGA       | Analog           | ~1080p          | No    | Legacy/obsolete|
| DVI       | Digital/Analog   | 1920x1200+      | No    | Transition     |
| HDMI 2.1  | Digital          | 8K @ 60Hz       | Yes   | Modern TVs/PCs |
| DP 2.0    | Digital          | 16K @ 60Hz      | Yes   | High-end PCs   |

## Example: USB Versions
| Version | Year | Speed           | Connector   |
|---------|------|-----------------|-------------|
| USB 1.1 | 1998 | 12 Mbps         | USB-A       |
| USB 2.0 | 2000 | 480 Mbps        | USB-A       |
| USB 3.0 | 2008 | 5 Gbps          | USB-A/USB-C |
| USB 3.2 | 2017 | 20 Gbps         | USB-C       |
| USB4    | 2019 | 40 Gbps         | USB-C       |

## Example: Charge Cycle
- 1 full cycle = 0% → 100% charge.  
- Two partial charges (50% → 100% twice) = 1 full cycle.  
- Typical smartphone battery: 300–500 cycles before 20% capacity loss.  
- Typical laptop battery: 500–1000 cycles.  

## Example: Driver and BIOS
- **Driver:** To use a GPU properly, you must install its driver (e.g., NVIDIA/AMD).  
- **BIOS/UEFI:** Enter setup (F2/DEL key) → change boot order to install OS from USB.  

## Example: Display Technologies Comparison

| Technology | Type           | Strengths                               | Weaknesses                       |
|------------|----------------|-----------------------------------------|----------------------------------|
| LCD        | Backlit        | Affordable, reliable                    | Limited contrast, needs backlight|
| TN         | LCD subtype    | Very fast response, high refresh, cheap | Poor color/angles                |
| IPS        | LCD subtype    | Accurate colors, wide viewing angles    | Lower contrast than VA; IPS glow |
| VA         | LCD subtype    | High contrast, deeper blacks            | Slower response vs TN/fast IPS   |
| OLED       | Self-emissive  | Perfect blacks, wide angles             | Expensive; burn-in risk          |
| AMOLED     | OLED subtype   | Thin, efficient for mobile              | Same limitations as OLED         |
| Mini-LED   | LCD + tiny LEDs| High brightness, HDR performance        | More costly than normal LCD      |
| MicroLED   | Self-emissive  | Bright, durable, no burn-in             | Extremely expensive, early stage |

### Common Use
- **LCD:** Basic monitors, laptops  
- **TN:** Budget gaming monitors  
- **IPS:** Professional monitors, notebooks  
- **VA:** TVs, mid-range monitors  
- **OLED:** High-end TVs, smartphones  
- **AMOLED:** Smartphones, tablets  
- **Mini-LED:** Premium TVs, monitors  
- **MicroLED:** Prototypes, luxury displays  

## Example: Display Technologies Timeline

| Technology | Era/Introduction | Evolution Role                              | Status Today           |
|------------|------------------|---------------------------------------------|------------------------|
| LCD        | 1990s            | First mainstream flat panels replacing CRTs | Still common (basic)   |
| TN         | Late 1990s       | Fast & cheap LCD panels                     | Entry gaming monitors  |
| IPS        | 2000s            | Wide viewing, accurate colors               | Standard for pros      |
| VA         | 2000s            | Better contrast, deeper blacks              | TVs, mainstream use    |
| OLED       | 2010s            | Self-emissive, true blacks                  | High-end TVs, phones   |
| AMOLED     | 2010s            | Optimized OLED for mobile                   | Smartphones, tablets   |
| Mini-LED   | Late 2010s       | Improved LCD backlight for HDR              | Premium TVs/monitors   |
| MicroLED   | 2020s            | Next-gen self-emissive, no burn-in          | Early prototypes       |

## Example: Data Sizes Calculation
- 1 byte = 8 bits  
- 1 KB = 1024 bytes  
- 1 MB = 1024 KB = 1,048,576 bytes  
- 1 GB = 1024 MB ≈ 1 billion bytes  
- Example: A 5 GB file ≈ 5 × 1024 MB = 5120 MB   

---

## Example: Preventing ESD (Electrostatic Discharge)
- Always work on a non-carpeted surface.  
- Use an anti-static wrist strap connected to the case.  
- Touch a grounded metal object before handling components.  
- Avoid touching pins or circuitry directly.  

---

## Example: Applying Thermal Paste
1. Place a small pea-sized dot of thermal paste at the center of the CPU.  
2. Mount the heatsink evenly on top of the CPU.  
3. The pressure spreads the paste into a thin layer.  
4. Avoid using too much paste — it can cause overheating instead of cooling.  

---

## Example: POST (Power-On Self-Test)
- When turning on a PC, POST runs automatically.  
- **Success:** One beep, system proceeds to boot.  
- **Failure:** Beep codes or error messages indicate faulty components (e.g., no RAM detected).  

---

## Example: BIOS vs UEFI
| Feature         | BIOS                   | UEFI                          |
|-----------------|------------------------|-------------------------------|
| Interface       | Text-based             | Graphical, mouse support      |
| Disk Support    | Up to 2 TB (MBR)       | >2 TB (GPT)                   |
| Boot Speed      | Slower                 | Faster                        |
| Security        | Limited                | Secure Boot, advanced options |

---

## Example: System Image Restore
- If a PC is corrupted by malware, the user can boot into recovery mode.  
- Select **Restore System Image**.  
- Choose a backup created earlier.  
- The OS and files return to the exact state from the backup date.  

---

## Example: SoC (System on a Chip) in Practice
- Smartphones use SoCs that integrate CPU, GPU, memory controller, and wireless radios.  
- Example: Apple M1 chip → combines CPU, GPU, Neural Engine, memory in a single package.  
- Benefits: lower power consumption, higher integration, compact size.  

## Example: CPU Socket Types — PGA vs LGA

| Feature     | PGA (Pin Grid Array)         | LGA (Land Grid Array)               |
|-------------|------------------------------|-------------------------------------|
| Pins        | On the CPU                   | On the motherboard socket           |
| Fragility   | CPU pins can bend            | Socket pins can bend                |
| Repair      | Replace CPU if pins damaged  | Replace motherboard if pins damaged |
| Typical Use | AMD (ex.: AM4)               | Intel (ex.: LGA1200, LGA1700)       |

- **PGA:** More common in AMD processors. Easy to replace motherboard, but CPU pins are fragile.  
- **LGA:** More common in Intel processors. CPU safer, but motherboard socket is fragile.  

## Example: RAM Generations Comparison

| Type   | Year Intro | Voltage | Typical Speed | Status Today       |
|--------|------------|---------|---------------|--------------------|
| DDR    | 2000       | 2.5 V   | 200–400 MT/s  | Obsolete           |
| DDR2   | 2003       | 1.8 V   | 400–800 MT/s  | Obsolete           |
| DDR3   | 2007       | 1.5 V   | 800–2133 MT/s | Legacy systems     |
| DDR4   | 2014       | 1.2 V   | 1600–3200 MT/s| Current mainstream |
| DDR5   | 2021       | 1.1 V   | 4800–8400+ MT/s | Modern/high-end  |

---

### SO-DIMM in Practice
- Same technology as DIMM but smaller.  
- Used in laptops and mini-PCs.  
- Example: A gaming laptop may use 32 GB (2 × 16 GB) DDR5 SO-DIMM modules.  
