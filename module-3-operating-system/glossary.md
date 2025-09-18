# 📘 Glossary – Module 3: Operating System

### Operating System (OS)
System software that manages hardware resources and provides services for applications.  
Functions include process management, memory management, file systems, input/output device control, user interaction, and security.  
Examples: Windows, Linux, macOS, Chrome OS, Android, iOS.

### Components of an Operating System
The main modules that make up an OS, responsible for managing and coordinating system resources:  
- **Kernel**: Core of the OS, controls CPU, memory, and device drivers.  
- **Process Management**: Schedules and handles the execution of processes.  
- **Memory Management**: Allocates RAM and manages virtual memory.  
- **File System Management**: Organizes, stores, and retrieves data.  
- **I/O Management**: Handles communication between hardware devices and applications.  
- **User Interface**: Provides ways for users to interact with the OS (CLI or GUI).  

### Different Types of Operating Systems
Operating systems vary according to their target devices and use cases:  

- **Windows**: Widely used desktop OS developed by Microsoft. Known for user-friendly GUI, broad software support, and enterprise usage.  
- **Linux**: Open-source OS kernel with many distributions (Ubuntu, Fedora, Debian). Known for stability, security, and server usage.  
- **macOS**: Apple’s desktop OS, designed for Mac computers. Known for integration with Apple hardware and ecosystem.  
- **Android**: Open-source mobile OS based on Linux, developed by Google. Dominant in smartphones and tablets.  
- **iOS**: Apple’s mobile OS for iPhones and iPads. Known for security, simplicity, and exclusive app ecosystem.  
- **Chrome OS**: Lightweight OS by Google, based on Linux and designed for web/cloud-based applications.  

### Files
A file is a collection of data stored on a computer system.  
- Can contain text, images, audio, video, or software instructions.  
- Identified by a file name and extension (e.g., `report.docx`, `photo.png`).  
- Managed by the operating system through the file system.  

### Folders (Directories)
A folder, also called a directory, is a container used to organize files and other folders.  
- Helps structure data storage in a hierarchical way.  
- Allows grouping of related files together.  
- Examples: `Documents`, `Downloads`, `Pictures`.  

### Kernel
The **kernel** is the core component of an operating system.  
- It operates at the lowest level of the OS, directly interacting with hardware.  
- Responsible for managing CPU, memory, and device drivers.  
- Provides essential services such as process scheduling, resource allocation, and hardware abstraction.  
- Types of kernels include **monolithic kernels** (all services in one layer) and **microkernels** (minimal core, services run in user space).  

### File Systems
A **file system** is the method and structure that an operating system uses to organize, store, and retrieve files on a storage device.  
- Defines how data is named, stored, and accessed.  
- Common file systems include **NTFS** (Windows), **FAT32** (older Windows and external drives), **ext4** (Linux), **APFS** (macOS), and **HFS+** (older macOS).  
- Provides features such as permissions, metadata, directories, and indexing.  
- Plays a crucial role in performance, reliability, and security of data storage.  

### Block Storage
**Block storage** is a data storage method where data is stored in fixed-size units called *blocks*.  
- Each block has a unique address, and the operating system retrieves or writes data by addressing these blocks.  
- Commonly used in hard drives (HDDs), solid-state drives (SSDs), and SAN (Storage Area Networks).  
- Provides high performance and flexibility since files are split into blocks that can be distributed across disks.  
- File systems are built on top of block storage to provide structure and organization.  

### Metadata
**Metadata** is data that provides information about other data.  
- In file systems, metadata describes file attributes such as name, size, type, creation date, modification date, and permissions.  
- Helps the operating system manage, organize, and search files efficiently.  
- Does not contain the file’s actual content but essential details for identification and access control.  

### File Extension
A **file extension** is the suffix at the end of a file name that indicates its format and the type of data it contains.  
- Usually consists of 2–4 characters after a dot (e.g., `.txt`, `.jpg`, `.exe`).  
- Helps the operating system determine which program should open the file.  
- Some file extensions are associated with specific applications, while others are standard across multiple platforms.  

