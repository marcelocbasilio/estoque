# Controle de Estoque

## Como rodar o projeto?

1. Clone o repositório.
```
git clone https://github.com/marcelocbasilio/estoque.git
```
2. Crie um virtualenv com Python 3.
```
cd estoque
Linux: python3 -m venv .venv
Windows: python -m venv .venv
```
3. Ative o virtualenv.
```
Linux: source .venv/bin/activate
Windows: 
```
4. Instale as dependências.
```
pip install -r requirements.txt
```
5. Gerar arquivo .env
```
python contrib/env_gen.py
```
6. Para esconder as variáveis de ambiente
> [python-decouple](https://github.com/henriquebastos/python-decouple) <br>
> [package-of-the-week-python-decouple](https://simpleisbetterthancomplex.com/2015/11/26/package-of-the-week-python-decouple.html)
```bash
pip install python-decouple
```
7. Gerar arquivo requirements.txt
```bash
pip freeze
pip freeze > requirements.txt
```
8. Rode as migrações.
```bash
python manage.py migrate
```

## Notas
### Atualizar pip
```
pip install --upgrade pip
```
### Instalar Django
```
pip install django
```
### Criar projeto Django
```
django-admin startproject projeto .
```
