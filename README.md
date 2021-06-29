# Repositório teste github

## Continuando com as atividades e definindo uma rotina básica de trabalho

> __Como o repositório esta organizado__
> O arquivo __inicio.txt__ é um passo-a-passo de ações para aqueles que possuem o Git instaldo em suas máquinas
> No diretório __instale__ o arquivo __git_github_equipe_friends__ apresenta instruções básicas de como instalar o __Git__ em uma máquina local (poderá haver divergências no descritivo com a versão atual, mas os passos descritos no documento são a chave para que não tenha qualquer problema. Para o restante da instalção (passos que não estejam descritos no documento siga o default)
> Demais repositórios foram criados por colaboradores para testes, não se preocupem com eles. Criem os seus...

### Rotina sugerida para o time UFF

1. Faça o clone do repositório do github mfake0323 (este repositório reproduz as condições de operação do freindeslab).Neste repositório você poderá praticar sem problemas.
2. Gere as credenciais de trabalho – use git config user.name e git config user.email
3. Gere uma nova branch, sua branch de trabalho deverá ter um nome sugestivo, por exemplo, branch previsor, caso esteja trabalhando no módulo previsor e assim por diante.
3.1. Para criar um branch: git branch <nome_da_branch>
4. Você precisará ir para a branch criada, faça: git checkout <nome_da_branch>
5. Na nova branch, primeiro confira onde esta: __git branch__ o nome da nova branch deverá estar destacado com um _asterisco *_
6. Na nova branch trabalhe normalmente, altere crie, modifique, realize commits etc., enfim tudo o que aprendeu
7. Por fim, quando estiver convicto de que seu trabalho está ok, volte para a branch main: git checkout main
8. Na branch main verifique sua posição: __git branch__ você deverá estar na branch main, lembra do asterisco
9. Agora você deverá fazer o merge da branch que estava trabalhando com a branch master: git merge <nome_da_branch_que_criou>
10. Apague a branch de criada por você: git branch -d <nome_da_branch_que_criou>
11. Você agora deverá sincronizar com o repositório remoto: git pull origin main
12. Uma vez sincronizado é hora de você enviar toda sua produção para o repositório remoto: git push
13. A partir daí siga para seu próximo trabalho, sempre se lembrando de criar um nova branch para trabalhar
14. Controle seus commits, façam uso com prudência para não sobrecarregar o processo com commits desnecessários

#### Nota importante

> __O Git__ não foi idealizado para trabalhar com erros, logo ele não facilita muito quando algum erro for cometido, fique atento, caso algum erro ocorra, por exemplo numa mensagem de commit aprenda a conviver com isso e siga em frente, é uma jornda de aprendizado.
> __Atenção__, o que aqui foi mensionado são apenas diretivas básicas, como tudo em computação, sempre há possibilidades de se fazer diferente e corrigir muita coisa, aqui a preocupação é apenas com o tempo a ser gasto em soluções que para este projeto a princípio deve ser otimizado.
