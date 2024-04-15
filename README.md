# pratica-git
Repositório para prática de comandos do Git. 

~~~bash
git config --global core.editor "code --wait"
~~~

O comando acima define o VS Code como o editor padrão das mensagens de commit.

~~~bash
git commit --allow-empty
~~~

O parâmetro `--allow-empty` permite a criação de um commit vazio, para fins de prática e estudo de Git.

~~~bash
git commit -a 
~~~
O parâmetro `-a` adiciona todos os arquivos modificados ou não ignorados ao commit atual. <!-- não adiciona arquivos novos sem alteração e não rastreados -->

~~~bash
git checkout -b novoBranch
git switch -c novoBranch
~~~
O parâmetro `-b` alterna para `novoBranch` criando o branch. O mesmo acontece com o comando `git switch` com o parâmetro `-c`.  
