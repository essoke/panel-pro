## x-ui-pro (x-ui + nginx) модификация от https://github.com/GFW4Fun/x-ui-pro for REALITY
- Автоматическая установка (легковесная)
- Автоматическое продление SSL сертификата / Ежедневная перезагрузка Nginx X-ui
- Поддержка **REALITY** и **WebSocket** через **nginx**.
- Многопользовательский режим и настройка через порт **443**
- Автоматическое включение подписок через порт **443**
- Автоматическая настройка VLESS+Reality и VLESSoverWebSocket
- **Пользовательская веб-страница подписки**
- Функция использования **пользовательских конфигураций для SING-BOX & CLASH META**
- **Локальный сервер sub2sing-box**
- Автоматическая настройка файрвола
- Повышенная безопасность благодаря nginx
- Совместимость с Cloudflare (только для WebSocket/GRPC)
- 150+ случайных заглушек сайтов!
- Операционная система Linux Debian12/Ubuntu24!
- В будущем планируется добавление SOCKS5 прокси для телеграма
  >
   **ВАМ НЕОБХОДИМО 2 ДОМЕНА ИЛИ СУБДОМЕНА**
  1. Для панели и WebSocket/GRPC/HttpUgrade/SplitHttp
  2. Для маскировки REALITY
  >
  Получение бесплатных субдоменов - https://www.duckdns.org
  
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖

### Установка Panel-Pro

```
bash <(wget -qO- https://raw.githubusercontent.com/essoke/panel-pro/refs/heads/master/panel-pro.sh) -install yes
```
> 
> Не меняйте поддомен при обновлении SSL сертификата❗


**Деинсталляция Panel-Pro**:x:
```
sudo su -c "bash <(wget -qO- https://raw.githubusercontent.com/essoke/panel-pro/refs/heads/master/panel-pro.sh) -Uninstall yes"
```

**Бэкап панели и конфигурации nginx**:x:
```
sudo su -c "bash <(wget -qO- https://raw.githubusercontent.com/essoke/panel-pro/master/backup.sh)"
```

➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
### Screenshots :wrench:🐧⚙️
>
**How to open custom web sub page?**
>
![](https://github.com/legiz-ru/x-ui-pro/blob/master/media/CustomWebSubHow2Open.png?raw=true)
>
**Main Page custom web sub**
>
![](https://github.com/legiz-ru/x-ui-pro/blob/master/media/CustomWebSub.png?raw=true)
>
**sub2sing-box section on custom web sub page**
>
![](https://github.com/legiz-ru/x-ui-pro/blob/master/media/CustomWebSubSingBox.png?raw=true)
>
**local instance sub2sing-box fork by legiz**
>
![](https://github.com/legiz-ru/x-ui-pro/blob/master/media/sub2sing.png?raw=true)
