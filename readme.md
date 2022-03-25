<div align="center">
    <h1> 👩‍💻 Checkpoint I 👨‍💻</h1>
    <h6>INTRODUÇÃO A INFORMÁTICA I</h6>
    <h3> ✌️ Bem vindo! </h3>
</div>
<br>

---
<div  align="center">
<nav> <a href="#desafio">Desafio</a> | <a href="#apresentacao">Apresentação</a> | <a href="#brinds">Ebook e infográfico </a> | <a href="#integrantes">Integrantes</a></nav>
</div>

---

<br>
<h2> ✨ Objetivo</h2>
<p>
Nosso objetivo aqui é te apresentar o GIT, o que é, para que serve e como integrá-lo ao Github.
</p>
<p>
Aqui você terá o prazer de ter um <b>passo a passo</b> bem <i>rápido e básico</i> de como utilizar essa ferramenta incrível.
</p>

<p>
Além de ter seu mapinha pro seu <b>sucesso</b>, vai conhecer também um pouquinho da sua <b>história</b> e qual foi a <b> motivação!</b>

<h3> 👀  Maior trabalhão</h3>
<p>
Todos já tivemos que fazer trabalhos de escola, faculdade, empresariais ou pessoais. E antes do surgimento de plataformas Cloud (como o Google Drive), tínhamos o costume de fazer assim:
</p>

~~~
├─ Curriculo
   ├── curriculo_versao1.doc
   ├── curriculo_versao2.doc
   └── curriculo_versao_atualizado.doc
   ├── curriculo_esse_ta_bom.doc
   └── curriculo_versao_top.doc
~~~

<p>
    <b>E como eram os trabalhos em grupo?</b>
</p>
    <ul>
        <li> Vários arquivos separados em um e-mail;
        <li> Todo cuidado para não escrever onde seu colega está escrevendo;
        <li>E, depois de tudo isso, alguém sozinho pegava o trabalho e formatava do jeito que tinha que ser
    </ul>


<p>
    Várias e várias versões de um mesmo arquivo. Era tanto <b>CTRL+C / CTRL+V</b> de um único arquivo que gerava confusão e 'armazenamento indevido'.
</p>

<p>
    <b>Por que guardamos versões dos nossos trabalhos? </b>
</p>
    <ul>
        <li>  Para não perder ideias antigas
        <li>  Para poder voltar atrás em alguma decisão
        <li>  Acompanhar a evolução que estamos fazendo
    </ul>



<br><br>
<p>Então veio a...</p>
<h2> 🧠 Motivação: O GIT </h2>
 <p style="margin-left: 25px">
 <b>O que é?</b>

 🌱 O git é uma ferramenta que permite fazermos o
gerenciamento de versão de nossos projetos (de
programação ou não).
</p>

<p style="margin-left: 25px">
 <b>O que faz?</b>

👥 Facilita o trabalho colaborativo.
</p>

<p style="margin-left: 25px">
 <b>Porque faz?</b>

🎟️ É muito fácil manter o track (rastreamento) de
arquivos que são alterados por duas pessoas ao
mesmo tempo
</p>

<br>
<br>

<h2> 🤓 Um pouco da história do GIT</h2>

<p>
Este problema de versionamento é algo que já preocupava a comunidade científica (em especial,
desenvolvedora(e)s) há bastante tempo. Um dos primeiros sistemas a surgir foi o <b>bitkeeper</b>.
</p>
<p>
Mas o bitkeeper não era bom, e isso ficou evidente quando um dev começou a fazer um dos projetos
open-source mais famosos da história...
</p>

<p>
Em 1991, Linus Torvalds começou a elaborar o sistema operacional Linux. A princípio, ele só queria testar seus conhecimentos
de programação e criar o seu próprio sistema operacional. Segundo Linus, seria "algo simples":
</p>
<br>
<cite style="position:relative; right:0;">
Estou fazendo um sistema operacional (livre - apenas
como um hobby, não será algo grande e profissional
como o GNU) [...]
<br>
</cite> <span style="font-size: 12px">Mensagem enviada por Linus para divulgar seu projeto.</span>

