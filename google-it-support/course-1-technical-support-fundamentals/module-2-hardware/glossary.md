# Glossary — Module 2: Hardware

- **Desktop Computer:**  
  A personal computer designed to fit on or under a desk.  
  Typically consists of a separate monitor, keyboard, mouse, and a tower or case containing the main hardware components (CPU, RAM, storage, motherboard, power supply).  
  Desktops usually allow easier hardware upgrades compared to laptops.

- **RAM (Random Access Memory):**  
  A volatile memory that temporarily stores data and instructions being actively used by the CPU.  
  It allows fast read/write access and improves system performance, but loses its content when power is off.

  - **DDR (Double Data Rate):**  
  Type of SDRAM that transfers data on both rising and falling edges of the clock signal, doubling speed compared to regular SDRAM.  

- **DDR2:**  
  Faster and more efficient than DDR, with lower power consumption. Obsolete today, used in older PCs.  

- **DDR3:**  
  Common in PCs from ~2007–2015. Higher bandwidth and lower voltage than DDR2.  

- **DDR4:**  
  Mainstream RAM for most systems from 2015–2021. Improved speed, efficiency, and capacity compared to DDR3.  

- **DDR5:**  
  Current generation of RAM (2021+). Much higher bandwidth, larger capacity per module, and improved power efficiency. Standard in modern PCs and servers.  

- **SO-DIMM (Small Outline DIMM):**  
  A compact version of DIMM, used mainly in laptops and small form factor PCs. Available in DDR3, DDR4, and DDR5 versions.  

- **PSU (Power Supply Unit):** converts electricity from outlet to usable power for the PC.
- **I/O Devices:** peripherals for input (keyboard, mouse) and output (monitor, printer).
- **Hard Drive:** Holds all our data, which includes all of our music, pictures, applications.
- **EDB (External Data Bus):** A row of wires interconnect the parts of our computer.
- **Peripheral:** Anything that you connect to your computer externally that adds functionality.

- **USB (Universal Serial Bus):**  
  A standard interface used to connect peripherals (keyboard, mouse, storage devices, printers, smartphones) to a computer.  
  It supports both data transfer and power delivery.  

  **Main Versions:**
  - **USB 1.1:** Basic standard, up to 12 Mbps (legacy).  
  - **USB 2.0:** Widely adopted, up to 480 Mbps.  
  - **USB 3.0 / 3.1 / 3.2:** Faster speeds, ranging from 5 Gbps to 20 Gbps. Identified by blue connectors.  
  - **USB4:** Latest standard, up to 40 Gbps, based on Thunderbolt 3 technology.  
  - **USB-C:** Connector type (reversible) used in USB 3.x and USB4, supports high-speed data, video output, and power delivery (up to 100W+).  

- **MCC (Memory Chip Controller):**
  A component responsible for managing data flow between the CPU and the main memory (RAM).  
  In modern systems, the MCC is often integrated into the CPU itself, improving performance and reducing latency.

- **GPU (Graphics Processing Unit):**  
  A specialized processor designed to handle rendering of graphics, images, and video.  
  Modern GPUs also perform parallel computing tasks (e.g., AI, data science, crypto mining).  
  They are usually installed on dedicated PCIe graphics cards, but some CPUs have **integrated GPUs**

- **CPU (Central Processing Unit):** the brain of the computer that executes instructions.
- **Clock Speed:** The maximum number of clock cycles that it can handle in a certain time period.

- **CPU Overclock:** CPU overclocking makes it run at a higher clock frequency than the original manufacturer specifications.

- **CPU Instruction Set (ISA — Instruction Set Architecture):**  
  The complete set of machine language instructions that a CPU can understand and execute.  
  It defines operations such as arithmetic (add, subtract), logic (AND, OR), data movement (load, store), and control flow (jump, branch).  
  Examples of instruction set architectures include **x86**, **ARM**, and **RISC-V**.  
  The ISA acts as the interface between software and hardware, determining compatibility between programs and processors.

- **CPU Socket:**  
  A physical connector on the motherboard that holds the CPU and allows communication with other components.  
  It provides both the **electrical interface** (pins/contacts) and the **mechanical support** for the processor.  
  Different CPUs require different socket types (e.g., Intel LGA 1200, AMD AM4).  
  The socket type determines which processors are compatible with a given motherboard.

- **32-bit CPU:**  
  A processor architecture that handles data in 32-bit chunks.  
  It can use up to 4 GB of addressable memory space (2^32 addresses).  
  Common in older computers and operating systems.  

- **64-bit CPU:**  
  A processor architecture that handles data in 64-bit chunks.  
  It supports a vastly larger memory address space (2^64 addresses, theoretically ~16 exabytes, though practical OS limits are lower).  
  Modern computers and operating systems are mostly 64-bit.  
  64-bit CPUs can often run 32-bit applications for backward compatibility.

