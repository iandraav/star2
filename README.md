Desafio de Projeto: Modelagem Dimensional com Star Schema
Objetivo: Transformar uma base de dados única (Flat Table) em um modelo dimensional otimizado.

Etapas do Projeto:

ETL (Power Query): Decomposição da tabela Financial Sample em dimensões específicas: D_Produtos, D_Descontos e D_Detalhes.

Agregações: Utilização da função "Agrupar por" para extrair métricas de performance de produtos (Média, Máximo e Mínimo).

Criação de Chaves: Implementação de ID_Produto para garantir a integridade dos relacionamentos.

Modelagem: Estruturação do Star Schema com uma tabela fato central (F_Vendas) e tabelas dimensões ao redor, garantindo relacionamentos de 1:N.

Time Intelligence: Criação de uma tabela D_Calendário dinâmica via DAX.<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/fc22e873-a4e3-4307-9784-0a90f5ebe079" />
