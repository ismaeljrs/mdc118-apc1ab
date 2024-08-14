Prática 1

1. Criação de Repositório no GitHub.

a) Abra uma aba do navegador e acesse o site do GitHub (https://github.com/).

b) Faça login na sua conta do GitHub clicando em Sign in. Se você ainda não possui uma conta, clique em Sign up e siga as instruções fornecidas para criar uma conta.

c) Após o login, clique no ícone + localizado no canto superior direito da página inicial do GitHub.

d) No menu suspenso, escolha a opção New repository.

e) Na página de criação de repositório, preencha o nome do repositório (ex.: apc1), escolha a visibilidade pública, selecione a opção Add a README file e selecione C em template .gitignore. 

f) Role para baixo e clique em Create repository.


2. Importação do Repositório do GitHub para o Replit.

a) Abra uma aba do navegador e acesse o site do Replit (https://replit.com/).

b) Faça login na sua conta do Replit clicando em Log in. Se você ainda não possui uma conta, clique em Sing up for free. Em ambas as situações, selecione Continue with GitHub para prosseguir.

c) Após o login, clique em + Create Repl para criar um novo projeto.

d) No painel Create a Repl clique em Import from GitHub.

e) Selecione o repositório que você criou anteriormente no GitHub.

f) Clique em Import from GitHub. Aguarde o processo de importação do repositório para o Replit.

g) Informe o comando gcc no campo Run command e clique em Confirm and close.


3. Configuração Inicial do Projeto no Replit.

a) Abra o arquivo .gitignore e acrescente no final as seguinte linhas.

# Replit
.breakpoints
.ccls-cache/
.replit

b) Abra o arquivo README.md e altere o conteúdo com as seguintes linhas.

# Algoritmos e Programação de Computadores I

Repositório criado para as aulas teóricas e atividades práticas da discipina de Algoritmos e Programação de Computadores I.

## Organização do Repositório

Este repositório está organizado da seguinte forma:
- **aulas/**: Pasta que contém os códigos das aulas teóricas.
- **praticas/**: Pasta que contém os códigos das atividades práticas.

## Comandos Básicos do Shell no Linux

Aqui estão alguns comandos básicos do shell no Linux que podem ser úteis ao utilizar o Replit.

- Listagem de Arquivos e Pastas
```shell
ls      # Lista arquivos e pastas da pasta atual
ls -l   # Lista detalhadamente com informações adicionais
```
- Acesso a Pastas
```shell
cd nome_da_pasta    # Acessa a pasta especificada
cd ..               # Volta uma pasta (subir um nível)
cd ~                # Volta diretamente para a pasta home
```
- Executar um Programa Local
```shell
./nome_do_programa  # Executa um programa da pasta atual
```
- Limpar a Tela do Terminal
```shell
clear
```

## Instruções para Compilar um Programa C

1. Acesse a Pasta com os Códigos
```shell
cd aulas
cd aula01
```
2. Compile o Programa
```shell
gcc nome_do_arquivo.c -lm
```
3. Execute o Programa Compilado
```shell
./a.out
```
