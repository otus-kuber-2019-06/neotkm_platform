### Выполнено первое домашнее задание

Создан Dockerfile для сборки image web сервера  
Собран image web сервера и размещен на docker hub  
Создан манифест, для запуска контейнера с web сервером в kubernetes  
В репозиторий добавлены .travis.yml и PULL_REQUEST_TEMPLATE.md  


### Выполнено второе домашнее задание  
######  task01  
    Создан service account bob и ему назначена роль admin на весь кластер  
    Создан service account dave без доступа к кластеру  

######  task02  
    Создан namespace prometheus
    Создан service account carol в namespace prometheus  
    Всем  service account в  namespace prometheus даны права на get / list / watch pod`ов всего кластера  

######  task03  
    Создан namespace dev
    Создан service account jane в namespace dev  
    Service account jane в рамках namespace dev назначена роль admin  
    Создан service account ken в namespace dev  
    Service account ken в рамках namespace dev назначена роль view  
    
