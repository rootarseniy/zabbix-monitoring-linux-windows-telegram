# zabbix-monitoring-linux-windows-telegram

**Мониторинг инфраструктуры через Zabbix (Linux, Windows, Telegram)**
Проект по развёртыванию и настройке полноценной системы мониторинга на базе Zabbix. Всё сделано по шагам от установки сервера до подключения агентов, настройки алертов и Telegram-уведомлений.

**Состав репозитория**
Zabbix Monitoring Setup with Linux Windows Telegram Alerts.docx - подробный отчёт с пояснениями и скриншотами

**Что использовал**
1. Ubuntu Server 22.04 (в VMware Workstation Pro)
2. Windows 10 (вторая ВМ, в той же сети)
3. Zabbix Server + Web Interface
4. Zabbix Agent (на Linux и Windows)
5. MariaDB, Apache, PHP
6. Telegram Bot API (для алертов)
7. Word (для описания проекта)
8. Скриншоты (для демонстрации каждого этапа)

**Как открыть и использовать проект**
1. Установить Zabbix Server на Ubuntu по инструкции (пошагово как показано в отчёте)
2. Подключить Linux и Windows-клиентов через агенты
3. Проверить метрики (CPU, диск, сеть) в интерфейсе
4. Подключить Telegram и протестировать алерты
5. Посмотреть Zabbix Monitoring Setup with Linux Windows Telegram Alerts.docx - в нём описан весь процесс, с пояснениями и скринами

**Автор проекта: Арсений (rootarseniy)**

**P.S.**

Этот проект создан для отработки реальных навыков системного администратора. Здесь я показал, как разворачивается и настраивается система мониторинга, как подключаются хосты и создаются автоматические уведомления.
