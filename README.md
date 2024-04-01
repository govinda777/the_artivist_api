# the_artivist_api

Este projeto implementa uma API HTTP usando Lambda Functions na Vercel, escrita em Python e MongoDB.

## Objetivo

Salvar e listar os dados dos usuários (Artist / ONG / Activist Consumer)

## Pré-requisitos

Antes de começar, garanta que você tenha:

- Python 3.9+
- [Pipenv](https://pipenv.pypa.io/en/latest/)
- [Vercel CLI](https://vercel.com/download)
- Uma conta na [Vercel](https://vercel.com)
- [Git](https://git-scm.com/)

## Configuração Local

Para configurar este projeto localmente, siga os passos abaixo:

1. **Clone o Repositório**

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. **Instale as Dependências**

   ```bash
   pipenv install
   ```

3. **Ative o Ambiente Virtual**

   ```bash
   pipenv shell
   ```

4. **Desenvolvimento Local**

   Para rodar o projeto localmente, você pode usar o seguinte comando:

   ```bash
   vercel dev
   ```

## Deploy

Para fazer deploy na Vercel, execute:

```bash
vercel --prod
```

## Estrutura do Projeto

- `/api`: Contém os arquivos de função Lambda em Python.
- `Pipfile` e `Pipfile.lock`: Listam as dependências do projeto.

## Contribuindo

Instruções para contribuir para o projeto. Por exemplo:

Se você deseja contribuir para o projeto, sinta-se à vontade para fazer um fork, criar um branch com suas funcionalidades ou correções e enviar um pull request.

## Contato

Seu Nome – [@SeuTwitter](https://twitter.com/seutwitter) - email@example.com

Link do projeto: https://github.com/seu-usuario/seu-repositorio

## Comandos usados

pip install pipenv
pipenv --python 3.9
pipenv install flask