# Calculadora API

API REST de calculadora desenvolvida com FastAPI e Python.

## Tecnologias utilizadas

- Python 3.11+
- FastAPI
- Uvicorn
- Pydantic

## Como executar

### 1. Clone o repositório
```bash
git clone https://github.com/Nicc181/calculadora-api.git
cd calculadora-api
```

### 2. Crie e ative o ambiente virtual
```bash
python -m venv venv

# Windows
venv\Scripts\activate

# Linux/macOS
source venv/bin/activate
```

### 3. Instale as dependências
```bash
pip install -r requirements.txt
```

### 4. Execute o servidor
```bash
uvicorn main:app --reload
```

### 5. Acesse a documentação

- Swagger UI: http://localhost:8000/docs
- ReDoc: http://localhost:8000/redoc

## Endpoints

| Método | Endpoint | Descrição |
|--------|----------|-----------|
| GET | / | Mensagem de boas-vindas |
| POST | /somar | Soma dois números |
| POST | /subtrair | Subtrai dois números |
| POST | /multiplicar | Multiplica dois números |
| POST | /dividir | Divide dois números |
| GET | /calcular | Operação via query parameters |

## Projeto Avaliativo

Projeto Avaliativo desenvolvido para disciplina Programação de Sistemas Distribuidos da Universidade do Grandes Lagos - UNILAGO sob supervisão do Professor Gleydes Oliveira https://github.com/gleydes