# Livraria - Front-end (Exercício 8.4)

Este repositório contém o Front-end do sistema de livraria, construído com HTML e JavaScript puro.
O projeto implementa a Arquitetura Cliente-Servidor, consumindo a API Back-end via requisições HTTP.

> **Aviso:** Este é apenas o repositório do Front-end. O Back-end (API REST construída com Flask)
> está em um repositório separado hospedado na Azure.

---

## Links

| | URL |
|---|---|
| 🌐 Front-end | https://nicleo1112.github.io/Arquitetura-Cliente-Servidor-Front-end |
| ⚙️ Back-end | https://livraria-api-btc4e6eucreuctae.eastus-01.azurewebsites.net |

---

## Tecnologias Utilizadas

- **HTML5**
- **JavaScript (Fetch API):** Realiza as requisições HTTP para a API Back-end.
- **Bootstrap 5:** Estilização da interface via CDN.
- Não possui dependências instaláveis — nenhum `npm install` necessário.

---

## Funcionalidades

- 🔍 **Filtrar livros** por título, autor e intervalo de ano
- ➕ **Adicionar novos livros** ao catálogo
- 🗑️ **Remover livros** do catálogo

---

## Como executar localmente

1. Clone o repositório:
```bash
git clone https://github.com/nicleo1112/Arquitetura-Cliente-Servidor-Front-end.git
```

2. Abra o arquivo `index.html` direto no navegador — não precisa de servidor.

> Para rodar localmente apontando para o back local, troque no `index.html`:
> ```javascript
> const API = 'http://127.0.0.1:5000/api/livros';
> ```

---

## Estrutura do Projeto

```
Arquitetura-Cliente-Servidor-Front-end/
├── index.html    # Aplicação completa — HTML, CSS e JS
├── .gitignore
└── README.md
```

---

## Deploy (GitHub Pages)

O front-end é hospedado via **GitHub Pages** e atualizado automaticamente a cada push na branch `main`.
