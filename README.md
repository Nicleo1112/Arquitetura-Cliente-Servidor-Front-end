# Livraria - Front-end (Exercício 8.3)

Este repositório contém o Front-end do sistema de livraria, construído com HTML e JavaScript puro.
O projeto implementa a Arquitetura Cliente-Servidor, consumindo a API Back-end via requisições HTTP.

> **Aviso:** Este é apenas o repositório do Front-end. O Back-end (API REST construída com Flask)
> está em um repositório separado e deve estar em execução para que o sistema funcione.

---

## Tecnologias Utilizadas

- **HTML5**
- **JavaScript (Fetch API):** Realiza as requisições HTTP para a API Back-end.
- **Bootstrap 5:** Estilização da interface via CDN.
- Não possui dependências instaláveis — nenhum `npm install` necessário.

---

## Como executar localmente

1. Clone o repositório:
```bash
git clone https://github.com/Nicleo1112/Arquitetura-Cliente-Servidor-Front.git
```

2. Abra o arquivo `index.html` direto no navegador — não precisa de servidor.

> Certifique-se de que o Back-end está rodando antes de abrir o front.

---

## Funcionalidades

- 🔍 **Filtrar livros** por título, autor e intervalo de ano
- ➕ **Adicionar novos livros** ao catálogo
- 🗑️ **Remover livros** do catálogo

---

## Conexão com o Back-end

A URL da API está definida no início do script em `index.html`:

```javascript
const API = 'https://livraria-api.azurewebsites.net/api/livros';
```

Para rodar localmente apontando para o back local, troque para:

```javascript
const API = 'http://127.0.0.1:5000/api/livros';
```

---

## Links

| | URL |
|---|---|
| 🌐 Front-end (GitHub Pages) | https://github.com/Nicleo1112/Arquitetura-Cliente-Servidor-Front |
| ⚙️ Back-end (Azure) | https://github.com/Nicleo1112/Arquitetura-Cliente-Servidor-Back-end |
