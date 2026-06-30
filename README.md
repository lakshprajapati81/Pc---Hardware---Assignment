# Desktop PC Hardware Assignment

# DAY - 1: Overview of Hardware Components

## 1. Labeled Diagram of a Desktop PC

```mermaid
flowchart TB
    PC[Desktop PC Cabinet]

    PC --> MB[Motherboard]
    MB --> CPU[CPU / Processor]
    MB --> RAM[RAM]
    MB --> GPU[GPU / Graphics Card]
    PC --> HDD[HDD Storage]
    PC --> SSD[SSD Storage]

    CPU --> CPUWork[Processes instructions and controls tasks]
    RAM --> RAMWork[Stores temporary data while programs run]
    GPU --> GPUWork[Handles graphics and game visuals]
    HDD --> HDDWork[Stores large files, games, videos, and backups]
    SSD --> SSDWork[Fast storage for OS, apps, and games]
```

The motherboard is the main circuit board of the desktop PC. The CPU, RAM, GPU, HDD, and SSD are connected directly or indirectly to the motherboard.

This is a labeled block diagram of a desktop PC showing the main internal hardware components.
---

## 2. Difference Between HDD and SSD

| Feature           | HDD                                                         | SSD                                                        |
| ----------------- | ----------------------------------------------------------- | ---------------------------------------------------------- |
| Full Form         | Hard Disk Drive                                             | Solid State Drive                                          |
| Speed             | Slower because it uses moving mechanical parts              | Faster because it uses flash memory                        |
| Durability        | Less durable because it can be damaged by shock or movement | More durable because it has no moving parts                |
| Noise             | Can make noise due to spinning disk                         | Silent operation                                           |
| Cost              | Cheaper for large storage                                   | More expensive than HDD                                    |
| Typical Use Cases | Storing movies, documents, backups, and large files         | Installing operating system, games, and important software |
| Best For          | Large storage at low cost                                   | High speed and better performance                          |

---

## 3. Role of CPU, RAM, and GPU in Running Games Like PUBG or Free Fire

### CPU

The CPU is the brain of the computer. In games like PUBG or Free Fire, it handles game logic, player movement, enemy actions, controls, and background calculations.

### RAM

RAM stores temporary data while the game is running. More RAM helps the game load faster, reduces lag, and allows smooth multitasking while playing.

### GPU

The GPU handles graphics and visuals in the game. It is responsible for rendering characters, maps, shadows, textures, and smooth frame rates.

---

## 4. Hardware Upgrades for Running the Latest Version of FIFA Smoothly

To run the latest version of FIFA smoothly, I would consider upgrading the following components:

### 1. GPU / Graphics Card

The GPU is very important for gaming performance. Upgrading the GPU helps improve graphics quality, frame rate, and smooth gameplay.

### 2. RAM

Upgrading RAM helps the game run smoothly without lag. For modern games, at least 8 GB RAM is needed, but 16 GB RAM is better for smooth performance.

### 3. SSD

Installing FIFA on an SSD reduces loading time and improves overall system speed. An SSD is much faster than an HDD.

### 4. CPU / Processor

A better CPU helps in faster processing of game logic, physics, and background tasks. If the CPU is old, the game may lag even with a good GPU.

### 5. Power Supply Unit

If a powerful GPU is added, a better power supply may be required. A good PSU gives stable power to all components and protects the PC.

### 6. Cooling System

Gaming creates heat inside the PC. Better cooling helps maintain performance and prevents overheating during long gaming sessions.

---


# DAY - 2: Motherboard and CPU

## 1. Labeled Diagram of an ATX Motherboard

```mermaid
flowchart TB
    MB[ATX Motherboard]

    MB --> CPU[CPU Socket]
    MB --> RAM[RAM / DIMM Slots]
    MB --> PCIE16[PCIe x16 Slot]
    MB --> PCIE1[PCIe x1 Slot]
    MB --> SATA[SATA Ports]
    MB --> M2[M.2 Slot]
    MB --> USB[USB Headers]
    MB --> ATX24[24-pin ATX Power Connector]
    MB --> CPU8[8-pin CPU Power Connector]
    MB --> IO[Rear I/O Panel]
    MB --> CHIP[Chipset]

    CPU --> CPUUse[Processor is installed here]
    RAM --> RAMUse[RAM modules are installed here]
    PCIE16 --> GPUUse[Used for GPU / Graphics Card]
    PCIE1 --> CardUse[Used for Wi-Fi or sound card]
    SATA --> StorageUse[Used to connect HDD or SATA SSD]
    M2 --> SSDUse[Used for NVMe SSD]
    USB --> FrontUSB[Connects front panel USB ports]
    ATX24 --> PowerUse[Main power supply to motherboard]
    CPU8 --> CPUPower[Extra power for CPU]
    IO --> PortUse[USB, LAN, audio, HDMI ports]
    CHIP --> ChipsetUse[Controls communication between components]
```

