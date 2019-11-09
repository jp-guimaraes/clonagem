# Revisão 

O **terminal** é uma ferramenta muito poderosa para a manutenção de computadores e sistemas.


Lista de comandos importantes:

Comando| Funcionalidade
:-----:|:-----:
`echo`| Exibe uma string na tela
`pwd`| Mostra qual o diretório atual
`ls`| Lista pastas e arquivos no diretório atual
`cd`| Ir para diretório tal
`cd ..`| Ir para diretório superior
`clear`| Limpa a tela
`cp`| Copia diretórios e arquivos
`mv`| Move diretórios e arquivos
`rm`| Deleta arquivos e diretórios
`mkdir`|Creates a new directory

## echo

O comando `echo` tem a função de exibir uma string no terminal. O contexto em que ele é mais utilizado é na criação de scripts para o bash, para exibir informação ao usuário.

O uso do comando é o seguinte:
```shell
echo o_texto_que_eu_quero_exibir

````
Veja:

![Bash cmd cd](https://github.com/jp-guimaraes/clonagem/blob/master/assets/terminal_gifs/cmd_echo.gif)

## pwd

O comando `pwd` tem a função de exibir qual o diretório atual. O uso do comando é o seguinte:
```shell
pwd
````
## ls

O comando `ls` exibe o conteúdo do diretório atual, mostrando arquivos e pastas. 

```shell
ls
```
Veja:

![Bash cmd ls](https://github.com/jp-guimaraes/clonagem/blob/master/assets/terminal_gifs/cmd_ls.gif)

Uma opção interessante a ser acrescentada ao comando é a opção -all, que inclui na exibição informações sobre permissões, datas de modificação e tamanho de arquivos. O uso é assim: `ls -all`.

## cd

O comando `cd` vai para o diretório passado como parâmetro. Veja:

```shell
cd nome_do_diretorio

````
Com esse comando, estou entrando no diretório nome_do_diretorio. Por exemplo, se eu quiser entrar no diretório cujo nome é `github`, o comando a ser executado seria: 
```shell
cd github

````
Veja:

![Bash cmd cd](https://github.com/jp-guimaraes/clonagem/blob/master/assets/terminal_gifs/cmd_cd.gif)


Se eu quisesse voltar ao diretório anterior basta usar o comando `cd ..`




O [terminalizer](https://github.com/faressoft/terminalizer) foi usado para criar os gifs desse Markdown.