---

## 🧠 CPU Cache Levels

- **L1 Cache (Level 1):**  
  - The fastest and smallest cache, located inside each CPU core.  
  - Stores the most frequently used instructions and data.  
  - Typically between 16 KB and 128 KB.  

- **L2 Cache (Level 2):**  
  - Larger but slower than L1.  
  - Can be dedicated per core or shared between cores.  
  - Usually ranges from 256 KB to a few MB.  

- **L3 Cache (Level 3):**  
  - Shared across all cores in a multi-core CPU.  
  - Much larger but slower compared to L1 and L2.  
  - Improves performance by reducing main memory (RAM) access.  

- **Motherboard:** the main circuit board that connects all components.

- **Chipset:**  
  A group of integrated circuits on the motherboard that manages communication between the CPU, memory, storage, and peripherals.  
  It determines system features such as supported CPUs, maximum RAM, number of USB/SATA/PCIe ports, and expansion options.  
  Modern chipsets are often divided into the **Northbridge** (CPU, RAM, GPU communication) and **Southbridge** (I/O, storage, peripherals), although newer CPUs integrate many Northbridge functions directly.

- **Motherboard Form Factor:**  
  The physical size, layout, and mounting specifications of a motherboard.  
  Common form factors include ATX, Micro-ATX, Mini-ITX, and E-ATX.  
  The form factor determines compatibility with cases, power supplies, and expansion slots.  

- **PCI Express (PCIe):**  
  A high-speed interface standard used to connect expansion cards such as graphics cards, SSDs, and network adapters.  
  PCIe uses serial communication with multiple lanes (x1, x4, x8, x16) to provide scalable bandwidth.  
  Newer versions (PCIe 3.0, 4.0, 5.0) offer increasing transfer speeds.  

- **Computer Assembly (Motherboard, CPU, GPU, RAM, Storage Installation):**  
  The process of installing and connecting all major hardware components inside the computer case.  

  ## 🔌 Ports and Connectors

- **USB (Universal Serial Bus):**  
  Standard connection used for peripherals like keyboards, mice, external drives.  
  - USB-A: traditional rectangular connector.  
  - USB-C: smaller, reversible, supports power delivery and fast data transfer.  
- **Ethernet (RJ-45):**  
  Port used to connect computers to wired networks. Provides faster and more stable connection than Wi-Fi.  
- **HDMI (High-Definition Multimedia Interface):**  
  Transmits high-quality video and audio from the computer to monitors, TVs, and projectors.  
- **DisplayPort:**  
  Similar to HDMI but often used in monitors for higher resolutions and refresh rates.  
- **Audio Jack (3.5mm):**  
  Port for headphones, microphones, and speakers.  
- **VGA (Video Graphics Array):**  
  Older video port used for monitors and projectors. Largely replaced by HDMI and DisplayPort.  
- **Thunderbolt:**  
  High-speed port (often using USB-C shape) for data transfer, video output, and power delivery.  

- **Mobile Devices:**  
  Portable computing devices such as smartphones, tablets, and laptops.  
  They integrate CPU, memory, storage, battery, and display in compact form factors.  
  Mobile devices rely heavily on low-power processors, integrated GPUs, and wireless connectivity (Wi-Fi, Bluetooth).  
  They often use solid-state storage and rechargeable batteries, and may have limited upgrade options compared to desktops.

- **Battery (Mobile Devices):**  
  A rechargeable component that powers smartphones, tablets, and laptops.  
  Most modern devices use **Lithium-ion (Li-ion)** or **Lithium-polymer (Li-Po)** batteries due to their high energy density and rechargeability.  
  Battery health decreases over time as it goes through **charge cycles**.

- **Charge Cycle:**  
  One full cycle of charging a battery from 0% to 100%.  
  Partial charges (e.g., 50% → 100% and later 50% → 100%) count as one full cycle when combined.  
  Typical smartphone batteries are rated for ~300–500 cycles before noticeable capacity loss, while laptops often handle ~500–1000 cycles.

- **Projector:**  
  An output device that projects visual content (images, videos, presentations) onto a larger surface, usually a screen or wall.  
  Projectors connect to computers or media players via video interfaces such as HDMI, VGA, or DisplayPort.  
  Commonly used in classrooms, offices, and home theaters.  
  Modern projectors often support high resolutions (Full HD, 4K) and wireless connectivity.

- **Driver:**  
  A software component that allows the operating system and applications to communicate with hardware devices.  
  Each device (e.g., printer, graphics card, keyboard) requires a driver to function properly.  
  Without the correct driver, the hardware may not work or may operate with limited functionality.  

