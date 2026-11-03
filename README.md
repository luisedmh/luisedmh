<h1 align="center">Hi, I'm Luis Eduardo Martín Hernández</h1>

<p align="center">
  <b>Computer Engineering student at Universidad de La Laguna (Spain)</b><br>
  High-Performance Computing · GPU programming · Parallel & heterogeneous systems
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/luis-eduardo-mart%C3%ADn-hern%C3%A1ndez-a76307417"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:luiseduardomartinhdez@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <img src="https://img.shields.io/badge/Based_in-Tenerife,_Spain-555?style=for-the-badge" alt="Tenerife, Spain">
</p>

---

## About me

- Final-year **BSc in Computer Engineering** at the **Universidad de La Laguna (ULL)**, Tenerife, Spain.
- **Erasmus+ exchange semester** at **Linnaeus University (LNU), Sweden** — spring 2026, all courses taught in English.
- My main interest is **High-Performance Computing**: making scientific simulations run faster on GPUs and on heterogeneous CPU+GPU systems.
- Currently working on my **Bachelor's thesis**: a Lattice Boltzmann fluid solver that **dynamically balances work between CPU and GPU at runtime**.
- Next step: pursuing a **Master's degree** in HPC / parallel computing.

---

## Featured work

### [Heterogeneous CPU+GPU Lattice Boltzmann solver](https://github.com/luisedmh/lbm-heterogeneous-autotuning) — *Bachelor's thesis*
A 2D (D2Q9) Lattice Boltzmann CFD solver written from scratch in **C++, OpenMP and CUDA**, developed step by step: sequential → multithreaded CPU → GPU → CPU+GPU → runtime rebalancing.

- GPU-only version benchmarked against **FluidX3D** under equal conditions (same problem size and precision): **~7,341 MLUPS, ~39% faster in FP32**.
- **Dynamic CPU+GPU load balancing** adjusted during the simulation using live timing measurements: **+24.7% to +31.3% over GPU-only in FP64**.
- **Self-calibrating:** the solver measures whether using the CPU pays off and turns it off when it doesn't (e.g. FP32), avoiding performance regressions.
- Every version validated cell-by-cell against a verified reference implementation.

### [Programming Massively Parallel Processors — exercises](https://github.com/luisedmh/Exercices_ProgrammingMassivelyParallelProcessors_AHandsOnApproach_SecondEdition)
My CUDA solutions to the exercises in *Programming Massively Parallel Processors* (Kirk & Hwu), profiled with **NVIDIA Nsight Systems**.

### [Computer Engineering coursework — ULL & Linnaeus University](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL)
All the labs, assignments and reports I kept from my degree (4 years, 20+ courses), organised by year and semester — including the courses I took during my Erasmus in Sweden.

### More projects

