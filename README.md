# API de Livros com Python e Flask

## 1. Objetivo
Desenvolver uma API simples para disponibilizar informações de três livros em formato JSON.

## 2. Tecnologias utilizadas
- Python
- Flask

## 3. Estrutura do projeto
- `app.py`: código principal da API.
- `requirements.txt`: dependências do projeto.
- `README.md`: documentação.

## 4. Instalação

Crie o ambiente virtual:

```bash
python -m venv venv
```

Ative o ambiente virtual no Windows:

```bash
venv\Scripts\activate
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

## 5. Execução

Execute o comando:

```bash
python app.py
```

## 6. Rota disponível

- Método: GET
- Endereço: http://127.0.0.1:5000/livros

## 7. Dados disponibilizados

A API retorna três livros contendo:
- id
- titulo
- autor
- ano

## 8. Resultado esperado

Retorno dos três livros em formato JSON.
