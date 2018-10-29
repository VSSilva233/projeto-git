# Siga os passos a seguir


## Crie uma conta no GitHub
- Acesse o link https://github.com/join?source=header-home para criar sua conta
- Ou efetue login https://github.com/login?return_to=%2Fjoin%3Fsource%3Dheader-home

## Crie um repositório 
- Clice no icone de mais no lado superior direito
- Clice em New Repository
- Coloque no campo de Repository name o nome de "apredendendo-git"
- Deixe a opção public selecionada e clique em Create Repository

## Instalando GitBash
- Efetue download https://gitforwindows.org/
- Faça a instalação(aperto prosseguir em tudo)

## Configurando o projeto local
- Para baixar o projeto, clique no botão verde, Clone or Download
- Copie o link na caixa de dialogo
- Vá para area de trabalho e clique com o botão direito no mouse
- Abra o GitBash
- Digite: git clone url-copiada-no-site

## Fazendo modificações no projeto
- Crie um arquivo chamado `index.html` e salve ele
- No terminal do gitbash digite `git status`
 
## Fazendo seu primeiro commit 
- Digite `git add .`
- Digite `git commit -m "meu primeiro commit"` 

## Fazendo seu primeiro push 
- Digite `git push orign master`

## Criando um branch 
- Para criar uma branch digite `git branch primeira-branch`
- Para ver as branches local(que não estão no repositório online), digite: `git branch `
- Para ver as branches online digite `git branch -a`
- Se quiser deletar uma branch vc pode executar o comado: `git branch -d nome-da-branch`

- Digite `git checkout primeira-branch` para realizar a troca da branch 
* As alterações que você realizar nessa branch não irão para a master até você realizar o merge

## Fazendo alterações na branch
- Realize qualquer alteração ou adição de arquivo

``` HTML
<!DOCTYPE html>
<html>
  <head>
    <title>Apredendo git</title>
    <meta charset="UTF-8">
  </head>
  
  <body>
    <h1>Olá mundo</h1>
    <p>.......................................</p>
  </body>
</html>
```
== Criar um repositório ==  
	- Crie com nome "aprendendo-git"

== Fazer download do git ==
	- link: https://gitforwindows.org/

== Configurando repositório ==
 	- Crie uma pasta chamada "apredendo-git"
 	- Clique com botão direito e abra com git-bash
 	- git remote add url
 	- git commit -m "meu primeiro commit"
 	- git push orign master 
== 