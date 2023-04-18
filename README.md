# anotacoes-pl-sql
Minhas anotações dos conhecimentos obtidos sobre PL/SQL.

Todo SGBD (Oracle, My SLQ Server, Postg...) possui uma linguagem de programacao propria 

A linguagem SQL possui apenas comandos de manipulacao de dados como leitura, gravacao, alteracao e remocao dos registros.

PL/SQL é uma extensão da linguagem padrão SQL para o SGBD Oracle da Oracle Corporation.

# COMO ESTRUTURAR BLOCOS DE CODIGONA LINGUAGEM PL/SQL

Um bloco de codigos e a estrutura principal de um programa PL/SQL.

As tres secoes da sua estrutura sao:

DECLARE secao onde e declarado as variaveis, constantes e cursores (opc)
BEGIN / END uma secao (obrig) pois e onde declaramos o objetivo do bloco
EXCEPTION secao onde se codifica o tratamento de erros.

number
dbms_output.put_line()
when others then
raise_application_error()