### Labeled Parts Marked in the Diagram

1. CPU Socket  
2. RAM / DIMM Slots  
3. PCIe x16 Slot  
4. PCIe x1 Slot  
5. SATA Ports  
6. M.2 Slot  
7. USB Headers  
8. 24-pin ATX Power Connector  
9. 8-pin CPU Power Connector  
10. Rear I/O Panel  
11. Chipset  

---

## 2. Popular CPU Socket Types and Compatible CPU Models

| CPU Socket Type | Compatible CPU Model | Description |
|---|---|---|
| LGA1151 | Intel Core i5-9400F | Used with many Intel 8th and 9th generation desktop processors |
| AM4 | AMD Ryzen 5 5600 | Used with many AMD Ryzen desktop processors |
| LGA1200 | Intel Core i5-10400 | Used with many Intel 10th and 11th generation desktop processors |

---

## 3. Functions of CPU and Chipset

### CPU

The CPU is the main processing unit of the computer. It performs calculations, runs instructions, and controls the main tasks of the system. When we open an application like Spotify, the CPU processes the command and starts the application.

### Chipset

The chipset is an important part of the motherboard that helps different components communicate with each other. It manages data flow between the CPU, RAM, storage devices, USB ports, and other hardware. It works like a traffic controller on the motherboard.

### How CPU and Chipset Work Together When Opening Spotify

When we open Spotify, the CPU starts processing the application instructions. The chipset helps the CPU access data from the SSD or HDD and sends the required data to RAM. It also manages communication with audio hardware, USB devices, internet/LAN, and other motherboard components so that Spotify can open and play music smoothly.

---

## 4. Real Motherboard Photo With Labeled Ports and Slots

I used a real motherboard photo and identified different ports and slots by circling and labeling them.

### Identified Motherboard Parts

| Label | Motherboard Part | Use |
|---|---|---|
| 1 | CPU Socket | Used to install the processor |
| 2 | RAM / DIMM Slots | Used to install RAM modules |
| 3 | 24-pin ATX Power Connector | Provides main power to the motherboard |
| 4 | PCIe x16 Slot | Used to install a graphics card |
| 5 | M.2 / NVMe SSD Slot | Used to install a fast NVMe SSD |
| 6 | SATA Ports | Used to connect HDD or SATA SSD |
| 7 | Rear I/O Ports | Used for USB, LAN, audio, and display ports |
| 8 | Chipset Heatsink | Helps cool and protect the chipset |
| 9 | CMOS Battery | Stores BIOS settings and system time |
| 10 | 8-pin CPU Power Connector | Provides extra power to the CPU |

### Labeled Motherboard Image

![Labeled Motherboard](./Motherboard%20Labelled.png)

---

# DAY - 3: RAM and Storage

---

# DAY - 3: RAM and Storage

## 1. Comparison Table: DDR3, DDR4, and DDR5 RAM

| Feature | DDR3 RAM | DDR4 RAM | DDR5 RAM |
|---|---|---|---|
| Full Form | Double Data Rate 3 | Double Data Rate 4 | Double Data Rate 5 |
| Speed | Lower speed compared to DDR4 and DDR5 | Faster than DDR3 | Fastest among DDR3, DDR4, and DDR5 |
| Typical Speed Range | Around 800 MHz to 2133 MHz | Around 2133 MHz to 3200 MHz or higher | Around 4800 MHz and higher |
| Voltage | Around 1.5V | Around 1.2V | Around 1.1V |
| Power Efficiency | Less power efficient | More power efficient than DDR3 | Most power efficient |
| Performance | Suitable for basic computing | Good for modern PCs and gaming | Best for high-performance gaming, editing, and professional work |
| Typical Use Cases | Older desktops and laptops | Modern desktops, laptops, and gaming PCs | Latest high-end desktops, laptops, gaming PCs, and workstations |
| Compatibility | Works only with DDR3-supported motherboard | Works only with DDR4-supported motherboard | Works only with DDR5-supported motherboard |

---

## 2. Practical: RAM Slot Identification and Reinstallation

### Safety Steps Followed

Before opening the laptop or desktop, I followed these safety steps:

