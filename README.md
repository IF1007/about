# MicroObs
MicroObs é um projeto, parte da disciplina [IF1007/IN1062](https://github.com/IF1007/IF1007) ministrada pelo Prof. [Vinicius Garcia](http://viniciusgarcia.me/), que visa prover uma solução para observalidade que possa ser facilmente integrada/consumida.

## Equipe
 * Bruno Mota ([Gmail](mailto:bvgm@cin.ufpe.br) | [Github](https://github.com/brunomota18))
 * Carlos Zimmerle ([Gmail](mailto:cezl@cin.ufpe.br) | [Github](https://github.com/carloszimm))
 
## Escopo

### Objetivos 
  * Utilizar o padrão API gateway para facilitar a consumação de dados de observabilidade pelos serviços interessados, seja interno ou externo;
  * Oferecer um sistema de observabilidade de fácil uso e baseado em containers contendo ferramentas que endereçam aspectos de logging e métricas.


### Tecnologias
  * Node.js/Express + GraphQL para o API Gateway;
  * Beats(filebeat) + Elasticsearch para Centralized Logging;
  * Prometheus para Metrics Collection/Storage;
  * Grafana para Metrics + Logs Visualization;
  * Docker + Docker-Compose para containers.
  
### Repositórios
  * [MicroObs](https://github.com/microobs/microobs) - Principal repositório do projeto contendo as configurações das ferramentas de observabilidade utilizadas e o script do docker-compose.
  * [Gateway](https://github.com/microobs/gateway) - Repositório contendo o código do API gateway do projeto.
  
### Arquitetura
<p align="center">
  <img src="https://user-images.githubusercontent.com/4553211/96804651-03ace380-13e6-11eb-91ed-cb4a279c4849.png">
</p>

#### Visão Alternativa (Backends for Frontends)
<p align="center">
 <img src="https://user-images.githubusercontent.com/4553211/97816037-1c808900-1c71-11eb-863f-e20acde518e2.png">
</p>