<br>
<p>
O resultado é que o Linux se tornou o SO mais usado por desenvolvedora(e)s no mundo.  Com o tempo, o projeto foi crescendo e se tornando
cada vez mais importante.
 Por ser um projeto <b>open-source</b>, qualquer pessoa poderia <b>contribuir</b> escrevendo código ou sugerindo
funcionalidades e melhorias
</p>

<p>
O bitkeeper começou a não ser mais o suficiente: ele era bastante lento e passou a ser pago.
</p>

<p>
Com isso, Linus e sua equipe decidiram criar o próprio version control software (VCS - software de controle de versão). Surge daí o "git", o software de controle de versão que
nenhum(a) dev imagina viver sem...
</p>

<h4> Mas peraí, Github não é a mesma coisa?</h4>

<p>
Éééééé.... <b>NÃO! </b>
</p>

<h3> Git vs. Github </h3>

<p>

- O git é a ferramenta que facilita o gerenciamento e colaboratividade dos projetos. 

- O Github é um serviço cloud que permite armazenar os projetos.
</p>

<p>
 O projeto que está na nossa máquina chamados de <b>repo(sitório) do git local</b>. 
 
 O projeto que está no github, chamados de
<b>repo(sitório) do git remoto</b>.


<br><br>

<h2> 🚀 Começando </h2>

<h3> 🛠️ Instalação </h3>

<p> 
<b> É importante saber que para começar a ciar um versionamento do nosso código/trabalho é necessário que a ferramenta esteja instalada!</b>
</p>

<p>
Então, caso não ainda não tenha instalado <a href="https://git-scm.com/downloads"> clique aqui </a> e faça o download no site oficial, de acordo com seu sistema operacional.


Vale ressltar que, é comum que os sistemas Linux e MacOS já venham com o git instalado, mas para desencardo é bom ter uma confirmação, e para isso abra o terminal e digite:
~~~
git --version
~~~
E se o retorno da mensagem for a versão do git, Ok! está instalado, se não aparecer nada ou der alguma mensagem fora do comum, instale o git.
</p>
<br>
<h3>⚙️ git config </h3>

<p> Vamos inserir nossas credenciais para que fique armazenado quem e quando foi feita as alterações do projeto.</p>
<p>Abra o terminal e siga os passos: 


1. Configurando o nome do usuário - escreva seu nome entre aspas - o seu nome mesmo.

~~~
git config --global user.name "digite-seu-nome-aqui-entre-aspas"
~~~

2. Configurando o e-mail do usuário - aqui é importante que escreva o seu e-mail de acordo com o que irá utilizar em um sistema de gerenciamento. (tipo github)

~~~
git config --global user.email "meu@email.com"
~~~

3. DICA MASSINHA. Habilitando a colorização da saída da linha de comando - esse passo é dispensável.

~~~
git config --global color.ui auto
~~~
</p>

<br>
<h3>🧬  git init </h3>

<p> Começamos criando um repositório local. Lembrando, abra seu terminal.

Siga os passos a seguir:

1. Inicializa o git na pasta atual:

~~~
git init
~~~

2. Cria e inicializa o git em uma nova pasta, e armazena na sua pasta atual:

~~~javascript
git init novo_repositorio
~~~

3. Inicializa o git no endereço fornecido:

~~~javascript
git init area_de_trabalho/meus_documentos/novo_repositorio
~~~

<p> É importante ressaltar que, quando iniciamos o repositório (git init) não será criado um diretório (uma pasta), e sim um arquivo .git que fica oculto. Caso queira ver esse arquivo que fora criado, apenas selecione a opção para <i>vizualizar aquivos ocultos</i>.</p>


<p><b>Pronto! Temos o inicio de um versionamento de seu trabalho.</b></p>

<p> A partir de agora, qualquer adição/alteração de um arquivo é possível verificar com o comando

~~~javascript
git status

// Irá mostrar no terminal o status do repositório
~~~

- Arquivos/pastas criados

- Arquivos/pastas modificados

- Arquivos/pastas removidos