### Process Management
**Process Management** is a core function of the operating system that handles the execution of programs.  
- Creates, schedules, and terminates processes.  
- Allocates CPU time and system resources to active processes.  
- Ensures multitasking by managing process states (ready, running, waiting).  
- Uses scheduling algorithms to balance efficiency and fairness.  

### Time Slice
A **time slice** (also called a time quantum) is the fixed amount of CPU time allocated to a process in a multitasking operating system.  
- Determines how long a process can run before the CPU switches to another process.  
- Used in preemptive scheduling to ensure fair CPU sharing among processes.  
- The length of the time slice affects performance:  
  - Too short → overhead from frequent context switching.  
  - Too long → poor responsiveness for other processes.  

### Virtual Memory
**Virtual memory** is a memory management technique that gives applications the illusion of having a large, continuous block of memory, regardless of the physical RAM available.  
- Uses both RAM and disk storage to extend available memory.  
- Allows multiple programs to run simultaneously without interfering with each other.  
- Implements mechanisms like **paging** and **segmentation** to map virtual addresses to physical addresses.  
- Can reduce performance when excessive disk swapping occurs, a situation known as **thrashing**.  

### I/O Devices
**Input/Output (I/O) devices** are hardware components that allow a computer system to communicate with the external world.  
- **Input devices**: Send data to the computer (e.g., keyboard, mouse, scanner, microphone).  
- **Output devices**: Receive data from the computer (e.g., monitor, printer, speakers).  
- **Storage devices**: Can serve as both input and output (e.g., hard drives, SSDs, USB drives).  
- Managed by the operating system through **device drivers**, which provide the interface between hardware and software.  

### Shell
A **shell** is a user interface that allows interaction with the operating system by entering commands.  
- Acts as a bridge between the user and the OS kernel.  
- Can be **command-line based** (CLI), such as Bash, PowerShell, or Zsh.  
- Can also be **graphical** (GUI shells), providing windows, icons, and menus for interaction.  
- Interprets user commands and translates them into actions performed by the OS.  

### Logs
**Logs** are records automatically generated by an operating system or applications to document events, activities, and errors.  
- Help administrators monitor system performance and troubleshoot issues.  
- Common types include **system logs**, **application logs**, and **security logs**.  
- Typically stored as plain text files and managed by logging services (e.g., syslog in Linux, Event Viewer in Windows).  
- Provide valuable information for auditing and detecting anomalies.  

### Bootloader
A **bootloader** is a small program that runs when a computer is powered on and is responsible for loading the operating system into memory.  
- Initializes hardware components and prepares the system for the OS.  
- Typically stored in the system’s firmware or on the first sector of a storage device.  
- Examples include **GRUB** (Linux) and **Windows Boot Manager**.  
- Without a bootloader, the operating system cannot start.  

### Boot Process
The **boot process** is the sequence of steps a computer follows to start the operating system after being powered on:  

1. **Power On** → The system receives electrical power and begins startup.  
2. **BIOS/UEFI** → Firmware initializes hardware components and runs the **POST (Power-On Self-Test)** to check system health.  
3. **Boot Device Selection** → The firmware locates a valid boot device (e.g., hard drive, USB, CD/DVD).  
4. **Bootloader** → A small program on the boot device that loads the operating system into memory.  
5. **Operating System (OS)** → Once loaded, the OS takes control and provides the user environment.  

### Mobile Operating Systems
**Mobile operating systems** are specialized OSs designed to run on mobile devices such as smartphones and tablets.  
- Provide efficient power management and support for touch-based interfaces.  
- Include features such as wireless connectivity (Wi-Fi, Bluetooth, cellular), GPS, and app stores.  
- Popular examples: **Android** (developed by Google) and **iOS** (developed by Apple).  
- Focus on portability, ease of use, and integration with mobile hardware.  

### User Space
**User space** is the portion of system memory where user applications and processes run, separated from the kernel space.  
- Prevents direct access to hardware, improving system stability and security.  
- Applications in user space request services from the kernel using **system calls**.  
- Errors in user space usually affect only the application, not the entire operating system.  

