# LuaWiki

**Uma wiki escrita em portugues-PT-BR a todo tempo e a qualquer hora**

### Introdução

**[Lua](https://www.lua.org/faq.html)** é uma linguagem de script poderosa, eficiente, leve e incorporável desenvolvida por uma equipe da PUC-Rio, a Pontifícia Universidade Católica do Rio de Janeiro no Brasil. Lua é um software livre usado em muitos produtos e projetos ao redor do mundo.

#### Como lua é implementada? <br> 

Lua consiste em duas partes - a parte do interpretador Lua e o sistema de software em funcionamento. O sistema de software em funcionamento é um aplicativo de computador real que pode interpretar programas escritos na linguagem de programação Lua. O interpretador Lua é escrito em ANSI C, portanto, é altamente portátil e pode ser executado em uma vasta gama de dispositivos, desde servidores de rede de ponta até dispositivos pequenos.


Caso tenha dúvidas [Discord API](https://discord.gg/NKM3XmF) servidor para discutir sobre lua e outras bibliotecas do Discord! <br> 
Caso não consiga entrar no discord [pt.stackoverflow](http://pt.stackoverflow.com/questions/tagged/lua) 

### Instalação no windows

Há um IDE separado chamado "SciTE" desenvolvido para o ambiente Windows, que pode ser baixado da seção https://code.google.com/p/luaforwindows/ download. 
<br> Caso você esteja interessado em instalar Lua em modo de linha de comando, você precisa instalar MinGW ou Cygwin e então compilar e instalar Lua no Windows.

### Instalação no linux
Para baixar e instalar lua, use o seguinte comando -

```linux
$ wget http://www.lua.org/ftp/lua-5.2.3.tar.gz
$ tar zxf lua-5.2.3.tar.gz
$ cd lua-5.2.3
$ make linux test
```
Para instalar em outras plataformas como aix, ansi, bsd, generic linux, mingw, posix, solaris substituindo Linux em make Linux, teste com o nome da plataforma correspondente.

### Documentation

Visite este projeto [Wiki](https://github.com/Nuno001/LuaWiki/wiki) para documentação e tutoriais.

### History

Lua é uma linguagem de programação extensível e leve escrita em C. Começou como um projeto interno em 1993 por Roberto Ierusalimschy, Luiz Henrique de Figueiredo e Waldemar Celes. <br> 
Ele foi projetado desde o início para ser um software que pode ser integrado ao código escrito em C e outras linguagens convencionais. Essa integração traz muitos benefícios. Ele não tenta fazer o que C já pode fazer, mas visa oferecer o que C não é bom: uma boa distância do hardware, estruturas dinâmicas, sem redundâncias, facilidade de teste e depuração. Para isso, Lua possui um ambiente seguro, gerenciamento automático de memória e boas facilidades para manipulação de strings e outros tipos de dados com tamanho dinâmico.

### FAQs

Por que lua?
- Lua é uma linguagem de script leve que tende a ser amigável para iniciantes, mas poderosa nas mãos de um usuário avançado ao mesmo tempo. Embora Lua possa não ter a mesma popularidade de outras linguagens de script, como Python ou JavaScript, a capacidade de expansão de Lua a torna tão capaz quanto as outras, enquanto permanece fácil de usar e geralmente mais eficiente em termos de recursos.

Existem outros tipos de sistemas em lua?

Sim! existem os que vou citar abaixo:
- [Luvit/Discordia](https://luvit.io/install.html) 
- [FiveM] (https://docs.fivem.net/docs/scripting-manual/runtimes/lua/)
- [Roblox] (https://developer.roblox.com/en-us/learn-roblox/coding-scripts)

Como posso ajudar a wiki?
- Pull request são bem-vindas, mas verifique com o autor da biblioteca antes de iniciar uma grande implementação. Contribuições para a Wiki também são úteis.
