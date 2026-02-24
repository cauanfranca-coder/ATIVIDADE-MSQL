# ATIVIDADE-MSQL

-- create
CREATE TABLE Usuario (
  id  INT,
  name varchar(254)  NOT NULL,
  cpf char(14) NOT NULL,
  data_nasc date NOT NULL,
  email varchar(254) NOT NULL,
  primary key(id)
);

-- insert
INSERT INTO Usuario VALUES (01, 'Clark',
'089.617.955-97', 
'2012/12/12',
'jakeeotario@gmail.com');


-- fetch 
select * from Usuario;