Caso, queira permanecer com as alterações, é preciso adicionar ao git, enviando os arquivos modificados, removidos e
criados para a Staging Area (que é local):

~~~javascript
// para adicionar apenas o arquivo modificado
git add nome-arquivo

// para adicionar todos os arquivos da pasta em questão
git add . 

// para adicionar todos os arquivos alterados no projeto
git add --all
~~~

Depois de add suas alteações, é preciso fazer um commit.

<br>
<h3> 📎  git commit </h3>

<b> Mas, o que é um commit?</b>

Serve para informar com uma mensagem a alteração que houve no projeto e quais os arquivos que serão adicionados na Staging Area.

A mensagem deve explicar as modificações, criações e deleções feitas.

Para dar um commit, depois de ter feito a adicção com o git add, digite no terminal:

~~~javascript
git commit -m "mensagem"

// Não esquecer do -m
// Caso esqueça, você vai entrar em uma parte do terminal, que para sair você deve digitar: esc esc -q
// Não esquecer das aspas (")
~~~

Caso queira verificar o histórico de commits que fez, digite o comando:

~~~javascript
git log

ou

git log -- graph
//Mostra de forma mais descritiva e visual o que está acontecendo.
~~~

<br>
continua...
<br>
<br>
<p><b>😅 Legal, conhecemos um poquinho do que é e pra que serve o git, agora vamos colocar a mão na massa! </b></p>



<p>
E ae pessoal, como vai? Bora fazer essa atividade?
</p>

<p>A ideia de se ter um README em um repositório é que aqui vocẽ vai explicar tudo de maneira simples e sucinta . Neste caso, tentarei deixar de maneira detalhada o passo a passo que vocês devem seguir para cada integrante entregar sua parte da atividade.
</p>
<hr><br>
<h2> 💻 Vamos ao que interessa: mão na massa, quer dizer, no código!</h2>
<br><br>
<h3 id="desafio">📑 Desafio</h3>

<p>
O desafio consiste em: 

- fazer o clone desse repositório; 

- criar sua branch e realizar suas alterações;

- essas alterações são: criar uma pasta, entrar na pasta e criar um arquivo Nome_Sobrenome.txt com qualquer conteúdo.

- em seguida, vir até esse arquivo e colocar o print do terminal com os comandos que cada integrante utilizou.

- fazer o commit e consequentemente, um push estando na sua branch;

- Ir até o github e fazer uma PR (pull request) e solicitar um reviewer.

- Próximo passo é deixar o dono do PR fazer o merge na Main.

</p>

---

~~~javascript
// Gravei um vídeo, e está na Twitch para acompanhar e ir fazendo junto caso tenha dúvidas
// Link na Twich: https://www.twitch.tv/videos/1421978671
// Link no Youtube: https://youtu.be/7CQzHB0oqYQ
// Qualquer dúvida, pode me chamar.
~~~

---
<h3>⌨️ Passo a passo via terminal 🖱️</h3>

Clone
~~~javascript
git clone git@github.com:gabazevdo/checkpoint_intro_informatica.git
//Basta copiar o código acima e clonar o 
//repositório na sua pasta de sua preferencia.
~~~

Acessar a pasta localmente:

~~~javascript
cd Git_GitHub_Checkpoint-1
//Após acessar a pasta, faça o comando: code .
//Esse comando vai abrir o VsCode nesta pasta em questão, 
//deixe ele minimizado e siga os próximos passos
~~~ 

Criar sua branch:
~~~javascript
git checkout -b "Nome_Sobrenome"
//Com esse comando vc irá criar a branch e já entrar direto
~~~

Criar sua pasta:
~~~javascript
mkdir Nome_Sobrenome
//Feito isso, irá acessar a pasta:
cd Nome_Sobrenome
~~~
<br><br><br><br>
 <b>Para o passo a seguir, <a href="https://github.com/gabazevdo/checkpoint_intro_informatica/blob/main/assets/readme.md"> clique aqui </a></b>
<br><br><br><br>
Criar um arquivo de texto, utilizaremos o markdown:
~~~javascript
touch README.md
//Abrir o arquivo e colocar informações gerais sobre o git/github
//Para realizar esse passo, vá até o VsCode e realize as alterações no arquivo que criou.

