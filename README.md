## Projeto Observabilidade

## Objetivo
Criar um ambiente de observabilidade via Docker usando Prometheus e Grafana para monitorar uma aplicação.

## Ferramentas Utilizadas
- Killercoda Linux (Ubuntu based) - https://killercoda.com/playgrounds/scenario/ubuntu
- Python Application
- Prometheus
- Grafana
- Docker

## Requisitos

- É necessário ter  uma máquina Linux (pode ser uma VM, um servidor ou mesmo uma máquina local com Docker instalado).
- Conhecimento básico de linha de comando do Linux.
- Docker instalado na máquina.
- Uma aplicação de exemplo para monitorar (nesse exemplo simples em foi feito em Python).
- Clonar o repositório do Projeto, pois terá os arquivos necessários para realizar cada etapa do projeto.

### 1º Passo :
1.1 Instalar em uma máquina Linux Ubunto o Docker compose:
```plaintext

 # comando para instalação
 $ sudo curl -L "https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

 # após a execução deste comando, os usuários com acesso sudo poderão executar o docker-compose como um programa.
 $ sudo chmod +x /usr/local/bin/docker-compose

```
1.2 Clonar este repositório
```plaintext

 # comando para clonar o repositório
 $ git clone https://gitlab.com/patrickjcardoso/desafio-observabilidade.git

 #  e acesse o diretório do laboratório:
 $ cd desafio_o11y/observability-lab

 ```

