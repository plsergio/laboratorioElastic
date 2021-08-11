# Laboratorio Elastic

### Requisitos
- [Docker Compose](https://docs.docker.com/compose/install/)
- Set vm.max_map_count to at least 262144:
  - ` sudo sysctl -w vm.max_map_count=262144 `

### Rode docker-compose para subir o cluster:
- ` docker-compose up `

### Urls
- master: http://localhost:9200/
- kibana: http://localhost:5601/

### Requests configurados no insomnia
- importar o arquivo [Insomnia_elastic.json](Insomnia_elastic.json) no Insomnia.

### Extensão do Chrome recomendada:
- https://chrome.google.com/webstore/detail/elasticsearch-head/ffmkiejjmecolpfloofpjologoblkegm/related?hl=pt-BR

### Documentação de referência:
- https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html
- https://www.elastic.co/guide/en/elastic-stack-get-started/current/get-started-docker.html
