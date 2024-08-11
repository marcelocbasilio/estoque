# Controle de Estoque

> Atualizar pip
```
pip install --upgrade pip
```
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
6. Rode as migrações.
```
python manage.py migrate
```