# Aplicação Web com Docker Compose

Este repositório contém um exemplo simples de servidor **Apache (httpd)** rodando dentro de um container Docker, configurado com **Docker Compose**.

---

## Estrutura do projeto

```
.
├── docker-compose.yml   # Configuração do Docker Compose
└── htdocs/              # Pasta com os arquivos do site
    └── index.html       # Página inicial
```

---

## Como executar o projeto

### 1. Pré-requisitos
- [Docker](https://docs.docker.com/get-docker/) instalado  
- [Docker Compose](https://docs.docker.com/compose/install/) instalado  

Verifique as versões instaladas:
```bash
docker -v
docker compose version
```

---

### 2. Subir o container
No diretório do projeto, execute:
```bash
docker compose up -d
```

---

### 3. Acessar a aplicação
Abra o navegador em:  
👉 [http://localhost:8080](http://localhost:8080)

Se tudo estiver certo, você verá a página `index.html` localizada em `htdocs/`.

---

### 4. Parar a aplicação
Para encerrar e remover os containers criados:
```bash
docker compose down
```

---


✍️ **Autor:** Sávio Tomaz de Brito da Silva  
📅 Projeto criado para estudos de **Docker + Apache + Docker Compose**