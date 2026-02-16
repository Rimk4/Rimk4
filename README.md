# 👋 Hi, I'm Roman | Systems / Embedded C/C++ Developer

[![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)](https://github.com/Rimk4)
[![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)](https://github.com/Rimk4)
[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://github.com/Rimk4)
[![Bash](https://img.shields.io/badge/bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://github.com/Rimk4)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://github.com/Rimk4)
[![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)](https://github.com/Rimk4)
[![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://github.com/Rimk4)
[![CMake](https://img.shields.io/badge/CMake-%23008FBA.svg?style=for-the-badge&logo=cmake&logoColor=white)](https://github.com/Rimk4)

**Middle C/C++ Developer** with ~5 years of experience in embedded systems, systems programming, and infrastructure automation. I specialize in low-level software development (STM32, bare-metal), Linux system programming (drivers, daemons, IPC), and building robust CI/CD pipelines for embedded projects.

📍 **Location:** St. Petersburg / Moscow / Remote  
📧 **Email:** [rimka.aromaug@gmail.com](mailto:rimka.aromaug@gmail.com)  
📞 **Phone:** +7 992 202-60-24  

---

## 🛠️ Tech Stack & Expertise

### **Core Languages**
- **C/C++** (Advanced, C++11/14/17/20/23) — Primary languages for embedded and systems software.
- **Python** (Intermediate) — Tooling, automation scripts, CI/CD integration.
- **Bash/Shell** — System scripting and automation.
- **ARM Assembly** (Basic) — For low-level understanding and optimizations.

### **Embedded Development**
- **Microcontrollers:** ARM Cortex-M (STM32), Register-level programming (no HAL), Clock management, Power optimization.
- **Peripherals & Drivers:** SPI, I2C, UART, USB (CDC), ADC, DMA, Display and sensor interfacing.
- **Debugging:** JTAG/SWD (ST-Link, J-Link), Logic analyzers, Oscilloscopes.
- **OS & Environments:** RTOS, Bare-metal, Embedded Linux.

### **Systems Programming (Linux)**
- **Kernel Space:** Device driver porting and module development.
- **User Space:** High-performance daemons, Multithreading (`pthreads`), IPC (Shared memory, sockets, pipes, netlink).
- **Network Programming:** TCP/UDP sockets, High-performance servers (epoll), Traffic analysis (`tcpdump`/Wireshark).
- **Debugging & Profiling:** GDB, `strace`/`ltrace`, `perf`, Valgrind.

### **Infrastructure & Tools**
- **Version Control:** Git, Git Flow.
- **Build Systems:** Make, CMake, Autotools.
- **CI/CD:** GitLab CI/CD, Docker, Pipeline design for embedded projects.
- **OS Build Systems:** Buildroot, Yocto (basic).
- **Documentation:** Doxygen.
- **Methodologies:** Agile/Scrum, Rigorous Code Review, TDD.

---

## 💼 Featured Projects & Experience

### **🔧 Bare-metal Firmware for STM32**
*Full-cycle firmware development for industrial controllers.*
- Developed peripheral drivers (SPI for displays, I2C for sensors, 12-bit ADC) at the register level, utilizing DMA for zero-copy data transfer.
- Optimized clock trees and power management for low-power operation.
- Performed hardware debugging with oscilloscopes and logic analyzers to validate and refine the circuit design.

### **🖥️ Porting a USB CDC Driver to Embedded Linux**
*Low-level systems programming for a custom embedded platform.*
- Ported a USB CDC driver from the mainline Linux kernel to a custom embedded system.
- Ensured real-time stability and debugged complex synchronization issues.
- Developed a system daemon for metric collection using shared memory and netlink sockets.

### **🚀 CI/CD Pipeline for Embedded Projects**
*Automating build, test, and release processes.*
- Architected and implemented GitLab CI pipelines from scratch: building firmware in Docker containers, running unit tests, integrating static analysis (Cppcheck), and enforcing code style.
- Automated release workflows: building artifacts (firmware, OS images) on git tags and publishing to a remote server.
- Created Python utilities for changelog validation in Merge Requests and auto-generating unit test templates.

### **🌐 High-Load Network Gateway & Legacy Code Modernization**
*Building a scalable network gateway for an industrial IoT platform.*
- **Architectural Redesign:** Analyzed a monolithic legacy system and architected a new modular system with clear microservice boundaries (Connection Dispatcher, TCP Server, Data Manager).
- **Network Microservices:** Engineered a high-performance, custom TCP server with a robust connection state machine and application-level protocols over TCP.
- **High-Load Optimization:** Optimized buffer management and connection handling to support tens of thousands of concurrent sessions using `epoll` for asynchronous I/O.
- **Refactoring:** Executed a comprehensive refactoring, extracting core logic into reusable libraries, significantly improving code readability and developer onboarding.

---

## 📚 Education

**Peter the Great St. Petersburg Polytechnic University (SPbPU)**  
Faculty of Physics and Mechanics  
*Applied Mathematics and Computer Science*  
**Degree:** Bachelor's (Expected 2025)

---

## 🎯 Career Interests

I thrive at the intersection of hardware and software. I'm seeking a role where I can apply my deep systems knowledge to complex challenges in:

- Low-level software development (drivers, firmware, protocols).
- High-performance and reliable Linux systems.
- Implementing and improving DevOps practices for embedded development.

Open to opportunities in St. Petersburg, Moscow, or remote work.

---

## 📂 Repository Highlights

- **`[embedded-stm32-examples](link)`** — Low-level driver examples for STM32 (SPI, I2C, ADC with DMA).
- **`[linux-system-programming](link)`** — Examples of multithreaded applications, IPC, and system daemons.
- **`[ci-cd-templates](link)`** — Templates and utilities for setting up GitLab CI/CD pipelines for embedded projects.
- **`[network-server-example](link)`** — A high-performance TCP server in C using `epoll`.

---

## 📊 GitHub Statistics

### Weekly Activity
![Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=Rimk4&theme=react-dark&hide_border=true&area=true&color=FF6B6B&line=4ECDC4&point=FFFFFF&bg_color=0D1117&height=250)

### 📊 Detailed Analytics
<div style="display: flex; flex-wrap: wrap; gap: 8px; margin: 10px 0;">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Rimk4&theme=github_dark&height=120" style="flex: 1; min-width: 170px;" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Rimk4&theme=github_dark&height=120" style="flex: 1; min-width: 170px;" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Rimk4&theme=github_dark&utcOffset=3&height=120" style="flex: 1; min-width: 170px;" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Rimk4&theme=github_dark&utcOffset=3&height=120" style="flex: 1; min-width: 170px;" />
</div>


**✨ I'm always open to interesting challenges and contributing to complex, impactful projects. Let's connect!**
