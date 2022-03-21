<div style="display:flex; align-items:center; justify-content: center; flex-direction: column; ">
    <h1> 👩‍💻 Checkpoint I 👨‍💻</h1>
    <h6>INTRODUÇÃO A INFORMÁTICA I</h6>
    <h3> ✌️ Bem vindo! </h3>

</div>
<br><br>


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
<!-- ->
Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

Consulte **Implantação** para saber como implantar o projeto.

### 📋 Pré-requisitos

De que coisas você precisa para instalar o software e como instalá-lo?

```
Dar exemplos
```

### 🔧 Instalação

Uma série de exemplos passo-a-passo que informam o que você deve executar para ter um ambiente de desenvolvimento em execução.

Diga como essa etapa será:

```
Dar exemplos
```

E repita:

```
Até finalizar
```

Termine com um exemplo de como obter dados do sistema ou como usá-los para uma pequena demonstração.

## ⚙️ Executando os testes

Explicar como executar os testes automatizados para este sistema.

### 🔩 Analise os testes de ponta a ponta

Explique que eles verificam esses testes e porquê.

```
Dar exemplos
```

### ⌨️ E testes de estilo de codificação

Explique que eles verificam esses testes e porquê.

```
Dar exemplos
```

## 📦 Desenvolvimento

Adicione notas adicionais sobre como implantar isso em um sistema ativo

## 🛠️ Construído com

Mencione as ferramentas que você usou para criar seu projeto

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - O framework web usado
* [Maven](https://maven.apache.org/) - Gerente de Dependência
* [ROME](https://rometools.github.io/rome/) - Usada para gerar RSS

## 🖇️ Colaborando

Por favor, leia o [COLABORACAO.md](https://gist.github.com/usuario/linkParaInfoSobreContribuicoes) para obter detalhes sobre o nosso código de conduta e o processo para nos enviar pedidos de solicitação.

## 📌 Versão

Nós usamos [SemVer](http://semver.org/) para controle de versão. Para as versões disponíveis, observe as [tags neste repositório](https://github.com/suas/tags/do/projeto). 

## ✒️ Autores

Mencione todos aqueles que ajudaram a levantar o projeto desde o seu início

* **Um desenvolvedor** - *Trabalho Inicial* - [umdesenvolvedor](https://github.com/linkParaPerfil)
* **Fulano De Tal** - *Documentação* - [fulanodetal](https://github.com/linkParaPerfil)

Você também pode ver a lista de todos os [colaboradores](https://github.com/usuario/projeto/colaboradores) que participaram deste projeto.

## 📄 Licença

Este projeto está sob a licença (sua licença) - veja o arquivo [LICENSE.md](https://github.com/usuario/projeto/licenca) para detalhes.

## 🎁 Expressões de gratidão

* Conte a outras pessoas sobre este projeto 📢
* Convide alguém da equipe para uma cerveja 🍺 
* Obrigado publicamente 🤓.
* etc.


---
⌨️ com ❤️ por [Armstrong Lohãns](https://gist.github.com/lohhans) 😊