# docker-sonar
Docker sonarQube 5.1

Built on tpires/sonar-server

```
docker run -i -t -d --name sonar -p 9000:9000 --link smysql:db smnielsen/sonar-server
```
