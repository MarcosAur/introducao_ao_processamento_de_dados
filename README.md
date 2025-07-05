## Arquivos necessários
- É necessária uma conexão com o Banco de dados Mysql. Este projeto assume que ao iniciar a execução o ambiente já esteja com essa conexão
- Microdados Enem 2023
    - [Link para download](https://download.inep.gov.br/microdados/microdados_enem_2023.zip)
    - Descompactar os arquivos e mover o arquivo MICRODADOS_ENEM_2023.csv para pasta data

- Variaveis de ambiente
    - Copiar o arquivo .env.exemplo e nomear de .env
    - Preencha com os dados de conexão do banco de dados

## Instalação do projeto
- Rodar os comandos para instalação das dependencias
    - `python3 -m venv .venv`
    - `.venv/bin/python3 -m pip install requirements.txt`

## Tecnologias e bibliotecas utilizadas
- Python3
- Mysql
- Pandas
- Matplotlib
- SqlAlchemist
