Visão Geral do Projeto

Este projeto foi desenvolvido para demonstrar a criação e implementação de uma Directed Acyclic Graph (DAG) utilizando Apache Airflow. O foco foi a ingestão e transformação de dados do Banco Central do Brasil relacionados à cotação de moedas, com o objetivo de automatizar o download e o processamento desses dados a partir de um arquivo CSV disponível em um endpoint público.

## Objetivos do Projeto

- Ingestão de Dados: Implementar um fluxo de trabalho automatizado para o download diário das cotações de moedas, garantindo a atualização contínua e a disponibilidade das informações.
- Transformação de Dados: Processar os dados até a camada Silver, utilizando técnicas de limpeza e transformação para assegurar a qualidade e a integridade das informações.
- Versionamento: Armazenar versões das cotações, permitindo rastreamento e auditoria ao longo do tempo.

## Tecnologias Utilizadas

- Apache Airflow: Para orquestração de tarefas e agendamento de fluxos de trabalho.
- PostgreSQL: Como banco de dados local para armazenamento das cotações de moedas.
- Docker: Utilizado para isolar o ambiente de desenvolvimento, garantindo consistência na execução do projeto.
- Astro CLI e SDK: Facilitando a configuração e o gerenciamento do ambiente virtual dentro de um container Docker.

## Considerações Finais

Este projeto exemplifica a capacidade de orquestrar e gerenciar processos de ETL em um ambiente controlado, destacando habilidades em manipulação de dados, automação e versionamento. A utilização de tecnologias modernas e práticas recomendadas reforça a robustez e a escalabilidade da solução proposta.
