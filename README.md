# mySQL_comandos
Bloco de Anotações (WILA) - Conteúdo : mySQL
# TABELA DE COMANDOS USADOS
| COMANDO | FUNÇÃO | CONSIDERAÇÕES |
|:-----:|:-----:|:------:|
| `mysql -u root`| Inicia o MySQL | `-u`: parâmetro de usuário; `root`: usuário |
| `create database escola_db` | Cria um novo banco de dados | `escola_db`: nome do banco de dados |
| `show database` | Mostra os parâmetros dos bancos de dados | N/A |
| `drop database escola_dp` | Apaga o banco de dados inteiro | N/A |
| `use escola_db` | Entra no banco de dados inserido | N/A | 
| `create table alunos` | Cria uma nova tabela | `alunos`: nome da tabela |
| `insert into alunos (colunas) values (linha)` | Insere os valores (linha) na tabela (conforme as colunas) | `(colunas)`* e `(linha)`**: a nível de EXEMPLIFICAÇÃO |
| `drop table alunos` | Apaga a tabela inteira | N/A |
|`select * from alunos`| Mostra a tabela inteira | `*`: seletor - Puxa todas as colunas |
|`select  nome from alunos`| A especificamente a coluna de nomes | `nome`: parâmetro (especificação)

* *Conteúdo de `(colunas)`: (matrícula `int`, nome `VARCHAR(50)`, cpf `VARCHAR(11)`)*
** *Conteúdo de `(linhas)`: (1, Rafaela Souza, 12345678900)*


