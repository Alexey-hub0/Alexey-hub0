# Привет! Я Алексей

### Junior SOC Analyst | Blue Team

Начинающий аналитик информационной безопасности. Развиваюсь в направлении **Security Operations Center (SOC)**, уделяя основное внимание мониторингу событий безопасности, анализу оповещений и расследованию инцидентов.

Практикуюсь в собственной лаборатории на базе **Wazuh SIEM, Sysmon и Suricata IDS**. Исследую техники MITRE ATT&CK, анализирую события безопасности и изучаю методы обнаружения подозрительной активности.

Завершил программу **SOC Analyst Learning Path на LetsDefend**, получил сертификат. Продолжаю обучение и развиваю практические навыки Blue Team.

---

## 🛡️ Технические навыки

**SIEM & Detection**
- Wazuh SIEM — анализ событий, работа с Discover, настройка сбора журналов и правил обнаружения.
- Sysmon — анализ процессов, сетевых соединений и событий Windows.
- Suricata IDS — анализ сетевой активности и IDS-оповещений.
- Windows Event Logs — исследование событий безопасности, PowerShell и Task Scheduler.

**Incident Investigation**
- Alert Triage — первичная обработка и анализ оповещений.
- Process Tree Analysis — исследование цепочек запуска процессов.
- Timeline Analysis — восстановление последовательности событий.
- IOA / IOC Analysis — выявление признаков подозрительной активности.
- MITRE ATT&CK Mapping — сопоставление наблюдаемых действий с техниками атак.
- True Positive / False Positive Analysis — классификация событий.
- Severity Assessment — оценка критичности.
- Detection Gap / Telemetry Gap Analysis — выявление недостатков обнаружения и сбора данных.

**Инструменты и технологии**
- Windows 11, Ubuntu Linux, Kali Linux.
- Wazuh, Sysmon, Suricata.
- PowerShell, Bash.
- Nmap, Atomic Red Team.
- VirtualBox, Git, GitHub.
- TCP/IP, HTTP, DNS, SSH — основы сетевых протоколов и их анализ.

---

## 🔬 SOC Investigation Portfolio

**[Открыть портфолио SOC Analyst](https://github.com/Alexey-hub0/soc-investigation-portfolio)**

Портфолио состоит из двух направлений:

**Hands-on Labs** — практические эксперименты в собственной лаборатории с генерацией тестовой активности, анализом событий и проверкой механизмов обнаружения.

**Blind SOC Investigations** — расследования по синтетическим учебным данным без предварительного знания эталонного вердикта. Основной акцент — на аналитическом мышлении, проверке гипотез и принятии решений в условиях неполной телеметрии.

### Hands-on Labs

| Кейс | Сценарий | Основные навыки |
|---|---|---|
| [LAB-01 — PowerShell Execution](https://github.com/Alexey-hub0/soc-investigation-portfolio/tree/main/labs/case-01-powershell) | Подозрительное выполнение PowerShell | Process Tree, Event ID 4104, Wazuh Detection Rule |
| [LAB-02 — Scheduled Task Persistence](https://github.com/Alexey-hub0/soc-investigation-portfolio/tree/main/labs/case-02-scheduled-task) | Закрепление через планировщик задач Windows | Persistence Detection, Windows Events, Telemetry Gap |
| [LAB-03 — Network Reconnaissance](https://github.com/Alexey-hub0/soc-investigation-portfolio/tree/main/labs/case-03-network-reconnaissance) | Сканирование TCP-портов и обнаружение Nmap NSE | Nmap, Suricata IDS, Wazuh, Sysmon |

### Blind SOC Investigations

| Кейс | Сценарий | Основные навыки |
|---|---|---|
| [TRIAGE-01 — Mass File Modification](https://github.com/Alexey-hub0/soc-investigation-portfolio/tree/main/investigations/TRIAGE-01-mass-file-modification) | Массовое изменение файлов | False Positive Analysis, Process Investigation |
| [TRIAGE-02 — Password Spraying](https://github.com/Alexey-hub0/soc-investigation-portfolio/tree/main/investigations/TRIAGE-02-password-spraying) | Подозрительная активность аутентификации | Authentication Analysis, Incident Triage |
| [TRIAGE-03 — OAuth Consent Abuse](https://github.com/Alexey-hub0/soc-investigation-portfolio/tree/main/investigations/TRIAGE-03-oauth-consent) | Избыточные OAuth-разрешения приложения | Cloud Security, OAuth Permissions, Risk Assessment |

---

## 🖥️ Лабораторная среда

Для практики использую собственную виртуальную инфраструктуру на базе **Oracle VirtualBox**.

| Компонент | Назначение |
|---|---|
| Ubuntu Server + Wazuh | Централизованный сбор, анализ и хранение событий |
| Windows 11 + Sysmon | Генерация и исследование событий конечного устройства |
| Kali Linux | Контролируемая имитация подозрительной активности |
| Suricata IDS | Сетевое обнаружение и анализ IDS-оповещений |
| Atomic Red Team | Имитация техник MITRE ATT&CK |

В ходе лабораторных работ исследую события безопасности, проверяю встроенные правила обнаружения Wazuh и при необходимости разрабатываю собственные.

Результаты фиксирую в технических отчётах с исходными журналами, скриншотами и аналитическими выводами.

---

## 🎓 Обучение

**LetsDefend — SOC Analyst Learning Path**
- Программа завершена.
- Получен сертификат.
- Практика анализа оповещений и расследования инцидентов.

**Skillbox — «Специалист по кибербезопасности»**
- Обучение продолжается.
- Изучены основы Linux.

**Самостоятельная подготовка**
- Практика в собственной SOC-лаборатории.
- Изучение MITRE ATT&CK и методов обнаружения угроз.
- Разбор сценариев атак и подготовка к техническим собеседованиям SOC Analyst L1.

---

## 🎯 Профессиональные интересы

**Текущая цель:** Junior SOC Analyst / SOC Analyst L1.

Основные направления интереса:

- Security Monitoring & Alert Triage.
- Incident Detection & Investigation.
- Endpoint & Network Security Monitoring.
- Detection Engineering.
- Threat Hunting — направление дальнейшего профессионального развития.

**[Мои SOC-расследования и лабораторные кейсы →](https://github.com/Alexey-hub0/soc-investigation-portfolio)**
