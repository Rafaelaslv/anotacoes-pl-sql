## 👽📣 Hey terráqueos!!



### Este repositório conterá minhas anotações dos conhecimentos obtidos sobre PL/SQL através do canal Fulltureschool.

Todo SGBD (ORACLE DATABASE, MYSQL, SQL SERVER, POSTGRESQL...) possui uma linguagem de programação própria. 

A linguagem SQL possui apenas comandos de manipulacao de dados como leitura, gravacao, alteracao e remocao dos registros.

PL/SQL é uma extensão da linguagem padrão SQL para o SGBD Oracle Database da Oracle Corporation.

#### COMO ESTRUTURAR BLOCOS DE CÓDIGO NA LINGUAGEM PL/SQL

Um bloco de código é a estrutura principal de um programa PL/SQL.

As tres sessões da sua estrutura são:

DECLARE onde é declarado as variáveis, constantes e cursores. E é opcional.
BEGIN / END uma seção obrigatória pois é onde declaramos o objetivo do bloco.
EXCEPTION seção onde codificamos o tratamento de erros.

#number
dbms_output.put_line()
when others then
raise_application_error()#




