# docker-compose
Развертывание zabbix на ubuntu при помощи docker.

zabbix-server-pgsql 6.0 + zabbix-web-nginx-pgsql 6.0 + postgres:13.6

# Старт и остановка zabbix-сервера

## Старт
```bash
sudo docker-compose docker-compose.yaml up -d
```

## Остановка
```bash
sudo docker-compose docker-compose.yaml down
```
