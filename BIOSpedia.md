# BIOS
- [Tweaker](#Tweaker)
  - [Advanced CPU Settigns](#Advanced-CPU-Settigns)
  - [Advanced Memory Settigns](#Advanced-Memory-Settigns)
    - [Memory Subtimings](#Memory-Subtimings)
    - [SPD Info](#SPD-Info)
  - [CPU-VRM Settings](#CPU-VRM-Settings)
- [Settings](#Settings)
  - [Platform Power](#Platform-Power)
  - [IO Ports](#IO-Ports)
    - [Intel® I211 Gigabit Network Connection](#Intel®-I211-Gigabit-Network-Connection)
      - [NIC Configuration](#NIC-Configuration)
    - [Network Stack Configuration](#Network-Stack-Configuration)
    - [NVMe Configuration](#NVMe-Configuration)
      - [Samsung SSD 970 EVO Plus 250GB](#Samsung-SSD-970-EVO-Plus-250GB)
    - [SATA Configuration](#SATA-Configuration)
    - [USB Configuration](#USB-Configuration)
  - [Miscellaneous](#Miscellaneous)
    - [Trusted Computing](#Trusted-Computing)
  - [AMD CBS](#memory-testing-software)
    - [CPU Common Options](#CPU-Common-Options)
      - [Performance](#Performance)
        - [Custom Core Pstates](#Custom-Core-Pstates)
      - [Prefetcher settings](#Prefetcher-settings)
      - [Core Watchdog](#Core-Watchdog)
    - Custom Core Pstates
    - [DF Common Options](#DF-Common-Options)
      - [Scrubber](#Scrubber)
      - [Memory Adressing](#Memory-Adressing)
      - [ACPI](#ACPI)
      - [Link](#Link)
    - [NBIO Common Options](#NBIO-Common-Options)
      - [XFR Enhancement](#XFR-Enhancement)
      - [SMU Common Options](#SMU-Common-Options)
        - [Fan Control](#Fan-Control)
        - [NBIO LCLK DPM](#NBIO-LCLK-DPM)
    - [UMC Common Options](#UMC-Common-Options)
      - [DDR4 Common Options](#DDR4-Common-Options)
        - [DRAM Timing Configuration](#DRAM-Timing-Configuration)
        - [DRAM Controller Configuration](#DRAM-Controller-Configuration)
          - [DRAM Power Options](#DRAM-Power-Options) 
        - [CAD Bus Configuration](#CAD-Bus-Configuration)
        - [Data Bus Configuration](#Data-Bus-Configuration)
        - [Common RAS](#Common-RAS)
          - [ECC Configuration](#ECC-Configuration)
        - [Security](#Security)
        - [Phy Configuration](#Phy-Configuration)
          - [PMU Training](#PMU-Training)
      - [DRAM Memory Mapping](#DRAM-Memory-Mapping)
      - [Memory MBIST](#Memory-MBIST)
        - [Data Eye](#Data-Eye)
      - [NVDIMM](#NVDIMM)
    - XFR Enhancement
  - [AMD Overclocking](#AMD-Overclocking)
    - [Manual CPU Overclocking](#Manual-CPU-Overclocking)
    - [DDR and Infinity Fabric Frequency/Timings](#DDR-and-Infinity-Fabric-Frequency/Timings)
      - DRAM Timing Configuration
      - [DRAM Controller Configuration](#DRAM-Controller-Configuration)
      - CAD Bus Configuration
      - [Data Bus Configuration](#Data-Bus-Configuration)
  - [PC Health](#PC-Health)
  - [Smart Fan 5](#Smart-Fan-5)
- [System Info](#System-Info)
- [Boot](#Boot)
  - [Secure Boot](#Secure-Boot)
    - [Key Managment](#Key-Managment)

[Sources](#Sources)

# Tweaker
* CPU Clock Control
* Spread Spectrum Control
* CPU Ratio Mode
* CPU Clock Ratio
* Precision Boost Overdrive
  * PBO Limits
    * PPT Limit [W] 
    * TDC Limit [A]
    * EDC Limit [A]
  * Precision Boost Overdrive Scalar
    * Precision Boost Overdrive Scalar
  * Max CPU Boost Clock Override

<details><summary id="Advanced CPU Settings"><h2>Advanced CPU Settings</h2></summary>

* Core Performance Boost
* SVM
* AMD Cool&Quiet fuction
* Global C-state Control
* Power Supply Idle Control
* CCD Control
* Downcore Control
* SMT Mode
* CPPC
* CPPC Preferred Cores</details>

___
* Extreme Memory Profile(X.M.P.)
* XMP High Frequency Support
* System Memory Multiplier
* FCLK Frequency
* UCLK DIV1 MODE

<details><summary id="Advanced Memory Settigns"><h2>Advanced Memory Settigns</h2></summary>

### Memory Subtimings
* CAS Latency
* tRCDRD
* tRCDWR
* tRP
* tRAS
* tRC
* tWR
* tCWL
* tRRD_S
* tRRD_L
* tWTR_S
* tWTR_L
* tRFC
* tRFC2
* tRFC4
* tRTP
* tFAW
* tRCPAGE
* tRDWR
* tRDRDSC
* tRDRDSD
* tRDRDDD
* tRDRD_SCL
* tWRRD
* tWRWRSC
* tWRWRSD
* tWRWRDD
* tWRWR_SCL
* tCKE
* ProcODT
* Command Rate(tCMD)
* Gear Down Mode
* AddrCmdSetup
* CsOdtSetup
* CkeSetup
* ClkDrvStren
* AddrCmdDrvStren
* CsOdtDrvStren
* CkeDrvStren
* RttNom
* RttWr
* RttPark

### SPD Info
* Power Down Enable</details>

___
* CPU Vcore
* Dynamic Vcore(DVID)
* VCORE SOC
* Dynamic VCORE SOC(DVID)
* CPU VDD18
* CPU VDDP
* DRAM Volrage (CH A/B)
* DDRVPP Voltage (CH A/B)
* DRAM Termination (CH A/B)
* VDDP Voltage Control
* VDDP Voltage
* VDDG Voltage Control
* VDDG Voltage

## CPU-VRM Settings
* CPU Vcore Loadline Calibration
* Vcore SOC Loadline Calibration
* CPU Vcore Protection
* CPU Vcore Current Protection
* PWM Phase Control

# Settings
![230316162544](https://user-images.githubusercontent.com/88921486/226192380-2ae3842f-b266-4b02-898a-149a2a8a5a18.JPG)

## Platform Power
* AC BACK
* ErP
* Sort-off by PWR-BTTN
* Power Loading
* Resume by Alarm
* Wake up day
* Wake up hour
* Wake up minute
* Wake up second
* Wake on LAN
* High Precision Event Timer

## IO Ports
* Initial Display Output
* HD Audio Controller
* PCIEX16 Bifurcation
* Above 4G Decoding
* Re-Size BAR Support
* Onboard Lan Controller

### USB Configuration
* Legacy USB Support
* XHCI Hand-off
* USB Mass Storage Driver Support
* Port 60/64 Emulation
* USB FLASH DRIVE PMAP

### NVMe Configuration
#### Samsung SSD 970 EVO Plus 250GB
* Self Test Option
* Self Test Action
* Run Device Self Test

### SATA Configuration
* SATA Mode
* NVMe RAID mode
* Chipset SATA Port Enable
* Chipset SATA Port Hot Plug

### Network Stack Configuration
* Network Stack

### Intel® I211 Gigabit Network Connection

<details><summary id="NIC Configuration"><h4>NIC Configuration</h4></summary>

* Link Speed
* Wake On LAN</details>

___
* Blink LEDs

## AMD CBS
### XFR Enhancement
* Precision Boost Overdrive
  * PPT Limit
  * TDC Limit
  * EDC Limit
* Precision Boost Overdrive Scalar
  * customized Precision Boost Overdrive Scalar
* FCLK Frequency
* SOC OVERCLOCK VID
* UCLK DIV 1 MODE
* VDDP Voltage Control
  * VDDP Voltage
* VDDG Voltage Control
  * VDDG Voltage
* SoC/Uncore OC Mode
* LN2  Mode

<details><summary id="Custom Core Pstates"><h3>Custom Core Pstates</h3></summary>

![230316134310](https://user-images.githubusercontent.com/88921486/226687600-f6dcfe61-c8c9-4e06-b882-7c799031736f.JPG)

* Custom Pstate0
  * Custom Pstate0 Freq (MHz)
  * Pstate0 VID </details>

___
* NUMA nodes per socket
* Memory interleaving
* ACS Enable
* PCIe ARI Support
* PCIe Ten Bit Tag Support

### CPU Common Options
#### Performance

<h5>Custom Core Pstates</h5>

[(Duplicated)](#Custom-Core-Pstates)

#### Prefetcher settings
* L1 Stream HW Prefetcher
* L2 Stream HW Prefetcher

#### Core Watchdog
* Core Watchdog Timer Enable
___
* Core Performance Boost
* Global C-state Control
* Power Supply Idle Control
* SEV ASID Count
* SEV-ES ASID Space Limit Control
  * SEV-ES ASID Space Limit
* Streaming Stores Control
* Local APIC Mode
* ACPI_CST C1 Declaration
* MCA error thresh enable
  * MCA error thresh count
* PPIN Opt-in

### DF Common Options

<details><summary id="Scrubber"><h4>Scrubber</h4></summary>

* DRAM scrub time
* Poison scrubber control
* Redirect scrubber control
* Redirect scrubber limit</details>

<details><summary id="Memory Adressing"><h4>Memory Adressing</h4></summary>

* NUMA nodes per socket
* Memory interleaving
* Memory interleaving size
* 1TB remap
* DRAM map inversion</details>

<details><summary id="ACPI"><h4>ACPI</h4></summary>

* ACPI SRAT L3 Cache As NUMA Domain
* ACPI SLIT Distance Control
* ACPI SLIT same socket distance
* ACPI SLIT remote socket distance
* ACPI SLIT local SLink distance
* ACPI SLIT remote SLink distance
* ACPI SLIT local inter-SLink distance
* ACPI SLIT remote inter-SLink distance
* ACPI SLIT remote relative distance</details>

<details><summary id="Link"><h4>Link</h4></summary>

* GMI encryption control
* xGMI encryption control
* CAKE CRC perf bounds Control
* 4-link xGMI max speed
* 3-link xGMI max speed
* xGMI TXEQ Mode
* PcsCG control</details>

___
* Disable DF to external downstram IP SyncFloodPropagation
* Disable DF sync flood propagation
* CC6 memory region encryption
* Memory Clear

### UMC Common Options
#### DDR4 Common Options
<h5>DRAM Timing Configuration</h5>

[(Duplicated)](#DRAM-Timing-Configuration)

##### DRAM Controller Configuration
<details><summary id="DRAM Power Options"><h6>DRAM Power Options</h6></summary>

* Power Down Enable
* Disable Burst/Postponed Refresh
* DRAM Maximum Activate Count</details>

___
* Cmd2T
* Gear Down Mode

#### CAD Bus Configuration
* CAD Bus Timing User Controls
* AddrCmdSetup
* CsOdtSetup
* CkeSetup
* CAD Bus Drive Strength User Controls
* ClkDrvStren
* AddrCmdDrvStren
* CsOdtDrvStren
* CkeDrvStren

<h4>Data Bus Configuration</h4>

[(Duplicated)](#Data-Bus-Configuration)

##### Common RAS
* Data Poisoning
* DRAM Post Package Repair
* RCD Parity
* DRAM Address Command Parity Retry
* Max Parity Error Replay
* Write CRC Enable
* DRAM Write CRC Enable and Retry Limit
* Max Write CRC Error Replay
* Disable Memory Error Injection

###### ECC Configuration
* DRAM ECC Symbol Size
* DRAM ECC Enable
* DRAM UECC Retry

##### Security
* TSME
* Data Scramble

##### Phy Configuration
###### PMU Training
* DFE Read Training
* FFE Write Training
* PMU Pattern Bits Control
* MR6VrefDQ Control
* CPU Vref Training Seed Control

#### DRAM Memory Mapping
* Chipselect Interleaving
* BankGroupSwap
* BankGroupSwapAlt
* Address Hash Bank 2 ColXor
* Address Hash Bank
* Address Hash CS
* Address Hash Rm
* SPD Read Optimization

#### Memory MBIST
##### Data Eye

#### NVDIMM

### NBIO Common Options
<h4>XFR Enhancement</h4>

[(Duplicated)](#XFR-Enhancement)

#### SMU Common Options
* Max Voltage Offset
* cTDP Control
  * cTDP

<details><summary id="Fan Control"><h5>Fan Control</h5></summary>
  
  * Fan Table Control
  * Low Temperature
  * Medium Temperature
  * High Temperature
  * Critical Temperature
  * Low Pwm 
  * Medium Pwm 
  * High Pwm 
  * Temperature Hysteresis
  * Pwm Frequency
  * Fan Polarity</details>

___
* EfficiencyModeEn
* Package Power Limit Control
  * Package Power Limit
* APBDIS
* DF Cstates
* CPPC
* CPPC Preferred Cores

##### NBIO LCLK DPM
* NBIO DPM Control
  * Socket 0 NBIO Target 0 DPM Level
  * Socket 0 NBIO Target 1 DPM Level
  * Socket 0 NBIO Target 2 DPM Level
  * Socket 0 NBIO Target 3 DPM Level
  * Socket 1 NBIO Target 0 DPM Level
  * Socket 1 NBIO Target 1 DPM Level
  * Socket 1 NBIO Target 2 DPM Level
  * Socket 1 NBIO Target 3 DPM Level

## AMD Overclocking
* Precision Boost Overdrive
* PBO Limits
* PPT Limit [W]
* TDC Limit [A]
* EDC Limit [A]
* Precision Boost Overdrive Scalar
* Precision Boost Overdrive Scalar
* Max CPU Boost Clock Overdrive
* Platform Thermal Throttle Limit
* Platform Thermal Throttle Limit
* SoC/Uncore OC Mode
* SoC Voltage
* VDDP Voltage Control
  * VDDP Voltage Control
* VDDG Voltage Control
  * VDDF CCD Voltage Control
  * VDDG IOD Voltage Control
* NUMA nodes per socket
* LN2 Mode
* ECO Mode

### Manual CPU Overclocking
* CPU Frequency
* CPU Voltage
* Core control
* SMT Control

### DDR and Infinity Fabric Frequency/Timings
#### DRAM Timing Configuration
* Overclock
* Memory Clock Speed
* Tcl Trcdrd
* Trcdrd
* Trcdwr
* Trp
* Tras
* Trc Ctrl
* Trc
* TrrdS
* TrrdL
* Tfaw Ctrl
* Tfaw
* TwtrS
* TwtrL
* Twr
* Trcpage Ctrl
* Trcpage
* TrereScL Ctrl
* TrereScL
* TwrwrScL Ctrl
* TwrwrScL
* Trfc Ctrl
* Trfc
* Trfc2 Ctrl
* Trfc4 Ctrl
* Tcwl
* Trtp
* Tcke
* Trdwr
* Twrrd
* TwrwrSc
* TwrwrDd
* TwrwrDd
* TrdrdSc
* TrdrdSd
* TrdrdDd
* ProcODT

#### DRAM Controller Configuration
* Cmd2T
* Gear Down Mode

<h4>CAD Bus Configuration</h4>

[(Duplicated)](#CAD-Bus-Configuration)

#### Data Bus Configuration
* Data Bus Configuration User Controls
* RttNom
* RttWe
* RttPark

___
* Power Down Enable
* Infinity Fabric Frequency and Dividers

## PC Health
![230316130030](https://user-images.githubusercontent.com/88921486/226683207-7adba852-0bf8-491f-9a0b-badf2925059d.JPG)

## Smart Fan 5

## Miscellaneous
* LEDs in System Power On State
* LEDs in Sleep, Hibernation, and Soft Off States
* PCIEX16 Slot Configuration
* PCIe Slot Configuration
* PCIe ASPM Mode
* 3DMark01 Enhancement
* IOMMU
* TSME
* AMD CPU fTPM

### Trusted Computing
* Security Device Support
* Disable Block Sid

# System Info

# Boot
* Boot Option #1
* Boot Option #2
* Bootup NumLock State
* Security Option
* Full Screen LOGO Show
* Fast Boot
* SATA Support
* NVMe Support
* VGA Support
* USB Support
* Network Stack Driver Support
* CSM Support
* LAN PXE Boot Option ROM
* Administrator Password
* User Password

## Secure Boot
* Secure Boot
* Secure Boot Mode
* Restore Factory Keys
* Reset To Setup Mode

<details><summary id="Key Managment"><h3>Key Managment</h3></summary>
  
* Factory Key Provision
* Restore Factory Keys
* Reset To Setup Mode
* Export Secure Boot variables
* Enroll Efi Image
* Remove 'UEFI CA' from DB
* Restore DB defaults</details>
___
* Preferrd Operating Mode
