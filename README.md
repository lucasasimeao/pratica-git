# Prática de Git

> Repositório de treino dos primeiros comandos de Git e do uso de `.gitignore`.

## Sobre

Repositório criado para praticar o fluxo básico de versionamento (`init`, `add`, `commit`, `push`). Não contém um projeto funcional: o `index.html` está vazio.

## O que foi praticado

- Criação do repositório e primeiros commits
- Teste do `.gitignore` com uma pasta `node_modules/`

> Observação: o `.gitignore` está vazio, por isso o arquivo de teste em `node_modules/` acabou sendo versionado. Para ignorar a pasta, basta adicionar a linha `node_modules/` ao `.gitignore` e rodar `git rm -r --cached node_modules`.
