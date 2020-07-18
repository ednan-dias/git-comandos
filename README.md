
![git-comandos](https://user-images.githubusercontent.com/62631162/87855084-5c06ad80-c8ec-11ea-8deb-b6f51e8bb29a.jpg)


## Inicializar repositório local e conectar ao repositório remoto:

* **Inicializar repositório local:** `git init` <br>

* **Conectar ao repositório remoto (GitHub):** `git remote add origin (Url do repositório)` <br>

* **(Primeiro Push) Colocar arquivos no repositório remoto:** `git push -u origin master` depois de realizar o primeiro push, pode usar apenas `git push` <br>

***

## Adicionando arquivos e realizando commits

* **Adicionar arquivo ao repositório local:** `git add (Nome do arquivo)` <br>

* **Adicionar todos os arquivos na pasta ao repositório local:** `git add .` <br>

* **Adicionar commit (pontos na história):** `git commit -m "Sua mensagem aqui"` <br>

* **Adicionar arquivo ao repositório local e commitar ao mesmo tempo:** `git commit -am "Sua mensagem aqui"` <br>

***

## Git Log, Status, Show

* **Ver informações sobre seu projeto (Como por exemplo a Branch que você está e avisos sobre aquivos modificados ou excluídos):** `git status` <br>

* **Ver pontos da história (commits):** `git log` <br>

* **Ver ultímo ponto da história (commit):** `git show` <br>

* **Ver ponto da história específico:** `git show (Código do commit)` <br>

***

## Branchs

* **Criar uma branch (Para que você possa criar novas funcionalidades no seu projeto, sem desmanchar as alterações da branch master:** `git branch (Nome da branch)` <br>

* **Mudar de branch:** `git checkout (Nome da branch)` <br>

* **Criar branch e já mudar pra ela:** `git checkout -b (Nome da branch)` <br>

* **Ver todas as branchs:** `git branch` <br>

* **Unir pontos da história de outras branchs para a branch master:** `git merge (Nome da branch)` <br>

* **Excluir branch:** `git branch -d (Nome da branch)` <br>

***

## Repositórios

* **Ver repositórios:** `git remote -v` <br>

* **Clonar repositório:** `git clone (Url do repositório)` <br>

* **Puxar alterações do repositório remoto para o seu repositório local:** `git pull` <br>

***

## Recuperar arquivos

* **Recuperar arquivo deletado que você não criou ponto na história:** `git checkout -- (Nome do arquivo)` <br>

* **Recuperar arquivo deletado que tenha algum ponto na história:** `git checkout (Código do commit) -- (Nome do arquivo)` <br>

## Transferir alterações na stage de uma branch para outra
* **Retirar alterações do branch atual** `git stash sabe (nome descritivo)` <BR>
* **Mudar de branch:** `git checkout (Nome da branch)` <br>
* **Colocar alterações no branch atual:** `git stash pop` <br>
*Por Ednan Dias, em 15/06/2020*
