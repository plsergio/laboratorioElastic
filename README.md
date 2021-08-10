# Laboratorio Elastic

### Requisitos
- [Docker Compose](https://docs.docker.com/compose/install/)
- Set vm.max_map_count to at least 262144:
  - ` sudo sysctl -w vm.max_map_count=262144 `

### Rode docker-compose para subir o cluster:
- ` docker-compose up `

### Submit a _cat/nodes request to see that the nodes are up and running:
- ` curl -X GET "localhost:9200/_cat/nodes?v=true&pretty" `
### Urls
- master: http://localhost:9200/
- kibana: http://localhost:5601/

### Documentação de referência:
- https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html
- https://www.elastic.co/guide/en/elastic-stack-get-started/7.9/get-started-docker.html