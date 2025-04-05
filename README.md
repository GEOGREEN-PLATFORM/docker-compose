# Инструкция для запуска
Запустить команду  
```echo ${GITHUB_TOKEN} | docker login ghcr.io -u ${GITHUB_LOGIN} --password-stdin```  
Запустить docker-compose.yml
## Swaggers
* msa geospatial-server http://localhost:8091/swagger-ui/index.html
* msa file-sever http://localhost:8092/swagger-ui/index.html
* msa photo-analyser http://localhost:8093/swagger-ui/index.html
* msa event-manager http://localhost:8094/swagger-ui/index.html
* msa collect-user-markers http://localhost:8095/swagger-ui/index.html

## Веб-интерфейс
* http://localhost:3000
