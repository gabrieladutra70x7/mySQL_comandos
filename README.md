# mySQL_comandos
Bloco de Anotações (WILA) - Conteúdo : mySQL
# TABELA DE COMANDOS USADOS
| COMANDO | FUNÇÃO | CONSIDERAÇÕES |
|:-----:|:-----:|:------:|
| `mysql -u root`| Inicia o MySQL | `-u`: parâmetro de usuário; `root`: usuário |
| `create database escola_db;` | Cria um novo banco de dados | `escola_db`: nome do banco de dados |
| `show database;` | Mostra os parâmetros dos bancos de dados | N/A |
| `drop database escola_dp;` | Apaga o banco de dados inteiro | N/A |
| `use escola_db;` | Entra no banco de dados inserido | N/A | 
| `create table alunos;` | Cria uma nova tabela | `alunos`: nome da tabela |
| `insert into alunos (colunas) values (linha);` | Insere os valores (linha) na tabela (conforme as colunas) | `(colunas)`* e `(linha)`**: a nível de EXEMPLIFICAÇÃO |
| `drop table alunos;` | Apaga a tabela inteira | N/A |
|`select * from alunos;`| Mostra a tabela inteira | `*`: seletor - Puxa todas as colunas |
|`select  nome from alunos;`| A especificamente a coluna de nomes | `nome`: parâmetro (especificação)|
|`update alunos set nome = 'Alice Souza' where matricula = 1;`| `update` faz uma alteração definitiva em um registro | IMPORTANTE ESPECIFICAR: `set nome`: Onde será a atualização (na coluna `nome`), `where matricula = 1`: filtro -> alteração será realizada no nome registrado na `matricula` `1` ;|
|`delete from alunos where nome = Gabriel Souza` | Deleta (definitivamente) da tabela `alunos` a linha do nome Gabriel Souza | `where`: filtro (IMPORTANTÍSSIMO)|

**Conteúdo de `(colunas)`: (matrícula `int`, nome `varchar(50)`, cpf `varchar(11)`);*  
** *Conteúdo de `(linhas)`: (1, Rafaela Souza, 12345678900);*

**O linguagem SQL obedece a ordem dos elementos** 
| Matrícula | Nome| CPF |
|:-----:|:-----:|:------:|
| 1 | Rafaela Souza | 12345678900 |
## Importantes

* `int` = Número Inteiro, sem vírgulas.
* `VARCHAR(50)` = Texto com limite de 50 caracteres.
* `VARCHAR(11)` = Texto com limite de 11 caracteres.
* **NÃO ESQUECER O `;`**
* Textos sempre em aspas simples ''.

