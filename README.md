<!-- ============================================================
     SHRUTIK KAPATEL — GitHub Profile README
     Terminal / embedded firmware aesthetic
     ============================================================ -->

<div align="center">

<!-- Animated SVG terminal banner -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00FFFF&center=true&vCenter=true&width=600&lines=Shrutik+KaPatel;MEng+Electrical+Engineering;Embedded+Firmware+%7C+Bare-Metal+STM32;C+%7C+ARM+Cortex-M4+%7C+RTOS" alt="Typing SVG" />

```
┌─────────────────────────────────────────────────────────┐
│  $ whoami                                               │
│  > MEng EE Graduate · Carleton University, Ottawa       │
│  > Embedded Firmware Engineer                           │
│  > Bare-metal STM32F407 · ARM Cortex-M4 · C            │
│  $ status: actively seeking embedded / firmware roles   │
└─────────────────────────────────────────────────────────┘
```

[![Portfolio](https://img.shields.io/badge/Portfolio-shrutik--kapatel.github.io-00FFFF?style=for-the-badge&logo=github&logoColor=black)](https://shrutik-kapatel.github.io)
[![Email](https://img.shields.io/badge/Email-ka.patelshrutik37%40gmail.com-00FFFF?style=for-the-badge&logo=gmail&logoColor=black)](mailto:ka.patelshrutik37@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shrutik-kapatel)

</div>

---

## `$ cat about_me.txt`

```c
typedef struct {
    char  *name;
    char  *degree;
    char  *focus;
    char  *platform;
    char  *status;
} Engineer_t;

Engineer_t shrutik = {
    .name     = "Shrutik KaPatel",
    .degree   = "MEng Electrical Engineering — Carleton University",
    .focus    = "Bare-metal firmware, digital hardware design",
    .platform = "STM32F407 (ARM Cortex-M4)",
    .status   = "Open to embedded firmware & hardware roles"
};
```

I write firmware close to the metal — register-level peripheral drivers, interrupt-driven architectures, and DMA pipelines. My work lives in C, on real hardware, without an OS getting in the way.

---

## `$ ls ./skills/`

<div align="center">

### ⚙️ Core Platform
![STM32](https://img.shields.io/badge/STM32F407-ARM%20Cortex--M4-00FFFF?style=flat-square&logo=stmicroelectronics&logoColor=white)
![C](https://img.shields.io/badge/C-Bare--Metal-00FFFF?style=flat-square&logo=c&logoColor=white)
![ARM](https://img.shields.io/badge/ARM-Assembly-555?style=flat-square&logo=arm&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-Learning-yellow?style=flat-square)

### 🔌 Protocols & Peripherals
![UART](https://img.shields.io/badge/UART%2FDMA-Protocol-00FFFF?style=flat-square)
![SPI](https://img.shields.io/badge/SPI-Protocol-00FFFF?style=flat-square)
![I2C](https://img.shields.io/badge/I2C-Protocol-00FFFF?style=flat-square)
![PWM](https://img.shields.io/badge/PWM-Timer-00FFFF?style=flat-square)
![ADC](https://img.shields.io/badge/ADC%2FDAC-Analog-00FFFF?style=flat-square)
![RS232](https://img.shields.io/badge/RS--232-Serial-555?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT-Messaging-555?style=flat-square)

### 🖥️ Digital Hardware
![Verilog](https://img.shields.io/badge/Verilog-HDL-9B59B6?style=flat-square)
![FPGA](https://img.shields.io/badge/FPGA-Digital%20Design-9B59B6?style=flat-square)
![MIPS32](https://img.shields.io/badge/MIPS32-Pipelined%20CPU-9B59B6?style=flat-square)

### 🛠️ Debug & Toolchain
![JLink](https://img.shields.io/badge/J--Link-JTAG%20Debug-333?style=flat-square)
![Logic](https://img.shields.io/badge/Logic%20Analyzer-Waveform%20Debug-333?style=flat-square)
![GCC](https://img.shields.io/badge/GCC%20ARM-Toolchain-333?style=flat-square&logo=gnu&logoColor=white)
![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## `$ ls ./projects/ --sort=impact`

### 🔴 [`STM32F407 Bare-Metal Firmware Suite`](https://shrutik-kapatel.github.io)
```
Platform  : STM32F407VGT6 · ARM Cortex-M4 @ 168 MHz
Lang      : C (bare-metal, no HAL)
Key work  : Register-level GPIO, UART/DMA, SPI, I2C, timer PWM
Debug     : J-Link + logic analyzer validation
Status    : [████████████████████] Active development
```
> Full peripheral driver stack written from scratch against the reference manual. No abstraction layers — pure CMSIS and direct register writes.

---

### 🟡 [`drone-search-rescue-mips32`](https://github.com/Shrutik-KaPatel/drone-search-rescue-mips32)
```
Platform  : MIPS32 (Verilog)
Lang      : Verilog HDL
Key work  : 5-stage pipelined processor, edge preprocessing for drone SAR
Status    : [████████████████████] Complete
```
> Implemented a fully pipelined MIPS32 processor in Verilog to run drone search-and-rescue edge workloads. Hazard detection, forwarding units, and pipeline stall logic included.

---

### 🟢 [`sensor-data-logger`](https://github.com/Shrutik-KaPatel/sensor-data-logger)
```
Platform  : Bare-metal C (STM32 learning series)
Lang      : C
Key work  : Structs, unions, enums for temp/voltage/pressure modeling
Status    : [████████████████████] Complete
```

### 🟢 [`UART-Command-Handler`](https://github.com/Shrutik-KaPatel/UART-Command-Handler)
```
Platform  : Bare-metal C
Lang      : C
Key work  : Linked-list command queue, volatile ISR flags, multi-file extern
Status    : [████████████████████] Complete
```

### 🟢 [`Sensor_data`](https://github.com/Shrutik-KaPatel/Sensor_data)
```
Platform  : Bare-metal C
Lang      : C
Key work  : Dynamic sensor buffer with linked lists, embedded memory patterns
Status    : [████████████████████] Complete
```

---

## `$ cat learning_log.txt`

```
[IN PROGRESS] FreeRTOS task scheduling & semaphores
[IN PROGRESS] Bare-metal DMA pipelines (STM32F4)
[IN PROGRESS] Hardware debugging — J-Link, logic analyzer
[IN PROGRESS] Interrupt-driven driver architecture
[NEXT]        Bootloader implementation (STM32)
[NEXT]        CAN bus protocol
```

---

## `$ ./stats.sh`

<div align="center">

![Shrutik's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Shrutik-KaPatel&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=00FFFF&icon_color=00FFFF&text_color=FFFFFF&ring_color=00FFFF)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Shrutik-KaPatel&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=00FFFF&text_color=FFFFFF&langs_count=6)

![GitHub Streak](https://streak-stats.demolab.com?user=Shrutik-KaPatel&theme=radical&hide_border=true&background=0D1117&ring=00FFFF&fire=00FFFF&currStreakLabel=00FFFF)

</div>

---

## `$ ping shrutik`

<div align="center">

```
PING shrutik (ka.patelshrutik37@gmail.com)
→ Reply from shrutik: Open to embedded firmware roles
→ Reply from shrutik: Ottawa, ON · Relocation open
→ Reply from shrutik: Response time < 24h
```

[![Portfolio](https://img.shields.io/badge/Visit%20Portfolio-%E2%86%92-00FFFF?style=for-the-badge)](https://shrutik-kapatel.github.io)
[![Email](https://img.shields.io/badge/Send%20Email-%E2%86%92-00FFFF?style=for-the-badge)](mailto:ka.patelshrutik37@gmail.com)

<br/>

![Visitor Count](https://komarev.com/ghpvc/?username=Shrutik-KaPatel&color=00FFFF&style=flat-square&label=PROFILE+VIEWS)

</div>

---

<div align="center">
<sub><code>// Last updated: 2026 · Built for embedded systems engineers who read the datasheet first</code></sub>
</div>
