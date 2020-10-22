# MicroObs
MicroObs é um projeto, parte da disciplina [IF1007/IN1062](https://github.com/IF1007/IF1007) ministrada pelo Prof. [Vinicius Garcia](http://viniciusgarcia.me/), que visa prover uma solução para observalidade que possa ser facilmente integrada/consumida.

## Equipe
 * Bruno Mota ([Gmail](mailto:bvgm@cin.ufpe.br) | [Github](https://github.com/brunomota18))
 * Carlos Zimmerle ([Gmail](mailto:cezl@cin.ufpe.br) | [Github](https://github.com/carloszimm))
 
## Escopo

### Objetivos 
  * Utilizar o padrão API gateway que servirá como ponto de integração para consumidores externos;
  * Criar um Sistema de Observabilidade onde seja facilmente retornado os logs e métricas armazenadas de maneira extensível suficiente para outras tarefas.


### Tecnologias
  * Node.js/Express + GraphQL para o API Gateway;
  * Beats(filebeat) + Elasticsearch para Centralized Logging;
  * Prometheus para Metrics Storage;
  * Grafana para Metrics + Logs Visualization;
  * Docker(+Compose) para Containers.
  * *(Go para Microservices de Exemplo)*
  
### Arquitetura
<p align="center">
  <img src="https://user-images.githubusercontent.com/4553211/96804651-03ace380-13e6-11eb-91ed-cb4a279c4849.png">
</p>
