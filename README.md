<h1>Sprint-02</h1>

<h3> Avaliação Sprint 02 </h3>

<p>
Para utilização do banco de dados, utilizei o MySQL Workbench.<br><br>
user: "root"<br>
password: "Lore2510@"<br><br>
</p>

<h4> Questão 01 </h4>
<p>
Para essa questão, eu criei a Database "produto" e a tabela "produto" por meio do MySQL Workbench
e cadastrei os produtospor meio do IntelliJ. <br>
  
**Criar a Database Produto:<br><br>
CREATE DATABASE produto;<br>

**Criar a tabela produto:<br><br>
CREATE TABLE `produto`.`produto`(<br>
`id` INT NOT NULL AUTO_INCREMENT,<br>
`nome` VARCHAR(45) NOT NULL,<br>
`descricao` VARCHAR(45) NOT NULL,<br>
`quantidade` VARCHAR(45) NOT NULL,<br>
`preco` DOUBLE NOT NULL,<br>
PRIMARY KEY (`id`));”<br>
</p>

<h4> Questão 02 </h4>
<p>
Para essa questão, eu criei a Database "filme" e as tabelas "pagina1" e "pagina2" por meio do MySQL Workbench
e cadastrei os filmes por meio do IntelliJ. <br>
  
**Para criar o banco de dados “filme”: <br><br>
CREATE DATABASE filme;<br>
  
**Criando a tabela “pagina 1”:<br><br>
CREATE TABLE `filme`.`pagina1` (<br>
`id` INT NOT NULL AUTO_INCREMENT,<br>
`nome` VARCHAR(45) NOT NULL,<br>
`descricao` VARCHAR(200) NOT NULL,<br>
`ano` VARCHAR(4) NOT NULL,<br>
PRIMARY KEY (`id`));<br><br>
  
**Criando a tabela “página 2”:<br><br>
  
CREATE TABLE `filme`.`pagina2` (<br>
`id` INT NOT NULL AUTO_INCREMENT,<br>
`nome` VARCHAR(45) NOT NULL,<br>
`descricao` VARCHAR(200) NOT NULL,<br>
`ano` VARCHAR(4) NOT NULL,<br>
PRIMARY KEY (`id`));<br>
  </p>

<h4>Questão 3</h4>
<p>Nessa questão, usei apenas i IntelliJ, visto que não havia a necessidade de armazenar os dados, apenas de compará-los.</p>



