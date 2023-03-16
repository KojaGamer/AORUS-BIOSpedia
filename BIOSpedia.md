# BIOS
- [Boot](#table-of-contents)
  - [Settings](#Settings)
    - [AMD CBS](#memory-testing-software)
      - [CPU Common Options](#CPU-Common-Options)
      - [Custom Core Pstates](#Custom-Core-Pstates)
      - [DF Common Options](#alternatives)
      - [NBIO Common Options](#comparison)
      - [UMC Common Options]
      - [XFR Enhancement]
    - [AMD Overclocking](#timings-software)
      -  DDR and Infinity Fabric Frequency/Timings
      -  Manual CPU Overclocking
    - [IO Ports](#benchmarks)
      - Intel® I211 Gigabit Network Connection
      - Network Stack Configuration
      - NVMe Configuration
      - SATA Configuration
      - USB Configuration
    - [Miscellaneous]
      - Trusted Computing
    - [PC Health]
    - [Platform Power]
    - [Smart Fan 5](#general-ram-info)
  - [Smart Fan 5](#general-ram-info)
  - [Frequency and Timings Relation](#frequency-and-timings-relation)
  - [Primary, Secondary and Tertiary Timings](#primary-secondary-and-tertiary-timings)
- [System Info](#expectationslimitations)
  - [Motherboard](#motherboard)
  - [Integrated Circuits (ICs)](#integrated-circuits-ics)
    - [Shorthand Notation](#shorthand-notation)
    - [Thaiphoon Report](#thaiphoon-report)
    - [Label on Sticks](#label-on-sticks)
      - [Corsair Version Number](#corsair-version-number)
      - [G.Skill 042 Code](#gskill-042-code)
      - [Kingston Code](#kingston-code)
    - [A Note on Logical Ranks and Density](#a-note-on-logical-ranks-and-density)
    - [Voltage Scaling](#voltage-scaling)
    - [Expected Max Frequency](#expected-max-frequency)
    - [Binning](#binning)
    - [Maximum Recommended Daily Voltage](#maximum-recommended-daily-voltage)
    - [Ranking](#ranking)
    - [Temperatures and Its Effect on Stability](#temperatures-and-its-effect-on-stability)
  - [Integrated Memory Controller (IMC)](#integrated-memory-controller-imc)
    - [Intel IMC](#intel-imc)
    - [AMD IMC](#amd-imc)
- [Tweaker](#overclocking)
  - [Finding a Baseline](#finding-a-baseline)
  - [Trying Higher Frequencies](#trying-higher-frequencies)
  - [Tightening Timings](#tightening-timings)
  - [Miscellaneous Tips](#miscellaneous-tips)
    - [Intel](#intel)
    - [AMD](#amd)
- [Useful Links](#useful-links)
  - [Benchmarks](#benchmarks-1)
  - [Information](#information)

# Setup
## Settings
### CPU Common Options
*Core Performance Boost
(Disable CPB)

*Global C-state Control
Controls IO based C-state generation and DF C-states.

*Power Supply Idle Control
The "Power Supply Idle Control" option in BIOS refers to a feature that helps to manage the power consumption of your computer when it's in an idle state. This option is usually found in the CPU Common Options section of the BIOS settings.
The three options available - Low Current Idle, Typical Current Idle, and Auto - refer to different levels of power consumption during idle periods.
⦁	Low Current Idle: This option typically sets the CPU to a very low power state, resulting in the lowest power consumption. However, this option may cause some delay when you try to resume the computer from an idle state.
⦁	Typical Current Idle: This option allows the CPU to maintain a certain level of activity even when the computer is idle, resulting in slightly higher power consumption than the Low Current Idle option. This setting usually results in faster wake-up times compared to the Low Current Idle option.
⦁	Auto: This option automatically adjusts the CPU's power consumption based on the system's workload, allowing the computer to balance power efficiency and performance.
The choice of which option to use will depend on your specific needs and preferences. If you are looking to conserve as much power as possible, you may want to use the Low Current Idle option. On the other hand, if you need a more responsive system, the Typical Current Idle or Auto option may be more suitable.

*SEV ASID Count
This field specifies the maximum valid ASID, which affects the maximum system physical address space, 16TB of physical address space is available for systems that support 253 ASIDs, while 8TB of physical address space is available for systems that support 509 ASIDs.

The "SEV ASID Count" option in BIOS refers to the maximum number of Address Space Identifier (ASID) values that the system can support when using AMD Secure Encrypted Virtualization (SEV) technology.
ASIDs are used to distinguish between different virtual machines running on a system. By limiting the number of ASIDs that can be used, the amount of physical address space that can be addressed by the system is also limited.
With SEV enabled, the maximum physical address space available to the system depends on the number of ASIDs supported. As the description in the BIOS suggests, a system supporting 253 ASIDs can address up to 16TB of physical memory, while a system supporting 509 ASIDs can address up to 8TB of physical memory.
SEV technology provides hardware-based memory encryption to help protect virtual machines from various attacks, including those targeting the hypervisor or host system. By using SEV, virtual machines can be securely isolated from each other and from the host system.

*SEV-ES ASID Space Limit Control
	SEV-ES ASID Space Limit
	SEV VMs using ASIDs below the SEV-ES ASID Space Limit must enable SEV-ES feature.	ASIDs from SEV-ES ASID Space Limit to (SEV ASID Count + 1) can only be used with SEV	VMs. If this field is set to (SEV ASID Count + 1), all ASIDs are forced to be SEV-ES ASIDs.	Hence, the valid values for this field is 1 - (SEV ASID

*Streaming Stores Control
Enables or disables the streaming stores functionality

The "Streaming Stores Control" option in the BIOS refers to a feature found in some modern processors that allows programs to store data in a more efficient manner. Streaming stores are a type of memory operation that can be used by some applications to write data directly to the cache memory, bypassing the slower system memory.
Enabling this option in the BIOS will allow the processor to use streaming stores when supported by the software running on the system. Disabling it will prevent the processor from using this feature, which may be necessary in some rare cases to ensure compatibility with certain software or hardware configurations.
Whether to enable or disable this option depends on your specific use case and the software you are running on your system. In general, if you are running modern software that supports streaming stores, enabling this option can provide a performance boost. However, if you are experiencing compatibility issues or other problems, disabling the option may be necessary.

*Local APIC Mode

*ACPI_CST C1 Declaration
Determines whether or not to declare the C1 state to the OS.

*MCA error thresh enable
Enable MCA error thresholding.

"Enable MCA error thresh enable" in BIOS refers to a setting that enables or disables Machine Check Architecture (MCA) error threshold reporting. MCA is a hardware error reporting mechanism used in modern CPUs, which allows the processor to detect and report hardware errors that occur during operation.
Enabling the MCA error threshold reporting feature will allow the system to monitor and report hardware errors that exceed a certain threshold. This can be useful in detecting and diagnosing hardware problems before they cause system crashes or data corruption.
Typically, this setting is found in the Advanced BIOS options menu and is disabled by default. It should only be enabled if you are experiencing hardware errors and need to diagnose the cause of the problem. However, it's important to note that enabling this feature can result in more frequent system restarts due to error reporting, so it should only be used when necessary.

*PPIN Opt-in
Turn on PPIN feature

*PPIN (Platform Processor Identifier Number) is a security feature provided by AMD processors that is used to authenticate the processor to the system. The PPIN Opt-in setting in the BIOS allows you to enable or disable this feature.
When the PPIN Opt-in feature is turned on, the processor generates a unique identifier that is tied to the system. This identifier can be used by security software to ensure that the processor is authentic and that the system has not been tampered with.
Enabling the PPIN feature can improve the security of your system, but it may also result in reduced system performance. Therefore, you should carefully consider whether you need this feature enabled or not, depending on your specific security needs.
It's worth noting that the PPIN feature is not commonly used by most users and it's mostly utilized in enterprise settings where system security is a critical concern.

*Indirect Branch Prediction Speculation
The "Indirect Branch Prediction Speculation" option in BIOS is a setting that controls the behavior of the CPU's branch predictor when executing code that includes indirect branch instructions.
Indirect branch instructions are used in computer programs to transfer control to another part of the program based on a value that is computed at runtime. The behavior of these instructions can be difficult to predict, which can lead to performance issues if the CPU's branch predictor guesses incorrectly.
The "Indirect Branch Prediction Speculation" option in the BIOS determines how the CPU's branch predictor handles these instructions. When enabled, the CPU will use speculative execution to try to predict the target of an indirect branch instruction, which can improve performance in some cases. When disabled, the CPU will use a more conservative approach that may be less vulnerable to certain types of attacks, but may also result in reduced performance.
It's worth noting that this setting can have implications for security, as speculative execution has been exploited in the past to execute unauthorized code. However, modern CPUs have implemented a variety of security features to mitigate these risks.

#Anything written in parenthesis is the stock explanation of BIOS.

### Custom Core Pstates

### Comparison
    
## Timings Software
    
## Benchmarks

# General RAM Info

## Frequency and Timings Relation

## Primary, Secondary and Tertiary Timings

# Expectations/Limitations

## Motherboard
  
## Integrated Circuits (ICs)

### Shorthand Notation

### Thaiphoon Report

### Label on Sticks

#### Corsair Version Number

#### G.Skill 042 Code

#### Kingston Code

### A Note on Logical Ranks and Density

### Voltage Scaling
  
### Expected Max Frequency
  
### Binning
  
### Maximum Recommended Daily Voltage

### Ranking

### Temperatures and Its Effect on Stability
 
## Integrated Memory Controller (IMC)

### Intel IMC
  
### AMD IMC
  
# Overclocking

## Finding a Baseline
   
## Trying Higher Frequencies
   
## Tightening Timings
    
## Miscellaneous Tips

### Intel

### AMD

# Useful Links

## Benchmarks

## Information
