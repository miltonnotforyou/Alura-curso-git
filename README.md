# Alura-curso-git
Repositório para guardar arquivos curso da Alura
<br>

Um pouco do processo chamado de Git Flow:
Entendemos que o estado do código representado pela branch master deve ser o mesmo que estará em produção
Vimos que deve haver uma branch de desenvolvimento (comumente chamado de develop), onde todas as funcionalidades e correções devem ser muito bem testadas antes de ir para produção (master)
Vimos que cada funcionalidade deve ser feita em uma branch separada, e que é comum que esta branch tenha feature/ como prefixo
Aprendemos também que bugs normalmente são corrigidos em branches separadas, com o prefixo hotfix/
Além disso, branches específicas para cada release são criadas para realizar os testes e correções de bugs específicos

![20180412-git-flow](https://user-images.githubusercontent.com/67373586/207925763-15b172d2-d0d7-4ace-9d9c-221c86dd1bfb.png)

<br>
<br>
Neste curso de Git e GitHub, uma introdução a tudo que a ferramenta de controle de versões pode nos oferecer.

Para darmos uma recapitulada, primeiro entendemos o conceito de repositório, o qual inicializamos na pasta do nosso projeto utilizando git init. Depois, vimos que com git status conseguimos verificar as alterações já foram realizadas em nosso código, se existe algum arquivo para ser adicionado, ou commitado, algum arquivo que ainda não é trackeado ou monitorado, e assim por diante.

Caso haja alguma modificação a ser adicionada, o fazemos com git add. Então, vimos que precisamos gerar commits, que funcionam como sendo um ponto de alteração a ser salva. Conversamos um pouco sobre quando commitar, no entanto, o ponto principal é nunca commitar um código que não funciona.

Aprendemos a verificar nosso histórico de alterações e navegar por elas com git log --oneline, geramos tags, uma release que, ao fim, após termos entendido um pouco melhor e trabalhado com GitHub, gera um entregável, uma versão pronta para ser baixada. Vimos também como criar um repositório ao nos cadastrarmos no GitHub, e depois disso, como enviar os dados do nosso projeto local para ele.

Percebemos que com estes repositórios remotos, conseguimos trabalhar em conjunto com outras pessoas da nossa equipe. Além disto, vimos como criar um repositório remoto em nosso próprio computador, e com isto atualmente temos dois deles, identificados a partir do comando git remote -v, um denominado local, e outro, de origin.

Aprendemos que não é difícil trabalharmos com mais de um usuário em um mesmo projeto, resolvemos conflitos, trabalhamos com branches, e ainda há muito mais conceito por trás deles, com os quais não trabalhamos no decorrer deste curso, mas o mais importante neste primeiro momento é entender que branches são linhas de desenvolvimento distintas, e mais para a frente poderemos, em cursos futuros, trabalhar as estratégias de quais branches criar, como gerenciá-las, e por aí vai.

Vimos como navegar pelo histórico do nosso código, pelos commits, desfazendo alterações, salvando-as de forma temporária para depois as recuperarmos, com git stash, enfim, isso tudo em um único arquivo, o index.html, ou seja, nem focamos ou entramos em detalhes em relação ao código, justamente para focarmos em todo o poder que o Git tem a oferecer.
