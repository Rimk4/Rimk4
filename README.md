# 👋 Roman | Системный / Embedded разработчик

**C/C++ Developer** с 5-летним опытом в embedded, системном программировании и настройке CI/CD для встраиваемых систем. Специализируюсь на создании низкоуровневого ПО, работе с микроконтроллерами (STM32, bare-metal), портировании драйверов в Linux и построении инфраструктуры для автоматизированной сборки и тестирования.

📍 **Локация:** Москва / Санкт-Петербург / Удалённо  
📧 **Email:** rimka.aromaug@gmail.com  
📞 **Телефон:** +7 992 202-60-24  
🐙 **GitHub:** [github.com/Rimk4](https://github.com/Rimk4)

---

## 🛠️ Технологический стек

![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Bash](https://img.shields.io/badge/bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-%23008FBA.svg?style=for-the-badge&logo=cmake&logoColor=white)

### **Языки программирования**
- **C/C++** (5 лет, продвинутый) — основной язык для embedded и системного ПО.
- **Python** (средний) — скриптование, утилиты автоматизации, инструменты CI/CD.
- **Bash/Shell** — автоматизация, системные скрипты.
- **ARM Assembly** (базовый) — для понимания низкоуровневых оптимизаций.

### **Embedded разработка**
- **Микроконтроллеры:** ARM Cortex-M (STM32), программирование на уровне регистров (без HAL), тактирование, энергопотребление.
- **Периферия и драйверы:** SPI, I2C, UART, USB (CDC), ADC, DMA, работа с дисплеями и датчиками.
- **Отладка:** JTAG/SWD (ST-Link, J-Link), логические анализаторы, осциллографы.
- **Операционные системы:** RTOS, bare-metal разработка, Linux для embedded.

### **Системное программирование (Linux)**
- **Пространство ядра / модули:** портирование драйверов устройств.
- **Пользовательское пространство:** системные демоны, многопоточность (`pthreads`), межпроцессное взаимодействие (IPC): shared memory, сокеты, пайпы.
- **Сетевое программирование:** сокеты (TCP/UDP), высокопроизводительные серверы (epoll), `tcpdump/Wireshark`.
- **Инструменты отладки:** GDB, strace, ltrace, perf, valgrind.

### **Инструменты и инфраструктура**
- **Системы контроля версий:** Git, Git Flow.
- **Сборка:** Make, CMake, Autotools.
- **CI/CD:** GitLab CI/CD, Docker, создание и управление пайплайнами для embedded-проектов.
- **Сборка образов ОС:** Buildroot, Yocto (базовый опыт).
- **Документирование:** Doxygen.
- **Методологии:** Agile/Scrum, Code Review, TDD.

---

## 💼 Ключевые проекты и опыт

### **🔧 Разработка firmware для STM32 (bare-metal)**
*Полный цикл разработки ПО для промышленных контроллеров.*

- Разработка драйверов периферии (SPI для дисплея, I2C для датчиков, 12-битный ADC) на регистровом уровне с использованием DMA для максимальной производительности.
- Оптимизация тактирования и энергопотребления микроконтроллера.
- Аппаратная отладка с использованием осциллографа и логического анализатора для внесения корректировок в схемотехнику.

### **🖥️ Портирование драйвера USB CDC в embedded Linux**
*Разработка низкоуровневого ПО для встраиваемой платформы.*

- Портирование драйвера из mainline ядра Linux в кастомную embedded-систему.
- Обеспечение стабильной работы в реальном времени, отладка проблем синхронизации.
- Разработка системного демона для сбора метрик с использованием shared memory и netlink socket.

### **🚀 Построение CI/CD пайплайна для embedded-проектов**
*Автоматизация процессов сборки, тестирования и релиза.*

- Полная настройка пайплайна в GitLab CI: сборка в Docker-контейнерах, запуск юнит-тестов, статический анализ кода (Cppcheck), проверка стиля.
- Автоматизация выпуска релизов: сборка артефактов (прошивки, образы) по тегу и публикация на удалённый сервер.
- Создание системы управления Docker-образами (GitLab Container Registry).
- Разработка Python-скриптов для валидации changelog и генерации шаблонов для unit-тестов.

### **🌐 Легковесный TCP/IP стек и рефакторинг legacy-системы**
*Разработка сетевого шлюза для промышленной системы.*

- Реализация с нуля пользовательского TCP/IP стека, включая state machine для TCP-сервера.
- Создание поверх него lightweight HTTP-сервера для API устройства.
- Полный рефакторинг монолитной системы: выделение модульной архитектуры (диспетчер серверов, менеджер соединений), применение паттернов проектирования. Результат: повышение читаемости кода и упрощение онбординга новых разработчиков.

---

## 📚 Образование

**СПбПУ (Политех Петра Великого)**  
Факультет: Физико-Механический  
Направление: Прикладная математика и информатика  
Степень: Бакалавр  
Год окончания: 2025

---

## 🎯 Карьерные цели

Стремлюсь к позиции, где востребован глубокий опыт работы на стыке hardware и software. Интересны сложные задачи в области:

- Разработки и оптимизации низкоуровневого ПО (драйверы, firmware, протоколы).
- Создания высокопроизводительных и надежных систем под Linux.
- Построения и улучшения DevOps-практик для embedded-разработки.

Открыт к релокации в Москву, Санкт-Петербург или к удалённой работе.

---

## 📂 Структура репозиториев

*В этом профиле вы найдете проекты, отражающие мой опыт:*

- **`embedded-stm32-examples/`** — Примеры низкоуровневых драйверов для STM32 (SPI, I2C, ADC с DMA).
- **`linux-system-programming/`** — Примеры многопоточных приложений, IPC, системных демонов.
- **`ci-cd-templates/`** — Шаблоны и утилиты для настройки GitLab CI/CD пайплайнов для embedded.
- **`network-server-example/`** — Пример высокопроизводительного TCP-сервера на C с использованием epoll.

---

**✨ Готов к интересным вызовам и участию в сложных проектах!**

### 📈 GitHub Analytics

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Rimk4&theme=onedark&hide_border=true&bg_color=0D1117&show_icons=true&include_all_commits=true&count_private=true&custom_title=Rimk4%27s%20GitHub%20Stats)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Rimk4&theme=onedark&hide_border=true&bg_color=0D1117&layout=compact&langs_count=6&exclude_repo=repo1,repo2)

![GitHub Streak](https://streak-stats.demolab.com?user=Rimk4&theme=onedark&hide_border=true&background=0D1117&dates=FFFFFF&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF)

</div>

### 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=Rimk4&theme=dark&hide_border=true&include_all_commits=true&count_private=true)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Rimk4&theme=dark&hide_border=true&layout=compact&langs_count=8)

### 👨‍💻 Coding Activity

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=Rimk4&theme=radical&show_icons=true&hide_border=true&count_private=true)
![Streak](https://github-readme-streak-stats.herokuapp.com/?user=Rimk4&theme=radical&hide_border=true)
![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Rimk4&theme=radical&hide_border=true&layout=compact)

</div>

## 📊 GitHub Stats

<div align="center">

![Roman's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Rimk4&theme=dark&hide_border=true&show_icons=true&include_all_commits=true&count_private=false)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Rimk4&theme=dark&hide_border=true&layout=compact&langs_count=8&exclude_repo=)

![GitHub Streak](https://streak-stats.demolab.com/?user=Rimk4&theme=dark&hide_border=true)

</div>
