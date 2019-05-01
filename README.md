# api-zabbixlatam-2019
Repositório com os arquivos da apresentação da palestra Monitoramento de Aplicações Web Modernas com Zabbix apresentada na Zabbix Conference LatAm 2019

#Imagem Docker
```sh
docker pull thalesreis/zabbixconf
docker run -d -p 8080:80 --name zabapi thalesreis/zabbixconf
```

O acesso pode ser feito nos endereços:
```sh
http://localhost:8080/api/health
http://localhost:8080/api/zabbix
```
