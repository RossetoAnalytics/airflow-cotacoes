# Visão Geral do Projeto

Este projeto foi desenvolvido para demonstrar a criação e implementação de uma DAG utilizando Apache Airflow. O foco foi a ingestão e transformação de dados do Banco Central do Brasil relacionados à cotação de moedas, com o objetivo de automatizar o download e o processamento desses dados a partir de um arquivo CSV disponível em um endpoint público.

[endpoint público](https://www.bcb.gov.br/estabilidadefinanceira/cotacoestodas)

<details>
  <summary>DAG</summary>

  ![dag_fin_cotacoes_bcb](https://github.com/user-attachments/assets/e3175878-cc25-4c3c-bed1-4738d52f8e43)

</details>

### Objetivos do Projeto

- Ingestão de Dados: Implementar um fluxo de trabalho automatizado para o download diário das cotações de moedas, garantindo a atualização contínua e a disponibilidade das informações.
- Transformação de Dados: Processar os dados até a camada Silver, utilizando técnicas de limpeza e transformação para assegurar a qualidade e a integridade das informações.
- Versionamento: Armazenar versões das cotações, permitindo rastreamento e auditoria ao longo do tempo.

### Tecnologias Utilizadas

- Apache Airflow: Para orquestração de tarefas, definição de conexões e agendamento de fluxos de trabalho.
- PostgreSQL: Como banco de dados local para armazenamento das cotações de moedas.
- Docker: Utilizado para isolar o ambiente de desenvolvimento, garantindo consistência na execução do projeto.
- Astro CLI e SDK: Facilitando a configuração e o gerenciamento do ambiente virtual dentro de um container Docker.

<details>
  <summary>Resultado</summary>
  
  ![dbeaver_fin_cotacoes](https://github.com/user-attachments/assets/0ec78be5-bf90-4bdb-81d8-58bbe634cd0a) 

</details>

### Considerações Finais

Este projeto exemplifica a capacidade de orquestrar e gerenciar processos de ETL em um ambiente controlado, destacando habilidades em manipulação de dados, automação e versionamento. A utilização de tecnologias modernas e práticas recomendadas reforça a robustez e a escalabilidade da solução proposta.
