# sistema de cadastro

```
node app.js
```
# Dicas para GIT

```

git log

git log --online

git log -p

git log --author="user_name"

mostrar todos os log do projeto 
```
---------------------------------------------
```
git clone

clona todo o repositorio remoto para a sua maquina 

git clone -branch new_feature <repositorio>

para clonar de uma brach diferente
```

---------------------------------------------
```
git pull https://github.com/GiovaniTasso/sistema-de-cadastro.git \\url do repositorio

verificar mudanças entre repositolorio local e o remoto
```
---------------------------------------------
```
git status

verifica se a alguma alteração no repositorio local
```
---------------------------------------------
```
git commit -m "mensagem"

git commit index.html -m "mensagem" \\ para commitar um arquivo unico

commitar as mudanças do reposirorio local para o repositorio remoto
```
---------------------------------------------
```
git push 

depois de adicionar/commitar voce usa o push para mandar para repositorio remoto



git push origin <nome de outra branch que nao é a main>

caso voce queira da push em uma branch que não e a main voce precisa especificar

```
-----------------------------------------------
```
git restore --source "hash do comite" . // . é para todos, mas pode especificar qual arquivi

git restore --source "hash do comite" index.html

voltar para a verção do comite selecionado
```
-----------------------------------------------
```
git add <nome do arquivo> 

git add . // . para adicionar todos arquivos novos

o add é para adicionar novos arquivos no git

lembrar que depois de adicionar tem que se fazer o commit e depois o push
```
-------------------------------------------------
```
git checkout -b <nome da nova branch>


para criar uma nova branch

lembrar que ele ja muda altomaticamente para a nova branch
```
---------------------------------------------------
```
git switch <nome da branch>


para mudar para outra branch
```
---------------------------------------------------
```
git merge <nome da branch que voce quer juntar com a main>

merge serve para juntar as alterações de uma brach com a outra

mas antes voce precisa da um git swicth para a branch que voce quer juntar// por exemplo a main

e depois da um push origin main // caso queira juntar com a main


exemplo: quero juntar a branch desenvolvimento com a main

git switch main

git marge desenvolvimento

git push origin main
```
-----------------------------------------------------
