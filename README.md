# python_chat

```
chat/
|--app/
|   |--__init__.py
|   |--main.py # Inicializa o FastAPI e inclui as rotas
|   |--manager.py # Gerencia conexões webSockets
|   |--models.py #Estruturar os dados / Pydantic (modelo de dados)
|   |--database.py # conexão com MongoDB
|   |--config.py #dados de configurações
|   |--routes/
|   |   |--http.py # rotas HTTP (Ex: listar salas, listar usuarios)
|   |   |--websocket.py # endpoint websocket
|--requirements.txt # para instalar as dependências
|--run.py # para rodar a aplicação
```

Instale as dependências da aplicação:
```
pip install -r requirements.txt
```