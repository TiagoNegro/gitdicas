# Repositório de comandos do git 👌
Repositório de uso pessoal, para lembrar alguns comandos utilizados no dia a dia com git.

## Instalação
Instalar o git na máquina atravês do site oficial do [git](https://git-scm.com/downloads).

## Inicialização de um novo repositório:
``` git
git init
```

## Configurações de usuário:
Adicionar o nome do usuário:
``` git
git config --global user.name "nome_do_usuario"
```

Adicionar o email do usuário:
``` git
git config --global user.email "seu@email.com"
```
Para buscar todas as informações:
``` git
git config --list
```
>Ou colocar a respectiva informação que busca, por exemplo:
>``` git
>git config user.name 
>git config user.email
>```

## Verificação do status dos arquivos:
Conforme há a modificação de arquivos, o git irá entender as modificações e mostrar os arquivos que ainda não houve um commit*.
> *Commit: No contexto de computação, realizar o commit é tornar efetivo um conjunto de alterações.

``` git
git status
```

## Realização de um commit
Para efetivar as mudanças de código utilizamos o seguinte:
1. Adicionamos os arquivos que foram modificados:
``` git
git add <file> // Para um único arquivo 
git add * // Para todos os arquivos 
```
2. Realizar feito o commit com a descrição do que foi feito:
```git
git commit -m "Descrição do que foi feito"
```
3. Enviar os commits de sua máquina local para o repositório:
``` git
git push origin [branch]
```