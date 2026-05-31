# Abdelrahman Aboelnour

I write bare-metal ARM Assembly and build distributed backends. The gap between them is where most of my thinking happens.

First-year CE student at Cairo University — the problems I keep gravitating toward are the ones that make you care about both layers.

---

## What I've been building

**[Elevator Control System](https://github.com/Abdelrahman-Aboelnour06)** `STM32 · ARM Assembly · GSM · RFID`

3-floor elevator on STM32F103 — no HAL, no abstraction layers, just registers and interrupts. Fire and emergency handlers hit sub-millisecond response. HX711 load cell for overweight detection, SIM800L GSM for automated SMS and voice call alerts, RFID + keypad for access control. Syncing Reed switches with door servos cut simulated cycle latency by 40%.

**[Collaborative Text Editor](https://github.com/Abdelrahman-Aboelnour06)** `Java · Spring Boot · WebSockets`

Real-time editor backend with a dual-level (Block/Character) CRDT. Logical clocks and tombstones handle conflict-free concurrent editing, version history, and undo/redo — no locking. 10 simultaneous users under 200ms.

**[OS Process Scheduler + MMU](https://github.com/Abdelrahman-Aboelnour06)** `C · Unix · IPC`

Each "simulated" process is an actual forked Unix child process — preempted with SIGSTOP, resumed with SIGCONT, terminated with SIGUSR2. Not a textbook abstraction. Three schedulers: HPF (with process dependency chains and equal-priority tie-breaking), SRTN, and Round Robin with configurable quanta. Custom MMU with Second-Chance and LRU page replacement, per-process page tables, and async disk I/O that blocks processes and unblocks them on completion. 97 of 100 test cases pass.

Also: a 4-bit ALU built in Verilog then physically wired with 74XX/40XX ICs. A BJT amplifier + rectifier circuit verified within 5% of theoretical values.

---

## Tools

```
Embedded    STM32 · ARM Assembly · UART · I2C · SPI · Interrupts
HDL         Verilog · ModelSim · Quartus · Questa
Languages   C/C++ · Java · Python · C# · Bash
Backend     Spring Boot · WebSockets · Flask · REST APIs
DB          MySQL · SQL Server · SQLite · MongoDB
Simulation  Multisim · MATLAB · Keil uVision5 · STM32CubeIDE
```

---

📍 Cairo, Egypt  
📬 abdelrahman.aboelnour.07@gmail.com · [LinkedIn](https://linkedin.com/in/abdelrahman-aboelnour-07-)
