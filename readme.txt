Passo a passo para executar a aplicação:

1 - Baixe o ArangoDB.

2 - Abra um terminal e digite "arangod" e execute.

3 - Em outro terminal, digite "arangodb" e execute.

4 - Execute os arquivos na seguinte ordem: database/insertDatabaseDeputados, database/insertDatabaseLeis, 
database/insertPEC

5 - Execute o arquivo main.

6 - Em um browser, digite "localhost:20000" e acesse a aplicação.

Caso queira acessar a interface do banco de dados, digite na barra de busca de um browser "localhost:8529", ou 
a porta estabelecida pelo seu sistema operacional. Para saber a porta, basta acessar o terminal que digitou "arangod"
e encontrar a linha "INFO [6ea38] {general} using endpoint 'http+tcp://127.0.0.1:XXXX' for non-encrypted requests", 
onde XXXX é a porta de acesso.