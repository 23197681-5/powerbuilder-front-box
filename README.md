# powerbuilder-front-box

Use ibm db2 connection, and use this sql:

```sql
create table w_produto (
  pk_id integer,
  descricao varchar(4),
  preco decimal(15, 2),
  quantidade decimal(15, 2)
  )
  
select * from client
drop table client;
create table client(
        name varchar(23),
        id integer primary key generated always as identity not null default 0
);
go
commit

insert into client ( name ) values ('Roberta Franca')
select * from client

Create table phone(
description varchar(11),
id integer primary key generated always as identity not null,
parentid integer not null
)

Create table Historico_compras(
Id integer primary key generated always as identity not null,
Caixa varchar(23) not null,
Custototal decimal(10,2),
Funcionario varchar(23) not null,
Data date not null,
Hora time not null
) ALTER TABLE historico_compras
      ALTER COLUMN custototal
      SET DATA TYPE decimal(20,2)
GO
COMMIT


Create table last_user(
Id integer primary key generated always as identity not null,    
Name varchar(31) not null,
Senha varchar(31) not null
)


create table NivelDeAcesso(
name varchar(64) primary key not null,
categoria varchar(64) not null
)

create table TelasAcessiveis(
Nivel integer not null primary key,
Venda char(1) not null,
Caduser char(1) not null,
CadProd char(1) not null,
CadNiveis char(1) not null,
Imprimir char(1) not null,
Historico char(1) not null,
Categorias char(1) not null
)

Create table Chat_CISSMIRIM(
        Id integer primary key generated always as identity NOT NULL,
        Nome VARCHAR(50) NOT NULL,
        Companhia VARCHAR (30) NOT NULL,
        Mensagem VARCHAR (500)NOT NULL,
        Data DATE NOT NULL,
        Hora VARCHAR(8) NOT NULL)
GO COMMIT

Create table LOG (
        Id integer primary  key generated always as identity,
        Usuario varchar(31) not null,
        Acao varchar(300) not null,
        data date not null,
        horavarchar(8) not null
)

```
##in the login use
User: suporte
Password: suporte
and all privileges will be given to you.

 ![picture alt](https://lh5.googleusercontent.com/a7zW6JoVhOCXht-9DVksWM3ZylhhcalyUk7Gjb7lL68c08gg0Lq3IGMOQbBCKl1mJkSMFAyVUPmocCo=w1301-h702-rw "FrontBoxLogin")
