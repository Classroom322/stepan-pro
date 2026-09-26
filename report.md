# Отчет по практической работе №2

* **Выполнил студент группы:** [3ИИС-1024]
* **ФИО:** [Жорин Степан Денисович]

---
### 🛠️ Этап 1. Характеристики виртуальной машины
* **Используемый гипервизор:** [Oracle VirtualBox] <!-- MARKER_HYPERVISOR -->
* **Выделенный объем ОЗУ (RAM):** [2048 MB] <!-- MARKER_RAM -->

---
### 📸 Этап 2. Скриншот установленной ОС
![Рабочий стол ОС](image.png) <!-- MARKER_IMAGE -->


---
### 💻 Этап 3. Системные логи диагностики оборудования
```text
[Architecture:             x86_64
  CPU op-mode(s):         32-bit, 64-bit
  Address sizes:          39 bits physical, 48 bits virtual
  Byte Order:             Little Endian
CPU(s):                   2
  On-line CPU(s) list:    0,1
Vendor ID:                GenuineIntel
  Model name:             Intel(R) Core(TM) i5-10400 CPU @ 2.90GHz
    CPU family:           6
    Model:                165
    Thread(s) per core:   1
    Core(s) per socket:   2
    Socket(s):            1
    Stepping:             3
    BogoMIPS:             5807.99
    Flags:                fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse3
                          6 clflush mmx fxsr sse sse2 ht syscall nx rdtscp lm constant_tsc rep_g
                          ood nopl xtopology nonstop_tsc cpuid tsc_known_freq pni pclmulqdq ssse
                          3 fma cx16 pcid sse4_1 sse4_2 x2apic movbe popcnt aes xsave avx f16c r
                          drand hypervisor lahf_lm abm 3dnowprefetch pti fsgsbase bmi1 avx2 bmi2
                           invpcid rdseed adx clflushopt arat md_clear flush_l1d arch_capabiliti
                          es
Virtualization features:  
  Hypervisor vendor:      KVM
  Virtualization type:    full
Caches (sum of all):      
  L1d:                    64 KiB (2 instances)
  L1i:                    64 KiB (2 instances)
  L2:                     512 KiB (2 instances)
  L3:                     24 MiB (2 instances)
NUMA:                     
  NUMA node(s):           1
  NUMA node0 CPU(s):      0,1
Vulnerabilities:          
  Gather data sampling:   Unknown: Dependent on hypervisor status
  Itlb multihit:          KVM: Mitigation: VMX unsupported
  L1tf:                   Mitigation; PTE Inversion
  Mds:                    Mitigation; Clear CPU buffers; SMT Host state unknown
  Meltdown:               Mitigation; PTI
  Mmio stale data:        Mitigation; Clear CPU buffers; SMT Host state unknown
  Reg file data sampling: Not affected
  Retbleed:               Vulnerable
  Spec rstack overflow:   Not affected
  Spec store bypass:      Vulnerable
  Spectre v1:             Mitigation; usercopy/swapgs barriers and __user pointer sanitization
  Spectre v2:             Mitigation; Retpolines; STIBP disabled; RSB filling; PBRSB-eIBRS Not a
                          ffected; BHI Retpoline
  Srbds:                  Unknown: Dependent on hypervisor status
  Tsx async abort:        Not affected
                                          ]
```
<!-- MARKER_LOG -->
