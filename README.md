# Aprendendo Git

## Configurações iniciais

```shell
$ git config --global user.name "Jonata Weber"
$ git config --global user.email jonataa@gmail.com
```

## Inicializar um repositório

```shell
$ mkdir aprendendo-git # cria uma pasta
$ cd aprendendo-git/   # entra na pasta
$ git init             # cria um novo repositório
```

## git-status

```shell
$ git status # mostra o status do repositório
```

## Realizando um commit

```shell
$ git add README.md
$ git commit -m "mensagem do commit"
```

## Visualizando os logs

```shell
$ git log
$ git log --full-diff -p README.md
```

## Visualizando as diferenças

```shell
$ git diff README.md # Mostra a diferença desse arquivo para o último commit
```

## Descartando as mudanças

```shell
$ git checkout -- README.md # descarta as mudanças do arquivo no último commit
```

## Trabalhando com Branchs

```shell
$ git branch                          # lista todas as branchs
$ git checkout -b <branch-name>       # cria e troca para nova branch
$ git checkout <hash ou branch-name>  # troca de branch
```
