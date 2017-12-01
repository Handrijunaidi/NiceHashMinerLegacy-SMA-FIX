# NiceHashMinerLegacy-SMA-FIX
NiceHashMinerLegacy.exe ver 1.8.1.5 with fix off "Unable to get NiceHash profitability data" while getting SMA data.
NiceHashMinerLegacy.exe ver 1.8.1.5 с исправлением ошибки "не удается получить данные прибыльности Nicehash" при получении данных SMA Nicehash.

## Ссылка

https://github.com/xtrime-ru/NiceHashMinerLegacy-SMA-FIX/releases/download/1.8.1.5-sma-fix/NHML-1-8-1-5_sma_fix.zip

## Описание

Скомпилированные исправления от @Sav87 из данного pull-request'a: https://github.com/nicehash/NiceHashMinerLegacy/pull/625
Если NiceHash не получается получить данные по протоколу webscoket то данная версия обращается к серверу по старому протоколу. При этом данные баланса не отобразятся, но майнинг будет рабоать корректно. VPN и перезапуски программы больше не нужны. Исправления одобрены командой NiceHashMinerLegacy и будут в ключены в один из следующих релизов. Но пока это не сделано, можно использовать эту версию с фиксом. 

## Инструкция: 
1) Распаковать файлы в папку с установленным NiceHashMinerLegacy версии 1.8.1.5 или 1.8.2 с заменой. 
2) Запустить
3) Подтвердить запуск файла без цифровой подписи (если операционная система будет ругаться).

Баланс при запуске не может не отображаться, но майнинг будет работать. 

Как только websocket соединение поднимется, то и баланс отобразится.

При наличии проблем можно просто перезаписать файлы официальными.

### Если вам помог этот фикс то:

* BTC: 1LQB96xHxBM9ZwF5QtsXyEB1ynYdhz55yr
* ETH: 0x4a073c8a31c96d770eb5c4ba25a9ee08a9cd51f4
* ZEC: t1dVGwSWBLqAnV2Fy1ZuxC5aq1iCJVEQ3N9
