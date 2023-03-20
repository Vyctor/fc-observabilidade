# Observabilidade

## Introdução

### O que realmente é observabilidade?

É proativamente coletar, vizualizar e aplicar inteligência em todas métricas, eventos, logs e traces.
É quão bem você pode entender o seu sistema.
A partir do momento que eu consigo inferir o estado do meu sistema através de seus outputs.

### Observabilidade x Monitoramento?

- Monitoramento mostra que há algo de errado.
- Monitoramento se baseia em saber com antecedência quais os sinais você deseja monitorar.

- Observabilidade nos permite pergunta o porquê algo está acontecendo (vejo o output do sistema para poder inferir o motivo de algo estar acontecendo)

### Os três pilares da observabilidade

- Métricas (são números, 10 pods, % de memória livre, quantidade de requests)
- Logs
- Tracing (ordernação dos eventos)

## Elastic Stack

### Elastic Search

- Search engine e analytics
- Foi criado em cima do Apache Lucene
- Surgiu em 2010
- Rápido
- Escalável
- Possui API Rest
- Análise e visualização geoespacial
- Application, website e enterprise search
- Logging e analytics
- Trabalha de forma distribuída através de shards que possuem redundâncias de dados

### Logstash

- Engine coletora de dados em tempo real (pega dados de múltiplos locais)
- Iniciou como manipulador de logs
- Trabalha com pipelines
- Recebe dados de múltiplas fontes
- Normaliza e transforma dados
- Envia dados para múltiplas fontes
- Possui sistem de plugins

### Kibana

- Ferramenta de visualização e exploração de dados
- Usada com
  - Logs
  - Análise de séries
  - Monitoramento de aplicações
  - Inteligência artificial
- Integrado com o elastic search
- Criação de dashboards, gráficos interativos, mapas

### Beats

- Foi anunciado em 2015
- Lightweight data shipper
- Agente coletor de dados
- Integrado facilmente com Elasticsearch ou Logstash
- Logs, métricas, network data, audit data, uptime monitoring
- Posso criar meus próprios Beats

**Quando falo de Elastic Stack estou falando de Elastic Search, Kibana, Beats e Logstash**. Essa é a stack mais moderna da Elastic, pois possui os Beats.

### Elastic

- Open Source
- Oferece plugins e recursos que são licenciados pela Elastic, e deverão ser pagos
- Produtos
  - APM
  - Maps
  - Site search
  - Enterprise search
  - App Search
  - Infrastructure
