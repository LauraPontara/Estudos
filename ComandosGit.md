# Estudo de Git e Github

### Comandos no terminal:

1.  `git init` => Inicia um novo projeto com git na máquina
2.  `git add .`  => Adiciona os arquivos que estão prontos para serem comitados
3.  `git add (nome do arquivo)` => Adiciona o arquivo indicado para ser comitado
4.  `git commit -m "menssagem"` => Comita os arquivos no histórico ( Adicionar -m para fazer comentário)
5.  `git status` => Mostra como está o estado da nossa ramificação, se há alterações para serem comitadas, se há alterações preparadas para o commit mas que ainda não aconteceu...
6.  `git log` => Mostra os últimos commits, log de alterações
7.  `git diff` => Mostra o que foi alterado desde o último commit/DIFERENÇAS antes e após modificações feitas, se algo foi adicionado ou foi removido (Não mostra nada se todos os commits já tiverem sido feitos)
8.  `git merge (nome da branch)` => Mescla as modificações das ramificações
   
    ```
    OBS:
    É preciso estar na branch MASTER para puxar as alterações da outra branch e assim fazer a mesclagem.

9. `git branch` => Mostra em qual branch você está
10. `git branch -b (nome da nova branch)` => Cria uma nova branch A PARTIR DO HISTÓRICO DA BRANCH ATUAL QUE ESTAMOS
11. `git checkout (nome da branch)` => Muda a linha de trabalho da branch atual que você está para a branch indicada
12. `git remote add (nome) <url do repositório>` => Víncula um novo repositório remoto como o GitHub
13. `git remote -v` => Mostra o link do repositório o qual está associado, para onde irão as alterações se der commit (-v de verbose)
14. `git remote remove <nome do repositório ou origin>` => Remove o repositório vinculado ao projeto (add um novo repositório para dar commit)
15. `git push (nome do repositório ou origin) (nome da branch)` => Empurra as alterações LOCAIS que fizemos na branch indicada para o repositório remoto
16. `git pull (nome do repositório ou origin) (nome da branch)` => Puxa para a branch indicada as alterações adicionadas ao repositório que ainda não possuimos para a nossa máquina
17. `git fetch` => Atualiza o novo histórico local com o histórico salvo no repositório remoto (atualiza novas branchs que podem ter sido criadas)
18. `git clone <link do repositório>` => Clona um repositório remoto na nossa máquina o locando em uma pasta nova
19. `git clone <link do repositório> .` => O ponto faz com que ele não crie uma nova pasta para colocar o clone do repositório.

## Vídeos assistidos: 

* [APRENDA GIT e GITHUB DO ZERO - guia completo](https://youtu.be/pyM5QLS2h6M?si=AYWvyLk424Me84ZC)  - Fernanda Kipper | Dev
(40 min)

