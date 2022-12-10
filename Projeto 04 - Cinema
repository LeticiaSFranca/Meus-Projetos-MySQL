create database cinema_exercicio5;
use cinema_exercicio5;

create table cinema(
cod_cinema int not null primary key auto_increment,
nome varchar(20) not null,
rua varchar(80) not null,
numero int not null,
bairro varchar(80) not null,
cidade varchar(80) not null,
estado varchar(80) not null,
lotacao int not null
);

create table exibicao(
cod_exibicao int not null primary key auto_increment,
data_inicio date not null,
data_fim date not null
);

create table filme(
cod_filme int not null primary key auto_increment,
titulo varchar(80) not null,
ano int not null,
genero varchar(10) not null,
faixa_etaria int not null
);

select * from cinema;
describe cinema;
insert into cinema (nome, rua, numero, bairro, cidade, estado, lotacao) values
("nome1", "rua1", 1, "bairro1", "cidade1", "estado1", 1),
("nome2", "rua2", 2, "bairro2", "cidade2", "estado2", 2),
("nome3", "rua3", 3, "bairro3", "cidade3", "estado3", 3);

select * from exibicao;
describe exibicao;
insert into exibicao (data_inicio, data_fim) values
(2000/02/01, 2000/02/04),
(2000/02/02, 2000/02/05),
(2000/02/03, 2000/02/06);

select * from filme;
describe filme;
insert into filme (titulo, ano, genero, faixa_etaria) values
("titulo1", 2000/02/01, "romance", 10),
("titulo2", 2000/02/02, "terror", 12),
("titulo3", 2000/02/03, "aventura", 14);

delete from cinema where cod_cinema = 2; 
delete from exibicao where cod_exibicao = 3;
delete from filme where cod_filme = 1;

update cinema set nome = "nome1" where cod_cinema = 1;
update exibicao set data_inicio = 2000/02/02 where cod_exibicao = 2;
update filme set titulo = "titulo1" where cod_filme = 3;
