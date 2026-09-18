<h1 align="center">📡 discovery</h1>

<p align="center"><i>Система мониторинга сетевых устройств для интернет-провайдеров</i></p>

<p align="center">
  <a href="https://seelentov.github.io/discovery-landing/"><img src="https://img.shields.io/badge/сайт-35b6a6?style=for-the-badge" /></a>
  <a href="https://seelentov.github.io/discovery-landing/download.html"><img src="https://img.shields.io/badge/скачать-35b6a6?style=for-the-badge" /></a>
  <a href="https://seelentov.github.io/discovery-landing/docs.html"><img src="https://img.shields.io/badge/документация-35b6a6?style=for-the-badge" /></a>
  <a href="https://github.com/seelentov/discovery-releases"><img src="https://img.shields.io/badge/релизы-35b6a6?style=for-the-badge" /></a>
</p>

Обнаруживает коммутаторы, OLT и другое сетевое оборудование в сети по SNMP, опрашивает
метрики, поднимает тревоги при отклонениях и шлёт уведомления в Telegram/email/webhook —
без облака, полностью на инфраструктуре клиента. Написан на Rust, дашборд на React;
бинарники для macOS/Windows/Linux (arm64 и x86_64), автоматический бесплатный пробный
период без регистрации.

<p align="center">
  <img src="https://raw.githubusercontent.com/seelentov/discovery-landing/main/assets/img/shot-overview.png" width="720" alt="discovery — дашборд, обзор сети" />
</p>

- **Автодискаверинг** — сканирование подсетей по SNMP, устройство заводится само при первом ответе
- **Профили опроса** — любые OID, любая периодичность, тревоги с гистерезисом (без дребезга на границе порога)
- **Топология и групповые тревоги** — при аварии на магистрали видно причину, а не сотню однотипных уведомлений
- **SNMP v1/v2c/v3 + Trap/Syslog + SSH CLI-метрики**, ролевой доступ, REST API

Документация — [discovery-info](https://github.com/seelentov/discovery-info),
готовые бинарники — [discovery-releases](https://github.com/seelentov/discovery-releases).