### Choosing an Operating System
**Choosing an operating system** involves evaluating which OS best fits the user’s or organization’s needs.  
- Considerations include hardware compatibility, cost, ease of use, security, performance, and software availability.  
- **Windows**: Strong compatibility with most software and hardware, widely used in business.  
- **Linux**: Free, open-source, secure, and customizable, often used in servers and development.  
- **macOS**: Optimized for Apple hardware, strong integration with the Apple ecosystem.  
- **Mobile OSs** (Android, iOS): Designed for portability, app ecosystems, and mobile hardware.  
- The best choice depends on the intended use case (personal, enterprise, development, or mobile).  

### Virtual Machine (VM)
A **Virtual Machine (VM)** is a software-based emulation of a physical computer.  
- Runs an operating system and applications in an isolated environment.  
- Uses a **hypervisor** to allocate resources (CPU, memory, storage) from the host machine.  
- Enables running multiple OSs on the same hardware simultaneously.  
- Commonly used for testing, development, cloud computing, and server consolidation.  

### Windows 11 Installation
**Windows 11 installation** is the process of setting up Microsoft’s latest desktop operating system on a computer.  
- Requires compatible hardware that meets Microsoft’s system requirements (e.g., TPM 2.0, Secure Boot).  
- Can be performed through installation media such as a bootable USB drive or ISO image.  
- Steps include selecting language and region, choosing partitions, and configuring user accounts.  
- After installation, updates and drivers are typically installed to ensure stability and performance.  

### Differences Between Windows 10 and Windows 11
**Windows 11** introduced several changes compared to **Windows 10**, focusing on design, performance, and security:  
- **User Interface**: Windows 11 features a redesigned interface with centered Start Menu, rounded corners, and new icons.  
- **Performance**: Improved memory management, faster wake-from-sleep, and better optimization for hybrid processors.  
- **Gaming**: Includes technologies like DirectStorage and Auto HDR for enhanced gaming performance.  
- **Security**: Requires hardware features such as TPM 2.0 and Secure Boot for installation.  
- **Compatibility**: Some older hardware that supports Windows 10 cannot run Windows 11.  
- **Multitasking**: Snap Layouts and Snap Groups provide more flexible window management.  

### Linux Installation
**Linux installation** is the process of setting up a Linux-based operating system (distribution) on a computer.  
- Popular distributions include **Ubuntu**, **Fedora**, **Debian**, and **Arch Linux**.  
- Can be installed alongside another OS (dual boot), on a virtual machine, or as the only OS on the system.  
- Steps include creating a bootable USB/DVD, partitioning storage, and selecting packages.  
- Provides flexibility, open-source customization, and a wide range of desktop environments (e.g., GNOME, KDE).  
- Often used for servers, development, and cybersecurity due to stability and security.  

### Chrome OS
**Chrome OS** is a lightweight operating system developed by Google, based on the Linux kernel.  
- Designed primarily for use with web applications and cloud storage.  
- Runs on Chromebooks and other compatible devices.  
- Focuses on speed, simplicity, and security, with most apps accessed through the **Chrome browser**.  
- Supports Android apps and Linux applications on newer versions.  
- Relies heavily on internet connectivity but also offers offline functionality for certain apps.  

### macOS
**macOS** is the desktop operating system developed by Apple for Mac computers.  
- Based on Unix, providing strong stability and security.  
- Known for its polished graphical user interface and seamless integration with Apple’s ecosystem (iPhone, iPad, Apple Watch).  
- Uses the **APFS (Apple File System)** for efficient storage management.  
- Comes with built-in applications like Safari, Finder, and Spotlight.  
- Popular among creative professionals for design, video editing, and music production.  

### Qwiklabs
**Qwiklabs** is an online learning platform that provides hands-on labs for cloud computing and IT skills.  
- Allows users to practice in real cloud environments (Google Cloud, AWS) without needing a personal account or setup.  
- Offers temporary credentials to complete guided labs and exercises.  
- Commonly used in IT training programs to teach cloud services, operating systems, and troubleshooting.  
- Helps learners gain practical experience with real-world tools and scenarios.  
