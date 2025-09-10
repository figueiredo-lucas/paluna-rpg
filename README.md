# Paluna RPG

Sistema de documentação para o [Paluna RPG](https://figueiredo-lucas.github.io/paluna-rpg).

## Instalação

### Dependências

* [Python](https://www.python.org/downloads/)
* [MkDocs](https://www.mkdocs.org/user-guide/installation/) - Base da documentação. Também explica como fazer a instalação do Python.
* [Material MkDocs](https://squidfunk.github.io/mkdocs-material/getting-started/) - Estilo visual da documentação.

### Detalhes

Instale as dependências e clone o projeto para a pasta desejada. Navegue para a pasta do projeto e execute o comando:

```sh
mkdocs serve
```

Dessa forma você poderá ver a documentação sendo executada a partir da sua pasta na url [http://127.0.0.1:8000/paluna-rpg](http://127.0.0.1:8000/paluna-rpg).

## Atualizando a documentação

Dentro da pasta `docs/` é possível adicionar várias subpastas, definir todos os detalhes da documentação e escrever os arquivos em formato Markdown.

Para atualizar quaisquer alterações para o projeto principal basta fazer um commit com tudo que foi alterado na branch `main`. Existe um *workflow* do github que vai pegar essa atualização e gerar o gh-pages acessível no link do início desse arquivo.

### Comandos úteis para git

* `git clone git@github.com:figueiredo-lucas/paluna-rpg.git` - Usado para trazer o projeto para sua máquina
* `git add .` - Adiciona todos os arquivos que foram alterado para área de **stage**.
* `git commit -m "<mensagem>"` - Pega todos os arquivos na área de **stage** e adiciona ao **versionamento local**.
* `git push origin main` - Atualiza o versionamento remoto com os dados locais que já foram versionados.
* `git pull origin main` - Atualiza o versionamento local com os dados remotos que foram versionados.

> Idealmente, sempre que for iniciar uma nova adição na documentação, execute o comando `git pull origin main`, para garantir que quaisquer atualizações feitas por outras pessoas também atualizem o seu versionamento local.
