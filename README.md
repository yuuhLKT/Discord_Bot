# Bot Discord de Busca por Vagas de Desenvolvedor

Este bot do Discord foi criado com o objetivo de facilitar a busca por vagas de desenvolvedor no Brasil. Utilizando a API jSearch do RapidAPI, ele recupera vagas de diversos sites e as disponibiliza no chat do Discord.

## Funcionalidades

- Busca por vagas de desenvolvedor em todo o Brasil.
- Suporte para diversos sites de vagas.
- Filtro por palavras-chave.
- Interface amigável.

## Comandos

- `!jobs NOME_DA_VAGA`: Busca por vagas com o nome especificado.

## Requisitos

- Servidor Discord com o bot instalado.
- Conta RapidAPI para a API KEY.

## Instalação

1. Convide o seu bot para o seu servidor Discord;
2. Crie um arquivo `.env` na pasta do bot com as seguintes variáveis:
   - `API_KEY=SUA_CHAVE_DE_ACESSO`
   - `BOT_TOKEN=TOKEN_DO_SEU_BOT`
3. Inicie o bot com o comando `py -3 main.py`.

## Exemplo de Uso

- `!jobs Java Junior`
- `!jobs {STACK/LINGUAGEM} {TIPO(ESTÁGIO/JUNIOR/PLENO/SÊNIOR)}`

## Contribuições

Se deseja contribuir para o projeto, faça um fork do repositório e envie um [pull request](https://docs.github.com/pt/pull-requests).

## API

- [jSearch](https://rapidapi.com/letscrape-6bRBa3QguO5/api/jsearch)

## Licença

Este projeto está licenciado sob a [licença MIT](LICENSE).

