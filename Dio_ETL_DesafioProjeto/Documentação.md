# Documentação do Desafio de Projeto com PowerBi

## Etapa 1: Verificação de Problemas na Base de Dados

- Realizamos uma análise preliminar da base de dados para identificar problemas que precisam ser resolvidos antes de usar os dados.

## Etapa 2: Verificação dos Cabeçalhos e Tipos de Dados

- Examinamos os cabeçalhos das tabelas e os tipos de dados das colunas para garantir que estejam corretos.

## Etapa 3: Modificação dos Valores Monetários para o Tipo Double Preciso

- Convertemos os valores monetários nas tabelas para o tipo `double preciso` para garantir precisão nos cálculos.

## Etapa 4: Verificação de Existência de Nulos e Análise da Remoção

- Identificamos colunas com valores nulos e analisamos se devem ser removidos, substituídos ou tratados de outra forma.

## Etapa 5: Identificação de Employees Sem Gerentes

- Identificamos funcionários (employees) que têm valores nulos na coluna `Super_ssn`. Supomos que esses funcionários sejam gerentes. Verificamos se há colaboradores sem gerente.

## Etapa 6: Verificação de Departamentos Sem Gerentes

- Verificamos se há departamentos sem gerentes e, se necessário, preenchemos as lacunas com informações disponíveis.

## Etapa 7: Verificação do Número de Horas dos Projetos

- Analisamos o número de horas dos projetos para garantir que os dados estejam corretos e dentro dos limites aceitáveis.

## Etapa 8: Separação de Colunas Complexas

- Dividimos colunas complexas em colunas separadas, se necessário, para facilitar a análise.

## Etapa 9: Mesclagem de Consultas Employee e Departament

- Mesclamos as consultas de funcionários e departamentos para criar uma tabela de funcionários com os nomes dos departamentos associados aos colaboradores. A mescla é baseada na tabela de funcionários. Colunas desnecessárias são eliminadas neste processo.

## Etapa 10: Mesclagem de Colunas de Nome e Sobrenome

- Unimos as colunas de nome e sobrenome para criar uma única coluna contendo o nome completo dos colaboradores.

## Etapa 11: Agrupamento de Dados para Contar Colaboradores por Gerente

- Agrupamos os dados para determinar quantos colaboradores estão sob a supervisão de cada gerente.

## Etapa 13: Eliminação de Colunas e Tabelas Desnecessárias

- Removemos colunas que não serão usadas no relatório final, reduzindo a complexidade e o tamanho dos dados.

O processo descrito acima resultou em dados preparados e limpos para serem utilizados no Power BI. Os dados estão prontos para serem explorados e apresentados em relatórios.

A documentação deste processo foi criada para futuras referências e para facilitar a colaboração no GitHub.
Algumas coisas não consegui fazer, espero colaboração para melhorar o banco de dados.

* Data de Conclusão: 13/10/2023
* Autor: Matheus Almeida