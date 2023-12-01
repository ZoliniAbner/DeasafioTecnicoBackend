Sistema de Registro com NodeJs + Express + MySQL

- Criação da base de dados e tabela:
	CREATE DATABASE loginDB;
	USE loginDB;

	CREATE TABLE usuarios(
	id INT NOT NULL AUTO_INCREMENT,
	name VARCHAR(50) NOT NULL,
	username VARCHAR(50) NOT NULL,
	password VARCHAR(200) NOT NULL,
	PRIMARY KEY (id)
	);

	DESC usuarios;
	SELECT * FROM usuarios;

 
