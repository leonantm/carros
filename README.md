# Projeto Carros
Este é um projeto desenvolvido como parte do curso **Django Master** realizado por **Pycodebr Treinamentos**.

O projeto é um catálogo de carros, tendo como funcionalidades um CRUD(CREATE, READ, UPDATE e DELETE) de usuários e de carros.

## Tecnologias utilizadas
* Linguagem de programação: Python, HTML, CSS
* Framework: Django
* Bando de dados: Postgresql

## Rodar o projeto
Criar o ambiente virtual
```bash
python -m venv venv
```
Ativar o ambiente virtual
```bash
source venv/bin/activate
```

Instalar dependências
```bash
pip install -r requirements.txt
```

Fazer migrate
```bash
python manage.py migrate
```

Rodar o servidor
```bash
python manage.py runserver
```
Após isso, o sistema estará pronto para ser acessado em:
[http://localhost:8000](http://localhost:8000)
