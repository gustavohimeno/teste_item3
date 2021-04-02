# teste_item3
- A consulta que responde ao problema do teste está no arquivo item3.sql
- A consulta gera como uma resposta um tabela com o nome dos alunos e suas respectivas notas consolidadas e notas exatas. 
- Aqueles que tiveram nota menor que 8 estão com o nome substituído por NULL.
- Os resultados estão ordenados pela nota consolidada.
- Em caso de empate dos estudantes com nota consolidada maior ou igual a 8, os dados foram ordenados pelos nomes em ordem alfabética(**).
- Em caso de empate entre os estudantes com nota menor que 8 os dados foram ordenados pela nota exata em ordem decrescente.
- O arquivo example_table.sqlite.sql indica a estrutura das tabelas Notes e Students que foram utilizadas para validação da consulta.
- Os arquivos Notes.json e Students.json apresentam os dados que foram carregados nas tabelas Notes e Students, indicadas no enunciado do problema. Esses dados de exemplo foram usados para validação da consulta

** há um erro no exemplo do enunciado, as estudantes Marcela e Julia tem nota consolidada igual a 9, ou seja, tem nota consolidada igual e maior, elas deveriam estar ordenadas em ordem alfabética, mas não estão.
** a resolução desconsiderou o que está apresentado como resultado e se baseou no que foi descrito pelo enunciado. 
