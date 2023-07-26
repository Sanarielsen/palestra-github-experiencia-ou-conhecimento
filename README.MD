# ORIENTAÇÃO OU EXPERIÊNCIA? O QUE É PRECISO PARA MELHORAR A SUA ORGANIZAÇÃO COM GIT E GITHUB.

Objetivo: Essa palestra possui um vies de ilustrar que o conhecimento teórico ou prático sobre determinado assunto, as vezes não é suficiente para realizar determinadas tarefas, por isso, é necessário mostrar exemplos que nem sempre as pessoas irão compreender uma instrução que inicialmente parece simples, mas possui N termos que podem deixá-la insegura ou a pessoa já fez aquele processo, mas não conhece ele naqueles termos que foram apresentadas a ela.

Comandos usados nessa palestra para organização do código:

git status <br/>
Para verificar quais as modificações desse contexto em relação ao commit atual, isso sendo: Adição, remoção ou atualização de arquivos. <br/>

git add <caminho> <br/>
Para adicionar as modificações encontradas em relação ao commit atual. <br/>

git commit <br/>
Esse comando irá abrir uma janela no seu editor padrão para construir a mensagem que será atrelada a esse commit. <br/>

git push origin <branch> <br/>
Esse comando irá subir as modificações que foram contabilizadas com o "add" para a origem setada da branch informada. <br/>

git cherry-pick <hash> <br/>
Esse comando irá pegar o conteúdo de um commit registrado para transferir para a branch que esse comando foi executado. <br/>
Obs: Se houver conflitos, tanto o editor de texto quanto a plataforma do github podem te ajudar nessa situação. <br/>

git checkout -b <nomeBranch> <br/>
Esse comando para criar uma nova branch, lembrando que irá considerar os commits que estão na branch atual. <br/>

git checkout <nomeBranch> <br/>
Esse comando altera a branch atual para a branch informada. <br/>

git branch <br/>
Esse comando lista as branchs que estão em seu ambiente local. <br/>

Para mais comandos ou um guia mais completo, acesse a postagem abaixo do leo para maiores informações: <br/>
https://gist.github.com/leocomelli/2545add34e4fec21ec16 <br/>

### Links de materiais citados
Guia para instalação e comandos utilizados no git: https://education.github.com/git-cheat-sheet-education.pdf