# 👋 Roman | Системный / Embedded разработчик

**C/C++ Developer** с 5-летним опытом в embedded, системном программировании и настройке CI/CD для встраиваемых систем. Специализируюсь на создании низкоуровневого ПО, работе с микроконтроллерами (STM32, bare-metal), портировании драйверов в Linux и построении инфраструктуры для автоматизированной сборки и тестирования.

📍 **Локация:** Санкт-Петербург / Москва / Удалённо  
📧 **Email:** rimka.aromaug@gmail.com  
📞 **Телефон:** +7 992 202-60-24  

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
- **C/C++** (продвинутый) — основной язык для embedded и системного ПО.
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
## 📊 GitHub Statistics

### Development Metrics
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Rimk4&show=reviews,discussions_started,discussions_answered,prs_merged,prs_merged_percentage&hide_border=true&include_all_commits=true&count_private=true&theme=onedark&show_icons=true&bg_color=0D1117&hide=prs,issues&title_color=FF6B6B&text_color=C9D1D9&icon_color=4ECDC4)

### Coding Languages
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Rimk4&stats_format=bytes&theme=onedark&bg_color=0D1117&text_color=C9D1D9&title_color=FF6B6B)

### Weekly Activity
![Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=Rimk4&theme=react-dark&hide_border=true&area=true&color=FF6B6B&line=4ECDC4&point=FFFFFF&bg_color=0D1117&height=250)

### 📊 Detailed Analytics
<div style="display: flex; flex-wrap: wrap; gap: 8px; margin: 10px 0;">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Rimk4&theme=github_dark&height=120" style="flex: 1; min-width: 170px;" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Rimk4&theme=github_dark&height=120" style="flex: 1; min-width: 170px;" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Rimk4&theme=github_dark&utcOffset=3&height=120" style="flex: 1; min-width: 170px;" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Rimk4&theme=github_dark&utcOffset=3&height=120" style="flex: 1; min-width: 170px;" />
</div>
