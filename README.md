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
python contrib/env_gen.py
```
5. Rode as migrações.
```
python manage.py migrate
```