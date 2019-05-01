# api-zabbixlatam-2019
Repositório com os arquivos da apresentação da palestra [Monitoramento de Aplicações Web Modernas com Zabbix](https://www.slideshare.net/andredeo/monitoramento-de-aplicaes-web-modernas-com-zabbix) apresentada na [Zabbix Conference LatAm 2019](https://conference.zabbix.com.br)

## Imagem Docker
```sh
$ docker pull thalesreis/zabbixconf
$ docker run -d -p 8080:80 --name zabapi thalesreis/zabbixconf
```

O acesso pode ser feito nos endereços:
```sh
http://localhost:8080/api/health
http://localhost:8080/api/zabbix
```

## Documentação e Exemplos no Postman
Basta baixar o arquivo [ZabbixConf.postman_collection.json](https://github.com/andredeo/api-zabbixlatam-2019/blob/master/ZabbixConf.postman_collection.json) e importar no [Postman](https://www.getpostman.com/).

## Zabbix
Basta importar o arquivo [zbx_export_hosts.xml](https://github.com/andredeo/api-zabbixlatam-2019/blob/master/zbx_export_hosts.xml) que o host APIs será criado. **Não se esqueça de alterar as Macros do host.**
