# Portfólio Thomas Alves dos Santos — Versão Estática

Esta versão não utiliza Flask, Gunicorn ou servidor Python.

## Estrutura

- `index.html`
- `static/css/style.css`
- `static/js/main.js`

## Publicar no Render como Static Site

1. Envie estes arquivos para o repositório GitHub `portfolio`.
2. No Render, crie um **Static Site**.
3. Conecte o repositório.
4. Branch: `main`
5. Build Command: deixe vazio.
6. Publish Directory: `.`
7. Clique em **Create Static Site**.

Como é um Static Site, ele não entra em suspensão após 15 minutos de inatividade.

## Atualizações

Depois de alterar os arquivos:

```bash
git add .
git commit -m "Atualiza portfólio"
git push
```

O Render fará um novo deploy automaticamente.
