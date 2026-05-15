# Instalar as bibliotecas

mo terminal:
```bash
pip instal -r requirements.txt
```

# Inicializar o alembic
no terminal:
```bash
python -m alembic init migrations
```

# Editar o arquivo alembic init
sqlalchemy.url =

# Gerar a migration
no terminal:
``` bash
python -m alembic revision --autogenerate -m "Criar tabela usuarios"
```

# Aplicar a migration no banco
```bash
python -m alembic upgrade head
```