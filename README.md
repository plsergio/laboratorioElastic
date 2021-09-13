# Laboratório Elastic Stack

### Requisitos
- [Docker Compose](https://docs.docker.com/compose/install/)
- Set vm.max_map_count to at least 262144:
  - ` sudo sysctl -w vm.max_map_count=262144 `

### Rode docker-compose para subir o Cluster:
- ` docker-compose up `

### Urls
- master: http://localhost:9200/
- kibana: http://localhost:5601/

### Consultas configuradas no Insomnia
- Instalar o [Insomnia](https://insomnia.rest/download).
- importar o arquivo [Insomnia_elastic.yaml](assets/Insomnia_elastic.yaml).
![](assets/insomnia.png)

### Extensões recomendadas:
- Chrome:
  - https://chrome.google.com/webstore/detail/elasticsearch-head/ffmkiejjmecolpfloofpjologoblkegm/related?hl=pt-BR

- Visual Studio:
  - [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
  - [Elasticsearch for VSCode](https://marketplace.visualstudio.com/items?itemName=ria.elastic)

### Documentação
- Query Strings:
  - https://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-query-string-query.html?baymax=rec&rogue=pop-1&elektra=guide

- Documentação de referência:
  - https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html
  - https://www.elastic.co/guide/en/elastic-stack-get-started/current/get-started-docker.html
