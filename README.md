# FastApi Project

O projeto "Nome do Projeto" é uma aplicação desenvolvida utilizando o framework FastAPI em Python. Ele fornece uma estrutura sólida e eficiente para construir APIs RESTful de alto desempenho. 

A estrutura modular do projeto permite que você desenvolva APIs escaláveis e de fácil manutenção. Ele também é altamente personalizável, permitindo que você adicione facilmente novos recursos e extensões para atender às necessidades específicas do seu projeto.

A estrutura do projeto foi desenvolvida com base em referências sólidas e escaláveis encontradas no seguinte repositório: https://github.com/zhanymkanov/fastapi-best-practices#1-project-structure-consistent--predictable.

## Pré-requisitos

- Python 3.7 ou superior
- [pip](https://pip.pypa.io/en/stable/) para instalar as dependências

## Instalação

1. Clone este repositório:

git clone https://github.com/seu-usuario/nome-do-repositorio.git

2. Acesse o diretório do projeto:

cd nome-do-repositorio

3. Crie e ative um ambiente virtual (opcional, mas recomendado):

python3 -m venv env
source env/bin/activate

4. Instale as dependências:

pip3 install -r requirements.txt

## Configuração

1. Renomeie o arquivo `.env.example` para `.env`.

2. Edite o arquivo `.env` e configure as variáveis de ambiente necessárias.

## Uso

Execute o seguinte comando para iniciar o servidor de desenvolvimento:

uvicorn app.main:app --reload

Acesse o aplicativo em [http://localhost:8000](http://localhost:8000).

## Testes

Execute o seguinte comando para executar os testes automatizados:

pytest

## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).