1. Shut down the computer completely.
2. Disconnected the power cable or charger.
3. Pressed the power button for a few seconds to discharge remaining power.
4. Opened the back panel or cabinet carefully.
5. Located the RAM slot and RAM module.
6. Removed and reinstalled the RAM module properly.
7. Closed the system and turned it on again.
8. Verified that the system booted successfully.

### RAM Module Reference Image

I performed the RAM practical in front of my instructor.  
At home, I could not reopen my laptop because proper tools were not available, so I used this reference image for documentation.

![RAM Module Reference](./ram-module.jpg)


### Boot Verification

After reinstalling the RAM module, the system booted successfully. This confirms that the RAM was installed properly.

---

## 3. Differences Between HDD, SSD, and NVMe Storage

| Feature | HDD | SSD | NVMe |
|---|---|---|---|
| Full Form | Hard Disk Drive | Solid State Drive | Non-Volatile Memory Express |
| Speed | Slowest because it uses spinning disks | Faster than HDD because it uses flash memory | Fastest because it uses PCIe lanes |
| Connection Type | Usually SATA | Usually SATA | Usually M.2 PCIe |
| Moving Parts | Has moving mechanical parts | No moving parts | No moving parts |
| Durability | Less durable because shock can damage it | More durable than HDD | More durable and faster |
| Cost | Cheapest for large storage | Medium cost | More expensive than SATA SSD |
| Best Use | Large file storage and backups | Operating system, apps, and games | High-speed gaming, editing, and heavy applications |

### Daily App / Use Case Examples

| Storage Type | Best Daily Use Case | Example App |
|---|---|---|
| HDD | Storing large videos, movies, photos, and backups | Google Drive backup files / downloaded movies |
| SSD | Faster booting and smooth app opening | Windows, Chrome, VS Code |
| NVMe | Very fast loading for heavy apps and games | GTA V, FIFA, PUBG PC, video editing software |

---

## 4. Practical: Storage Drive Connector Identification and Reinstallation

### Safety Steps Followed

Before removing the storage drive, I followed these safety steps:

1. Shut down the computer completely.
2. Disconnected the power cable or charger.
3. Opened the laptop back panel or desktop cabinet carefully.
4. Located the storage drive.
5. Identified the connector type such as SATA, M.2, or NVMe.
6. Removed and reinstalled the storage drive carefully.
7. Closed the system and turned it on.
8. Verified that the device recognized the storage after reassembly.


### Storage Connector Reference Image

I performed the storage identification practical in front of my instructor.  
At home, I could not reopen my laptop because proper tools were not available, so I used this reference image to show the storage connector clearly.

![Storage Connector Reference](./storage-connector.jpg)

### Storage Recognition Confirmation

After reinstalling the storage drive, the device recognized the storage successfully. This confirms that the storage drive was connected properly.

### Practical Note

I performed the RAM and storage identification practical in front of my instructor.  
However, I could not reopen my personal laptop at home because I did not have the proper tools.  
So, for documentation, I used reference images to show the RAM slot and storage connector clearly.

---

---

---

# DAY - 5: Assemble and Disassemble a PC

## 1. Main Components Inside a Desktop PC

After opening a desktop PC cabinet, the following main components can be found:

| No. | Component | Short Description |
|---|---|---|
| 1 | Motherboard | The main circuit board that connects all computer components together. |
| 2 | CPU / Processor | The brain of the computer that performs calculations and executes instructions. |
| 3 | RAM | Temporary memory used to store data while programs are running. |
| 4 | HDD / SSD | Storage devices used to store the operating system, software, and files. |
| 5 | GPU / Graphics Card | Handles graphics processing, gaming visuals, and video output. |
| 6 | Power Supply Unit | Converts AC power into DC power and supplies power to all components. |
| 7 | Cooling Fan | Removes hot air and keeps the system temperature under control. |
| 8 | Heatsink | Absorbs heat from CPU/GPU and helps in cooling. |
| 9 | SATA Cables | Connect storage devices like HDD and SATA SSD to the motherboard. |
| 10 | Cabinet / Case | Holds and protects all internal components of the desktop PC. |
| 11 | CMOS Battery | Stores BIOS settings and system time. |
| 12 | Front Panel Connectors | Connect the power button, reset button, USB ports, and LED indicators to the motherboard. |

---

## 2. Desktop PC Disassembly Process

### Practical Note

I performed the PC assembly and disassembly practical during the hands-on session.  
For documentation, I used one combined labeled image showing all important disassembly steps in proper order.

### Combined Labeled Image of PC Disassembly Steps

![PC Assembly and Disassembly Steps](./assembly-disassembly.png)

### Steps Shown in the Image

