# Descrição do Fluxo de Dados e Análise
## Objetivo:
Este projeto visa analisar e visualizar dados de redes sociais para obter insights sobre engajamento, usuários e interações com posts.

# Etapas do Processo:
Análise de Padrões em Dados JSON:

Utilizei uma visualização JSON para identificar os padrões de arrays e a estrutura de tabelas nos dados.

# Estruturação dos Dados:

Criei uma nova estrutura para os dados, abrindo cada JSON e organizando-os para análise.
Implementação do Código:

O código Python está contido no arquivo CÓDIGO.ipynb.

# Execução do Código:

O código é projetado para rodar no ambiente Databricks, sendo acionado pelo Azure DataFactory.
Integração com Data Warehouse:

Os dados são enviados e armazenados diretamente no data warehouse.

# Atualização no Power BI:

O Power BI é atualizado a cada 2 horas com os dados mais recentes do data warehouse.
Métricas Principais no Power BI:
Engajamento por Post: Mede o nível de envolvimento por cada post publicado.
Quantidade de Usuários: Total de usuários registrados.
Usuários que são Patronos: Contagem de usuários que são patronos.
Quantidade de Votos e Comentários por Post: Analisa a interação dos usuários através de votos e comentários em cada post.
Escore de Envolvimento: Métrica que envolve uma pontuação específica.
Quantidade de Posts por Dia: Estatística sobre o número de posts publicados diariamente.