- **BIOS (Basic Input/Output System):**  
  Firmware stored on the motherboard that initializes and tests hardware components during startup (POST — Power-On Self-Test).  
  It provides an interface for configuring system settings such as boot order, CPU features, and memory settings.  
  Modern systems often use **UEFI (Unified Extensible Firmware Interface)**, which replaces traditional BIOS with more advanced features, including graphical interfaces and support for larger storage devices.

- **CMOS (Complementary Metal-Oxide Semiconductor):**  
  A small memory chip on the motherboard that stores BIOS/UEFI configuration settings such as system time, boot order, and hardware parameters.  
  Powered by a small battery (CMOS battery), it retains these settings when the computer is turned off.  
  If the battery fails, settings reset to defaults and the system clock may lose time.

- **LCD (Liquid Crystal Display):**  
  Flat-panel display technology that uses liquid crystals and a backlight to produce images. Widely used in monitors, TVs, and laptops.  

- **TN (Twisted Nematic):**  
  LCD subtype with very fast response times and low cost, but limited color accuracy and narrow viewing angles. Popular in budget gaming monitors.  

- **IPS (In-Plane Switching):**  
  LCD subtype with accurate colors and wide viewing angles (~178°). Preferred for professional monitors and notebooks. Slightly lower contrast than VA and may show “IPS glow” in dark scenes.  

- **VA (Vertical Alignment):**  
  LCD subtype with high contrast and deeper blacks than IPS or TN. Slower response times but common in TVs and mid-range monitors.  

- **OLED (Organic Light-Emitting Diode):**  
  Self-emissive technology where each pixel produces its own light. Excellent contrast, true blacks, and wide viewing angles. Can suffer from burn-in.  

- **AMOLED (Active-Matrix OLED):**  
  OLED variation designed for mobile devices. Thinner, energy-efficient, with fast response. Common in smartphones and tablets.  

- **Mini-LED:**  
  Advanced LCD backlight technology using thousands of tiny LEDs. Offers higher brightness and HDR performance compared to standard LED backlighting.  

- **MicroLED:**  
  Next-gen self-emissive technology where each pixel is a microscopic LED. Combines OLED quality with higher brightness, durability, and no burn-in. Currently expensive and limited to prototypes/premium displays.  

- **Data Sizes (Bits and Bytes):**  
  Fundamental units of digital information.  
  - 1 bit = smallest data unit (0 or 1).  
  - 1 byte = 8 bits.  
  - 1 KB = 1024 bytes, 1 MB = 1024 KB, 1 GB = 1024 MB, etc.  
  Used to measure memory, storage, and data transfer sizes.  

- **Desktop (Área de Trabalho):**  
  The main graphical interface of an operating system where icons, files, and applications are displayed. Provides easy access to frequently used tools and resources.  

- **DIMM (Dual Inline Memory Module):**  
  A physical module containing RAM chips, inserted into motherboard memory slots. DIMMs have separate electrical contacts on each side and come in types like DDR3, DDR4, DDR5.  

- **Driver:**  
  Software that allows the operating system and applications to communicate with hardware devices (e.g., printer, GPU). Without drivers, hardware may not function correctly.  

- **ESD (Electrostatic Discharge):**  
  A sudden flow of electricity caused by static buildup. Can damage sensitive components like CPUs and RAM during installation. Anti-static wrist straps and grounding are used to prevent ESD.  

- **Heatsink (Dissipador de Calor):**  
  A passive cooling device made of metal fins that absorbs and disperses heat from components like the CPU or GPU, often paired with a fan.  

- **Instruction Set (ISA — Instruction Set Architecture):**  
  The set of machine-level commands a CPU can execute (e.g., arithmetic, logic, control). Examples: x86, ARM, RISC-V. Determines software compatibility with processors.  

- **PGA (Pin Grid Array):**  
  A CPU packaging type where pins are arranged in a grid on the underside of the processor. Fits into a socket with matching holes (commonly used by AMD CPUs).  

- **POST (Power-On Self-Test):**  
  A diagnostic test run by the BIOS/UEFI at startup to check hardware components (CPU, RAM, storage, GPU) before loading the operating system.  

- **System Image Restore (Restaurar Imagem):**  
  A recovery process that restores a computer system from a backup image, returning OS and files to a previous working state.  

- **SoC (System on a Chip):**  
  An integrated circuit that combines CPU, GPU, memory, and other components into a single chip. Common in smartphones, tablets, and some compact PCs.  

- **Thermal Paste (Pasta Térmica):**  
  A conductive material applied between CPU/GPU and a heatsink to improve heat transfer and cooling efficiency.  

- **UEFI (Unified Extensible Firmware Interface):**  
  Modern replacement for BIOS, providing a graphical interface, faster boot times, support for large storage (>2 TB), and advanced security features (e.g., Secure Boot).
