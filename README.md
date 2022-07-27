# LuaSQL

## Suporte
Para obter suporte, entre no [servidor de suporte do discord.](https://discord.gg/M8gwNKqaXC)

# Conectar
Para abrir uma conexão com SQLUA você pode fazer o seguinte exemplo.   
```lua
require "luasql.mysql"
env = assert (luasql.mysql())
con = assert (env:connect"meu_db")
for id, name, address in rows (con, "select * from contacts") do
  print (string.format ("%s: %s", name, address))
end
```

### Callback
Um exemplo simples de criação de tabela Ele cria uma tabela com dois parâmetros id do tipo integer e name do tipo varchar.

#### Create Table Example
```lua
mysql = require "luasql.mysql"
local env  = mysql.mysql()
local conn = env:connect('test','root','123456')
print(env,conn)

status,errorString = conn:execute([[CREATE TABLE sample2 (id INTEGER, name TEXT);]])
print(status,errorString )

```
#### Quando você executa o programa acima, uma tabela chamada sample será criada com duas colunas, a saber, id e name.

```lua
MySQL environment (004BB178) MySQL connection (004BE3C8)
0 nil
```
