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
    - [Custom Core Pstates](#Custom-Core-Pstates)
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
    - [XFR Enhancement](#XFR-Enhancement)
  - [AMD Overclocking](#AMD-Overclocking)
    - [Manual CPU Overclocking](#Manual-CPU-Overclocking)
    - [DDR and Infinity Fabric Frequency/Timings](#DDR-and-Infinity-Fabric-Frequency/Timings)
      - [DRAM Timing Configuration](#DRAM-Timing-Configuration)
      - [DRAM Controller Configuration](#DRAM-Controller-Configuration)
      - [CAD Bus Configuration](#CAD-Bus-Configuration)
      - [Data Bus Configuration](#Data-Bus-Configuration)
  - [PC Health](#PC-Health)
  - [Smart Fan 5](#Smart-Fan-5)
- [System Info](#System-Info)
- [Boot](#Boot)
  - [Secure Boot](#Secure-Boot)
    - [Key Managment](#Key-Managment)

# Tweaker
* CPU Clock Control
* Spread Spectrum Control
* CPU Ratio Mode
* CPU Clock Ratio
* Precision Boost Overdrive
* Precision Boost Overdrive:
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
* VDDG Voltage Control
* SoC/Uncore OC Mode
* LN2  Mode

<details><summary id="Custom Core Pstates"><h3>Custom Core Pstates</h3></summary>

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
* PPIN Opt-in

### DF Common Options
#### Scrubber
* DRAM scrub time
* Poison scrubber control
* Redirect scrubber control
* Redirect scrubber limit

#### Memory Adressing
* NUMA nodes per socket
* Memory interleaving
* Memory interleaving size
* 1TB remap
* DRAM map inversion

#### ACPI
* ACPI SRAT L3 Cache As NUMA Domain
* ACPI SLIT Distance Control
* ACPI SLIT  same socket distance
* ACPI SLIT remote socket distance
* ACPI SLIT local SLink distance
* ACPI SLIT remote SLink distance
* ACPI SLIT local inter-SLink distance
* ACPI SLIT remote inter-SLink distance
* ACPI SLIT remote relative distance

#### Link
* GMI encryption control
* xGMI encryption control
* CAKE CRC perf bounds Control
* 4-link xGMI max speed
* 3-link xGMI max speed
* xGMI TXEQ Mode
* PcsCG control

___
* Disable DF to external downstram IP SyncFloodPropagation
* Disable DF sync flood propagation
* CC6 memory region encryption
* Memory Clear

### UMC Common Options
#### DDR4 Common Options
##### DRAM Timing Configuration

##### DRAM Controller Configuration
###### DRAM Power Options

##### CAD Bus Configuration

##### Data Bus Configuration

##### Common RAS
###### ECC Configuration

##### Security

##### Phy Configuration
###### PMU Training

#### DRAM Memory Mapping

#### Memory MBIST
##### Data Eye

#### NVDIMM

### NBIO Common Options

<h4>XFR Enhancement</h4>

[(Duplicated)](#XFR-Enhancement)

#### SMU Common Options
##### Fan Control

##### NBIO LCLK DPM

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

#### Data Bus Configuration
* Data Bus Configuration User Controls
* RttNom
* RttWe
* RttPark

___
* Power Down Enable
* Infinity Fabric Frequency and Dividers

## PC Health

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

### Key Managment

___
* Preferrd Operating Mode
