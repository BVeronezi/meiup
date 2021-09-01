# MEIUP

## :warning: Requerimentos

- [Node](https://nodejs.org/)
- [Docker](https://www.docker.com/products/docker-desktop)

## :package: Instalação

Clone este repositório com a opção **--recursive**

```bash
git clone --recursive https://github.com/BVeronezi/meiup
```

## :whale: Rodar com o Docker compose

Na pasta do projeto:

```bash
docker compose up
```

> O backend deverá abrir na porta **3000**

> O frontend deverá abrir na porta **8888**

## :robot: Deploy

Por meio do [Github Actions](https://github.com/features/actions) todos os **commits** e **Pull requests** feitos na _main_ iniciam o processo automático de deploy.

---

> Link do Heroku [Backend](https://meiup-api.herokuapp.com/swagger/)

> Link da Vercel [Frontend](https://meiup-frontend.herokuapp.com//)

---

## Atualizando a codebase

Para atualizar os submodules ao dar pull utilizar:

```bash
git pull --recurse-submodules
```
