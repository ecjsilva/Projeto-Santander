# <u>***Repositório Git/GitHub***</u>



## <u>Criando um Repositório</u>



### *Passo 1: Criando repositório no GitHub*

##### É necessário criar um repositório no GitHub antes, para conseguimos enviar nossos arquivos de forma remota.  Para criar, basta ir no GitHub ir em "Novo Repositório" e cria-lo.

### ***Passo 2: Iniciando o Git no Git Bash***

##### Iniciar o Git no Git bash, é utilizado o comando "git init", utilizando esse comando é criando uma pasta no diretório selecionado chamada ".git".

### *Passo 3: Adicionando Arquivos/Pastas*

##### Adicionar arquivos ou pastas no git é possível cria-la no diretório onde foi iniciada o "git init" ou utilizando o comando "mkdir" para criar uma pasta ou "echo > (nome do arquivo)" para criar um arquivo. logo após é necessesario usar o comando "git add (nome do arquivo) ou (um * para adicionar tudo)"

### *Passo 4: Verificando o Status*

##### Verificar o Status no git, é de suma importância para que o git verifique se os arquivos estão prontos para ser enviados para o GitHub, para isso é utilizado o comando "git status" que faz a verificação dos arquivos e da sua aprovação pro envio.

### *Passo 5: Criando uma "capa"* 

##### É necessário criar uma "capa"(Nome do repositório) para enviar o seus dados para o GitHub, ela é criada pelo comando "git commit -m ("Nome do repositório")"

### *Passo 6: Encontrando Repositório no GitHub*

##### Para encontrar é necessário o comando que o GitHub apresenta quando o repositório é criado no site, pode ser encontrado em Code>SSH, com ele copiado digite o seguinte código "git remote add origin (código SSH)" 

### *Passo Final: Autenticando e Enviando o Projeto*

##### Autenticação é necessária para que se saiba quem criou ou alterou o arquivo, o comando para autentica e enviar o projeto para o GitHub é "git push -u origin master"