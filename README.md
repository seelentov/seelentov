<h1 align="center">Привет, я Владислав 👋</h1>

<p align="center">
  <b>Backend-разработчик (Java / Kotlin / Go)</b> · промышленный IIoT · развиваюсь в AppSec
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vladislav-komkov-a78955434/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:komkov222111@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

## Обо мне

- 💼 **Tibbo Systems** — Middle Java-разработчик платформы [AggreGate](https://aggregate.digital/): IIoT-платформы для мониторинга,
  управления и интеграции промышленного оборудования. Многомодульный Gradle-проект на Java и Kotlin: плагинная архитектура
  (контексты, persistence-модули, драйверы устройств, сервисы авторизации), REST API, Cassandra / SQL, расследование
  инцидентов в production, code review.
- 🛠 До этого 1,5 года фриланса: полный цикл web- и mobile-разработки для малого бизнеса — от требований до запуска и поддержки.
- 🔐 Сейчас углубляюсь в **Application Security**: SAST (Semgrep, CodeQL), поиск секретов и SCA (Gitleaks, Trivy),
  threat modeling, ревью веб-приложений и API по OWASP Top 10, валидация находок и патчей.
- 🤖 Активно использую AI-агентов и LLM в разработке: исследование кодовой базы, разбор причин ошибок, генерация тестов, рефакторинг.

## Проекты

| Проект | Описание | Стек |
|---|---|---|
| 🛡 [**aiegis**](https://github.com/seelentov/aiegis) | Десктопное приложение для AppSec-аудита поверх Claude Code или pi (модели любого провайдера): матрица «требования × модули» с вердиктами и доказательствами, карта точек входа, триаж сигналов Semgrep/Gitleaks/Trivy, SCA с проверкой достижимости, PoC-проверка находок с автонастройкой тестового окружения. Агенты работают через MCP со scope-токенами в изолированных git worktree | Electron · TypeScript · React · MCP · SQLite · xterm.js |
| 📡 [**discovery**](https://github.com/seelentov/discovery) | Open-source система мониторинга сетевых устройств для интернет-провайдеров: SNMP-дискаверинг и опрос, тревоги с гистерезисом, топология, уведомления в Telegram/email/webhook. Один бинарник со встроенным дашбордом | Rust · Tokio · Axum · SeaORM · React · TypeScript · Playwright |
| 💬 [**miichat**](https://github.com/seelentov/miichat) | Self-hosted мессенджер: шифрование на сервере AES-256-GCM, E2E для secret-чатов (ECDH P-256), регистрация без email/телефона | Go · JavaScript · Docker |
| ⚙️ [**workflow**](https://github.com/seelentov/workflow) | Автоматизация задач на удалённых серверах по SSH: YAML-плейбуки и инвентори, аналог Ansible | Go · Cobra · YAML |
| 📰 [**gopress**](https://github.com/seelentov/gopress) | Headless CMS с визуальным конструктором запросов, типами контента, ролями и публичным REST API | Go · Gin · GORM · PostgreSQL / MySQL / SQLite |
| 🧮 [**gowcode**](https://github.com/seelentov/gowcode) | Вычислитель выражений для Go: переменные, тернарный оператор, списки и словари, встроенные и пользовательские функции | Go |

## Стек

**Языки**

![Java](https://img.shields.io/badge/Java_8%20%7C%2017%20%7C%2021-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Java enterprise**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring_MVC-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Jackson](https://img.shields.io/badge/Jackson-2C5BB4?style=for-the-badge)
![Tomcat](https://img.shields.io/badge/Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black)
![Netty](https://img.shields.io/badge/Netty-0F4C81?style=for-the-badge)
![Log4j](https://img.shields.io/badge/Log4j%20%2F%20SLF4J-D22128?style=for-the-badge&logo=apache&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

**Тестирование**

![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641?style=for-the-badge)
![AssertJ](https://img.shields.io/badge/AssertJ-1F6FEB?style=for-the-badge)
![Testcontainers](https://img.shields.io/badge/Testcontainers-291A3F?style=for-the-badge&logo=testcontainers&logoColor=white)
![WireMock](https://img.shields.io/badge/WireMock-1A1A1A?style=for-the-badge)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

**Хранилища и брокеры**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=for-the-badge&logo=apachecassandra&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)

**Go / Rust / Frontend**

![Gin](https://img.shields.io/badge/Gin-008ECF?style=for-the-badge&logo=gin&logoColor=white)
![GORM](https://img.shields.io/badge/GORM-00ADD8?style=for-the-badge)
![Tokio](https://img.shields.io/badge/Tokio-000000?style=for-the-badge)
![Axum](https://img.shields.io/badge/Axum-000000?style=for-the-badge)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

**DevOps и инфраструктура**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)

**Протоколы и интеграции**

![REST](https://img.shields.io/badge/REST_API-005571?style=for-the-badge)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge)
![SNMP](https://img.shields.io/badge/SNMP-4B5563?style=for-the-badge)
![OPC UA](https://img.shields.io/badge/OPC_UA-4B5563?style=for-the-badge)
![Modbus](https://img.shields.io/badge/Modbus-4B5563?style=for-the-badge)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)
![LDAP / OAuth](https://img.shields.io/badge/LDAP%20%2F%20OAuth-4B5563?style=for-the-badge)

**AppSec**

![OWASP](https://img.shields.io/badge/OWASP_Top_10-000000?style=for-the-badge&logo=owasp&logoColor=white)
![Semgrep](https://img.shields.io/badge/Semgrep-1B2A41?style=for-the-badge&logo=semgrep&logoColor=white)
![CodeQL](https://img.shields.io/badge/CodeQL-2F363D?style=for-the-badge&logo=github&logoColor=white)
![Gitleaks](https://img.shields.io/badge/Gitleaks-B91C1C?style=for-the-badge)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=trivy&logoColor=white)
![Threat Modeling](https://img.shields.io/badge/Threat_Modeling-374151?style=for-the-badge)

**AI-assisted development**

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![LLM Agents](https://img.shields.io/badge/LLM_Agents-374151?style=for-the-badge)