| Project | What it is | Stack |
|---|---|---|
| [Dynamic Maze Solver (A\*)](https://github.com/luisedmh/Busquedas_Informadas) | Pathfinding agent that re-plans with A\* in a maze whose obstacles change at every step | C++ |
| [LoRa → ESP32 → Raspberry Pi 5 IoT pipeline](https://github.com/luisedmh/Data-transfered-by-Lora32-to-esp32-into-WiFi-to-Socket-connection-with-RaspberryPi5) | End-to-end sensor data pipeline: LoRa radio, WiFi gateway and a custom C++ socket server | C++, PlatformIO, sockets |
| [DIY Force-Feedback Sim-Racing Wheel (8 Nm)](https://github.com/luisedmh/DIY-Simracing-FFB-Wheel-8-Nm) | Racing wheel built from scratch: motor driver, encoder, firmware and 3D-printed parts | Arduino, C++, 3D design |
| [Sanitarios DSL](https://github.com/luisedmh/Sanitarios_Ruby) | Ruby gem implementing an internal DSL, with tests and CI | Ruby, Minitest, GitHub Actions |

---

## Skills — and where to see them

Every skill below links to code or reports where I actually used it.

| Area | Skills | Evidence |
|---|---|---|
| **HPC & GPU** | CUDA, OpenMP, CPU+GPU load balancing, performance benchmarking (MLUPS), Nsight profiling | [LBM solver](https://github.com/luisedmh/lbm-heterogeneous-autotuning) · [PMPP exercises](https://github.com/luisedmh/Exercices_ProgrammingMassivelyParallelProcessors_AHandsOnApproach_SecondEdition) |
| **Algorithms & data structures** | Arbitrary-precision arithmetic, hash tables, sorting algorithms, BST/AVL trees, automata, grammars (CNF), convex hull, minimum spanning trees | [AyEDA](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL/tree/master/2%C2%BAInform%C3%A1tica/SegundoCuatri/AyEDA) · [CyA](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL/tree/master/2%C2%BAInform%C3%A1tica/PrimerCuatri/CyA) |
| **Artificial Intelligence** | BFS/DFS, A\* search, K-Means clustering, Prolog, collaborative filtering | [IA](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL/tree/master/3%C2%BAInform%C3%A1tica/PrimerCuatri/IA) · [Maze solver](https://github.com/luisedmh/Busquedas_Informadas) · [GCO](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL/tree/master/4%C2%BAInform%C3%A1tica/PrimerCuatri/GCO) |
| **Operating systems & Linux** | POSIX API, sockets, `mmap`, Bash scripting, system administration, virtualization | [SSOO](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL/tree/master/2%C2%BAInform%C3%A1tica/PrimerCuatri/SSOO) · [Systems Admin (LNU)](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL/tree/master/3%C2%BAInform%C3%A1tica/SegundoCuatri/Admin) |
| **Networks & security** | Protocol analysis (Wireshark), socket programming, PGP/GPG, OpenSSL, TLS/HTTPS | [RSD](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL/tree/master/2%C2%BAInform%C3%A1tica/SegundoCuatri/RSD) · [Internet Security (LNU)](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL/tree/master/3%C2%BAInform%C3%A1tica/SegundoCuatri/InternetSecurity) |
| **Computer architecture** | MIPS assembly, digital design in Verilog (ALU, adders, multiplexers) | [PC](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL/tree/master/1%C2%BAInform%C3%A1tica/SegundoCuatri/PC) · [EC](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL/tree/master/2%C2%BAInform%C3%A1tica/PrimerCuatri/EC) |
| **Embedded & IoT** | Arduino, ESP32, LoRa, Raspberry Pi, motor control | [IoT pipeline](https://github.com/luisedmh/Data-transfered-by-Lora32-to-esp32-into-WiFi-to-Socket-connection-with-RaspberryPi5) · [FFB wheel](https://github.com/luisedmh/DIY-Simracing-FFB-Wheel-8-Nm) |
| **Robotics** | Forward kinematics, Denavit-Hartenberg parameters | [Robótica](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL/tree/master/4%C2%BAInform%C3%A1tica/PrimerCuatri/Rob%C3%B3tica) |
| **Databases** | SQL queries, transactions, data definition | [Databases](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL/tree/master/3%C2%BAInform%C3%A1tica/PrimerCuatri/BASE%20DE%20DATOS) |
| **Software engineering** | Software architecture, project management, TDD, CI | [Software Architectures (LNU)](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL/tree/master/3%C2%BAInform%C3%A1tica/SegundoCuatri/SoftwareArchitectures) · [GPI](https://github.com/luisedmh/GradoEnIngenieriaInformatica_ULL/tree/master/3%C2%BAInform%C3%A1tica/PrimerCuatri/GPI) · [Sanitarios DSL](https://github.com/luisedmh/Sanitarios_Ruby) |

### Languages & tools

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![OpenMP](https://img.shields.io/badge/OpenMP-444?style=flat-square)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Prolog](https://img.shields.io/badge/Prolog-E61B23?style=flat-square)
![Verilog](https://img.shields.io/badge/Verilog-555?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

## Languages

- **Spanish** — native
- **English** — C1, Cambridge C1 Advanced (CAE), plus a full Erasmus semester taught in English

---

<p align="center"><i>Feel free to reach out on <a href="https://www.linkedin.com/in/luis-eduardo-mart%C3%ADn-hern%C3%A1ndez-a76307417">LinkedIn</a> or by email at <a href="mailto:luiseduardomartinhdez@gmail.com">luiseduardomartinhdez@gmail.com</a>.</i></p>
