
## Criando e enviando arquivos para seu repositório no Github.

### Criando o repositório

- Digite o Site do Github, faça login com a sua conta e clique em New repository:
- Em seguida, digite o nome e descrição do repositório que você esta criando e clicar em Create repository:
- Logo em seguida aparecerá uma tela:
- O repositório foi criado, só que ainda está vazio.
- Temos que enviar o arquivo para o Github.

### Inicializando um repositório na sua máquina
  
- Abra o Git Bash e vá até a pasta onde está o seu projeto.
- Agora vamos transformar esta pasta em um repositório git, para isto, basta digitar (git init) e dar enter:
~~~
$ git init
~~~
- A Mensagem está informando que iniciou um repositório vazio nessa pasta. Como saberei que agora tenho um repositório nessa pasta?
- Simples você terá que fazer uma configuração, abra a pasta no file explorer e configurar ele para mostrar os arquivos ocultos, verá que tem uma pasta 
a mais chamada .git:
- O Git usa essa pasta pra controlar as alterações feitas no seu repositório.
- agora temos um repositório na sua máquina e um no Github...como sincronizar os dois?


###  Adicionando uma origin
    Vamos agora executar esse comando:
~~~
git remote add origin git@github.com:seu email/pastagit.git
~~~
- Basicamente o que estamos dizendo nessa linha de comando é:
"Git, esse meu repositório local se conectará com um remoto, o caminho dele(origin) é git@github: seu email/pastagit.git. 
 Estabeleça essa comunicação pra mim".

### Em breve continuarei!

