# Awesome Marzban

## Основное
- [Блок о прокси](https://marzban.dev/)
- [GitHub Marzban](https://github.com/Gozargah/Marzban)
- [Документация Marzban на русском](https://marzban-docs.sm1ky.com)
- [Группа Marzban в Telegram](https://t.me/gozargah_marzban)



## Бекап
### Бекап панели
- [Backuper](https://github.com/erfjab/Backuper)
- [Marzban backup (Telegram)](https://github.com/jomertix/marzban-tools/tree/master/backup/marzban)
- [Marzban backup (rclone)](https://github.com/ElitraProject/marzban-backup)
- [Marzban backup (Telegram, Discord)](https://github.com/M03ED/Marzban_Backup)
- [AC-Lover](https://github.com/AC-Lover/backup)
- [Marzban backup (логи + панель)](https://github.com/terbyn/Marzban_logs_backupTG)

### Бекап логов
- [Logs backup (Telegram)](https://github.com/jomertix/marzban-tools/tree/master/backup/logs)
- [Marzban backup (логи + панель)](https://github.com/terbyn/Marzban_logs_backupTG)



## Миграция
- [X-UI -> Marzban](https://github.com/ItsAML/X-Ui-to-Marzban)
- [Hiddify -> Marzban](https://github.com/ItsAML/Hiddify-To-Marzban)
- [SQLite -> MySQL](https://github.com/mobinalipour/marzban-to-mysql)

## Ограничение пользователей
- [V2IpLimit](https://github.com/houshmand-2005/V2IpLimit) - при достижении лимита подключений блокируется аккаунт
- [luIP-marzban (UFW)](https://github.com/sm1ky/luIP-marzban) - при достижении лимита блокируются только новые подключения
- [luIP-marzban (iptables)](https://github.com/mmdzov/luIP-marzban) - при достижении лимита блокируются только новые подключения. Устаревший проект, не рекомендуется к использованию на проде

## Шаблоны подписок
- [Minimalistic Sub Page](https://github.com/jomertix/marzban-tools/tree/master/subscription)
- [x0sina sub](https://github.com/x0sina/marzban-sub)
- [marzban-sub-ru](https://github.com/DigneZzZ/marzban-sub-ru)
- [Clash](https://github.com/mahanmi/iran-clash-example)
- [Sing-box](https://github.com/oXIIIo/marzban-template)
- [marzban-custom-home](https://github.com/LibernetDigital/marzban-custom-home)

## Сканеры SNI
- [SNI-Checker (TLS 1.3, HTTP/2)](https://github.com/jomertix/SNI-Checker)
- [SNI-Checker (only TLS 1.3)](https://github.com/ElitraProject/SNI-Checker)

## Скрипты теста скорости, проверки доступности
Тест доступности сервисов на сервере:
```
bash <(curl -L -s https://bench.openode.xyz/checker.sh)
```
Тест для проверки Instagram:
```
bash <(curl -L -s https://bench.openode.xyz/checker_inst.sh)
```
Бенчмарк скорости:
```
wget -qO - bench.sh | bash
```
Бенчмарк скорости (регионы России):
```
wget -qO- bench.openode.xyz | bash
```
Тест доступности сервисов (Stream Platforms & Game Regions):
```
bash <(curl -L -s https://git.io/JRw8R) -E en -M 4
```

### Другие скрипты
Смена ядра Xray:
```
bash <(wget -qO- https://raw.githubusercontent.com/DigneZzZ/marzban_core_change/main/core.sh)
```
Расширенный скрипт для работы с Marzban с командой для обновления ядра (core-update)
```
sudo bash -c "$(curl -sL https://github.com/DigneZzZ/Marzban-scripts--n/raw/master/marzban.sh)" @ install
```
для установки скрипта:
```
sudo bash -c "$(curl -sL https://github.com/DigneZzZ/Marzban-scripts--n/raw/master/marzban.sh)" @ install-script
```
Тот же самый скрипт, но для нод Marzban:
```
sudo bash -c "$(curl -sL https://github.com/DigneZzZ/Marzban-scripts--n/raw/node/marzban-node.sh)" @ install
```
для установки скрипта:
```
sudo bash -c "$(curl -sL https://github.com/DigneZzZ/Marzban-scripts--n/raw/node/marzban-node.sh)" @ install-script
```

## API
- [marzpy](https://github.com/mewhrzad/marzpy)
- [marzban-api-client](https://github.com/oXIIIo/marzban-api-client)

## Коммерция/боты
- [marzban-shop](https://github.com/gunsh1p/marzban-shop)
- [SHM](https://github.com/danuk/shm)
- [botmirzapanel](https://github.com/mahdiMGF2/botmirzapanel)

## Управление пользователями
- [MarzbanExpiredUserRemover](https://github.com/ItsAML/MarzbanExpiredUserRemover)
- [Marzban_Inbound_Updater](https://github.com/M03ED/Marzban_Inbound_Updater)
- [Marzban_Flow_Select](https://github.com/M03ED/Marzban_Flow_Select)
- [holderbot](https://github.com/erfjab/holderbot)

## Аналитика/мониторинг
- [xray-checker](https://github.com/kutovoys/xray-checker)
- [marzban-node-monitor](https://github.com/sm1ky/marzban-node-monitor)
- [marzban_sqlite_streamlit](https://github.com/lifeindarkside/marzban_sqlite_streamlit)
- [marzban-grafana-pannel](https://github.com/lifeindarkside/marzban-grafana-pannel)
- [marzban-exporter](https://github.com/kutovoys/marzban-exporter)

## Генераторы inbound'ов
- [MarzbanInboundGenerator](https://azavaxhuman.github.io/MarzbanInboundGenerator)
- [Marzban-Reality-Generator](https://azavaxhuman.github.io/Marzban-Reality-Generator)

## Другие утилиты
- [marzban-torrent-blocker](https://github.com/kutovoys/marzban-torrent-blocker)
- [xray-online](https://mmmray.github.io/xray-online)


