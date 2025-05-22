### 1. Setup da Aplicação

Este projeto permite rodar uma aplicação localmente utilizando Docker, com suporte para modelos de linguagem
personalizados.

## Passos para rodar a aplicação

#### 1. Clone este repositório

```bash 
    git clone https://github.com/smViana19/deepseekIntegracao.git
```

#### 2. Acesse a pasta do projeto

```bash
    cd local-deepseek
```

#### 3. Rode o projeto

```bash
    docker compose up -d
```

#### 4. Instale o modelo do deepseek

```bash
docker compose exec ollama ollama pull deepseek-r1:7b
```

#### 5. Rode na url 
```bash 
http://localhost:3000
```
