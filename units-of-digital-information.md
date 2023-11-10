# Units of Digital Information
## Background
### Base Unit
The base unit of digital information is byte, abbreviated as B. Each byte always consists of 8 bits, each denoting a binary state.
### Decimal Units
The universally accepted units of digital information make use of the SI-compliant multiplier of 1000. This means that 1 KB = 1000 B, 1 MB = 1000 KB, 1 GB = 1000 MB, 1 TB = 1000 GB, etc.
### Binary Units
The technically preferrable units of digital information make use of the binary-compliant multiplier of 1024 (2^10). This means that 1 KiB = 1024 B, 1 MiB = 1024 KiB, 1 GiB = 1024 MB, 1 TiB = 1024 GiB, etc.
### Hexidecimal Ratio
For certain use cases, quantities are discounted by a factor of 1/16, creating the hexidecimal ratios of 3.75:4, 7.5/8, 15:16, 30:32, 60:64, 120:128, 240:256, 480:512, 960:1024, etc.
## Definitions
### Base Unit
The base unit of digital information is byte*, abbreviated as B*. Each byte* always consists of 8 bits, each denoting a binary state.
## Applications
### Storage Capacity of Devices
A storage device with 256 GB* of capacity may use the hexidecimal ratio and have an actual capacity of 240 GB, following the formula: 256*(1-1/16) GB* -> 240 GB = 240*1000^3 B = 240000000000 B.
### Capacity Allocation
A virtual machine with 8 GB* of memory may be actually configured with 7.5 GiB of memory, following the hexidecimal ratio, to allow for bursts and better optimization for horizontal scalability, similarly 15 GiB instead of 16 GiB, 3.75 GiB instead of 4 GiB, etc.