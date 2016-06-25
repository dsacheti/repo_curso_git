#Repositório para o curso de Git

**Comandos usados até realizar o primeiro push após criar o repositório no [GitHub](https://github.com)**

1. Clonando o repositório para o meu computador:

 `git clone https://github.com/dsacheti/repo_curso_git.git`

2. Criando o arquivo README.md:
 
 `touch README.md`

3. Adicionando arquivos criados anteriormente:

 `add README.md`

 `add index.html`

4. Fazendo commit:

 `git commit -m"Primeiro commit`

5. Verificando status do branch master:

 `git status`

_Quando executei este comando me mostrou uma mensagem estranha:_

>"Your branch is based on 'origin/master', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)"
  
  _Então resolvi fazer o que me pediu._
  
  `git branch --unset--upstream`
  
  Verifiquei novamente o satus. Desta vez tudo ok.
  
6. Fazendo push: o primeiro eu errei o comando, depois fiz:

 `git push origin master`