| Step | Process | Short Explanation |
|---|---|---|
| 1 | Power Off and Unplug | Turn off the PC and remove the power cable before opening the cabinet. |
| 2 | Remove Side Panel | Remove the screws and slide off the side panel to access internal components. |
| 3 | Identify Components | Identify CPU cooler, RAM, motherboard, GPU, storage drive, and power supply. |
| 4 | Disconnect Cables | Disconnect power and data cables carefully from internal components. |
| 5 | Remove RAM | Open the RAM slot clips and remove the RAM module gently. |
| 6 | Remove HDD / SSD | Unscrew the storage drive and disconnect SATA and power cables. |
| 7 | Remove GPU | Remove the GPU screw, unlock the PCIe slot, and take out the graphics card carefully. |
| 8 | Remove Motherboard | Disconnect remaining cables, unscrew the motherboard, and remove it carefully. |

---

## 3. Desktop PC Reassembly Process

### Step 1: Install the Motherboard

I placed the motherboard properly inside the cabinet and tightened the screws.

**Why order matters:** The motherboard should be installed first because most components connect to it.

---

### Step 2: Install CPU Cooler / Fan

I checked the CPU cooling fan and connected it to the CPU fan header.

**Why order matters:** The CPU must have proper cooling before the system is turned on.

---

### Step 3: Install RAM Module

I inserted the RAM module into the RAM slot and pressed it until the side clips locked.

**Why order matters:** RAM is required for the system to boot successfully.

---

### Step 4: Install HDD / SSD

I placed the HDD/SSD in the drive bay and connected the SATA data cable and SATA power cable.

**Why order matters:** Storage must be connected so the system can load the operating system and files.

---

### Step 5: Install GPU / Expansion Card

I inserted the GPU into the PCIe x16 slot and secured it with a screw.

**Why order matters:** The GPU is needed for display output and graphics performance if the system uses a dedicated graphics card.

---

### Step 6: Connect Power Cables

I connected the 24-pin ATX motherboard power connector and CPU power connector.

**Why order matters:** These power connections are necessary for the motherboard and CPU to work.

---

### Step 7: Connect Front Panel and USB Cables

I connected the power button, reset button, LED indicators, and front USB connectors.

**Why order matters:** These connections allow the cabinet buttons and front ports to work.

---

### Step 8: Final Check and Boot Test

I checked all connections, closed the side panel, connected the power cable, and turned on the PC.

**Result:** The PC booted successfully after reassembly.

---

## 4. Safety Precautions and Tools Checklist

### Tools Required

| Tool | Use |
|---|---|
| Screwdriver | Used to open cabinet screws and remove/install components. |
| Anti-static wrist strap | Protects components from static electricity damage. |
| Small container | Used to keep screws safely in one place. |
| Soft brush | Used to clean dust from components. |
| Microfiber cloth | Used for safe cleaning without scratching parts. |
| Flashlight | Helps to clearly see small connectors and slots. |
| User manual / motherboard manual | Helps identify correct slots, connectors, and cable positions. |

---

### Safety Precautions

| Safety Precaution | Why It Is Important |
|---|---|
| Shut down the PC completely | Prevents data loss and electrical issues. |
| Disconnect power cable | Protects from electric shock and short circuit. |
| Press power button after unplugging | Removes remaining power from the system. |
| Work on a clean and dry surface | Prevents dust, water, and accidental damage. |
| Handle components by edges | Avoids damage to circuits and gold contacts. |
| Do not force any component | Prevents breaking slots, pins, or connectors. |
| Keep screws organized | Helps during reassembly and avoids missing screws. |
| Avoid touching motherboard circuits | Prevents static discharge and physical damage. |
| Take photos before disconnecting cables | Helps remember cable positions during reassembly. |
| Check all connections before power on | Prevents boot failure or component damage. |

---

## Labeled Diagram of PC Assembly and Disassembly Flow

```mermaid
flowchart TD
    A[Start] --> B[Shut Down PC]
    B --> C[Disconnect Power Cable]
    C --> D[Remove Side Panel]
    D --> E[Identify Components]
    E --> F[Disconnect Cables]
    F --> G[Remove RAM]
    G --> H[Remove HDD / SSD]
    H --> I[Remove GPU]
    I --> J[Remove Motherboard]
    J --> K[Clean and Inspect Components]
    K --> L[Reinstall Motherboard]
    L --> M[Install RAM]
    M --> N[Install Storage Drive]
    N --> O[Install GPU]
    O --> P[Connect Power and Data Cables]
    P --> Q[Close Cabinet]
    Q --> R[Boot Test]
    R --> S[Process Completed]
```

