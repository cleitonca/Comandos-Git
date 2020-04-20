# Git e GitHub

Ótimo resumo do Git e GitHub.

## Sumário

[2.Quero começar a usar o Git, como faço?](#2)<br/>
&ensp;&ensp;[2.1Formas de usar o git](#2.1)<br/>
&ensp;&ensp;[2.2Instalando no Windows](#2.2) <br/>

<br/>
<br/>


## <a name=“2.1”><a/> Quero começar a usar o Git, como faço?
  
<h3> 1º) Você precisa saber que existem várias formas diferentes de usar o Git. </h3>

São elas:

> a) Ferramentas originais de linha de comando;<br/>
> b) Interfaces gráficas de usuário (GUI - Graphical User Interface) com opções variadas. (<a href="https://git-scm.com/downloads/guis">Ver sobre isso</a>)

A linha de comando é o único lugar onde você pode rodar <b>todos</b> os comandos do Git - a maioria das GUI implementa somente um subconjunto das funcionalidades do Git. 

Se você sabe como usar o Git na linha de comando, você provavelmente descobrirá como rodar versões GUI, enquanto o oposto não é necessariamente verdade. Além disso, enquanto a sua escolha da interface gráfica é uma questão de gosto pessoal, todos os usuário terão as ferramentas de linha de comando instaladas e disponíveis.


## <a name=“2.2”><a/> <h3>Windows</h3>

<a href="https://git-scm.com/download/win">Baixar o Git</a>
  
## <a name=“3”><a/> Comandos

<h2> Criar/Iniciar novo repositório: </h2>

git init

<h2> Verificar estado dos arquivos/diretórios: </h2>

git status
  
<h2> Adicionar arquivo/diretório (staged area): </h2>

<h3> Adicionar um arquivo em específico: </h3>

git add meu_arquivo.txt

<h3> Adicionar todos os arquivos/diretórios </h3>

git add .

<h3>Vincular repositório local com um repositório remoto<h3>
  
git remote add origin git@github.com:leocomelli/curso-git.git

https://github.com/cleitoninfo/Git-e-GitHub.git
