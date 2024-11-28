# Mattermost | La alternativa a #Slack y #Teams
Mattermost es un servicio de chat en línea de código abierto y alojable por cuenta propia que permite compartir archivos, realizar búsquedas e integrar aplicaciones de terceros. Está diseñado como un chat interno para organizaciones y empresas, y se promociona principalmente como una alternativa de código abierto a Slack y Microsoft Teams.


## Ejecutar estos comandos antes de instalar la app
$ mkdir -p /opt/docker/mattermost && cd /opt/docker/mattermost

$ mkdir -p /opt/docker/docker_data/postgresql/data && mkdir -p /opt/docker/docker_data/mattermost/{config,data,logs,plugins,client/plugins,bleve-indexes}

$ chmod -R 777 /opt/docker/docker_data/mattermost/config


## Instalamos la app con estos comandos

$ docker-compose up -d

## Iniciar la app 
Ver en "localhost:8065" ó "Ip:puerto" / "https://tudominio.com"