//LEMBRE-SE, A EXTENSÃO DO ARQUIVO SERÁ .md - EXTENSÃO APRA ARQUIVOS MARKDOWN
~~~

Veja o status 
~~~javascript
git status
//Provavelmente suas alterações aparecerão em destaque na cor VERMELHA
~~~

Adicione as alterações e deixe ele na espera (staging area)
~~~javascript
git add --all
//irá adicionar todas as suas alterações feitas no repositório
~~~

Veja o status 
~~~javascript
git status
//Provavelmente suas alterações aparecerão em destaque na cor VERDE
~~~

Faça o commit
~~~javascript
git commit -m "descreva o que foi realizado - seja breve"
~~~

Pronto, agora faça o push
~~~javascript
git push origin Sua_Branch
//Substituit o Sua_Branch pela branch que criou lá no passo 3 (git checkout -b "Nome_Sobrenome")
~~~

<h2>🧩 Passo a passo via GitHub</h2>

<p>

-  Fazer o PR (Pull Request).

-  Colocar um colega como Reviewer

- Aguardar para ter seu PR aprovado

- Fazer o Merge

- Partir pro abraço! Suas alterações foram aprovadas e integradas ao projeto principal! 🎉

</p>


---

<h2 id="apresentacao"> 👩‍🏫 Apresentação 👨‍🏫</h2>

<p>

Nosso grupo é composto por 8 integrantes, e foi feita a divisão da apresentação da seguinte maneira:

- O que é git e git hub, sobre a fundação e quanto vale a empresa hoje - Alicia

- Diferenciais Desemprenho - Hugo

- Segurança - Bruna

- Flexibilidade - Leonardo

- Modelo de  cobrança e usuários - Glaucia

- Curiosidades - Lucas

- Apresentação do respositorio - Gabriel  

- Disponibiliza o ebook - Douglas

</p>

<h3 id="brinds">📚 Disponibilizamos um ebook e uma apresentação para você leitor! </h3>
<a href="https://github.com/gabazevdo/checkpoint_intro_informatica/blob/main/assets/Ebook%20Git%20e%20Github.pdf">Clique aqui</a> e tenha seu exemplar totalmente grátis! (por tempo limitado 😆)

<p> Apresentação no Canva, para vizualizar,<a href="https://www.canva.com/design/DAE7haSjFOs/De0DKOMM-ryz6XqYkEj5AA/view?utm_content=DAE7haSjFOs&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink"> clique aqui</a>.


---

<h2 id="integrantes"> 👏 Integrantes do grupo </h2>

<div style="display:flex; flex-direction: column">

<a href="https://github.com/gabazevdo">
<img src="https://github.com/gabazevdo.png" height="50px" style="border-radius: 50px;">
Gabriel Azevedo
</a>

<a href="https://github.com/Leonardo-Jaen">
<img src="https://github.com/Leonardo-Jaen.png" height="50px" 
style="border-radius: 50px"> 
Leonardo Jean
</a>


<a href="https://github.com/AliciaOliveiras">
<img src="https://github.com/AliciaOliveiras.png" height="50px" style="border-radius: 50px"> 
Alicia Oliveira
</a>

<a href="https://github.com/cbrunacastro">
<img src="https://github.com/cbrunacastro.png" height="50px" style="border-radius: 50px">
Bruna Cavalcante
</a>

<a href="https://github.com/glauciaximenes">
<img src="https://github.com/glauciaximenes.png" height="50px" style="border-radius: 50px">
Glaucia Ximenes
</a>


<a href="https://github.com/douglasaraujoo">
<img src="https://github.com/douglasAraujoo.png" height="50px" style="border-radius: 50px">
Douglas Araujo
</a>

<a href="https://github.com/hugolcfn">
<img src="https://github.com/hugolcfn.png" height="50px" style="border-radius: 50px">
Hugo
</a>

<a href="https://github.com/Lucas5497">
<img src="https://github.com/Lucas5497.png" height="50px" style="border-radius: 50px">
Lucas Anselmo
</a>

</div>
