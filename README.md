# ETL com DummyJSON

Este projeto implementa um processo ETL (Extract, Transform, Load) utilizando dados da API **[DummyJSON](https://dummyjson.com/)** . Ele extrai dados de usuários e produtos, transforma-os para manter apenas colunas relevantes e os salva em arquivos CSV para análises futuras.

### 🚀 Funcionalidades

- **Extração** de dados da API DummyJSON

- **Transformação** dos dados para manter apenas colunas importantes

- **Carga** dos dados processados em arquivos CSV

- Estrutura organizada com armazenamento separado para arquivos brutos e processados

### 📁 Estrutura do Projeto
````
/etl-dummyjson
│── raw/            # Dados brutos extraídos da API
│── curated/        # Dados transformados em CSV
│── main.py         # Código principal
│── requirements.txt# Dependências do projeto
│── README.md       # Documentação do projeto
````
### 🛠️ Tecnologias Utilizadas

- **Python** -> (Manipulação de dados)

- **Requests** -> (Requisições HTTP para extrair dados da API)

- **Pandas** -> (Transformação e exportação dos dados para CSV)

- **OS** -> (Gerenciamento de diretórios para armazenar arquivos)

## 📦 Instalação

1. Clone este repositório:

```git clone https://github.com/seu-usuario/etl-dummyjson.git```

2. Entre no diretório do projeto:

```cd etl-dummyjson```

3. Instale as dependências:

```pip install -r requirements.txt```

## 🔄 Como Executar

Execute o script principal para iniciar o processo ETL:

```python main.py```

Os arquivos JSON serão armazenados na pasta ```raw/```, e os arquivos CSV transformados ficarão em ```curated/```.
