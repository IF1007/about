# MicroObs
A experimental solution involving observability for microservices class

## Time
 * Bruno Mota ([Gmail](mailto:bvgm@cin.ufpe.br) | [Github](https://github.com/brunomota18))
 * Carlos Zimmerle ([Gmail](mailto:cezl@cin.ufpe.br) | [Github](https://github.com/carloszimm))
 
## Escopo

### Objetivos 
  * Utilizar o padrão API gateway que servirá como ponto de integração para consumidores externos;
  * Criar um Sistema de Observabilidade onde seja facilmente retornado os logs e métricas armazenadas de maneira extensível suficiente para outras tarefas.


### Tecnologias
  * Node.js + GraphQL para API Gateway;
  * Go para Microservices como Exemplos;
  * Beats+Logstash+Elasticsearch para Centralized Logging;
  * Prometheus para Metrics Storage;
  * Grafana para Metrics+Logs Visualization;
  * Docker(+Compose) para Containers.
  
### Arquitetura

![arquitetura - 2](https://user-images.githubusercontent.com/4553211/90578275-44e00780-e199-11ea-985e-6b3fa461fc32.png)
