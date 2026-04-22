# Frontend — Sistema Autoatendimento

## Páginas

- `tablet/index.html` — Totem de autoatendimento para o cliente
- `admin/index.html` — Painel administrativo

## Configurar URL do Backend

Antes de usar em produção, defina a URL do backend no HTML (ou via variável de ambiente no seu servidor).

**Opção 1 — Diretamente no HTML** (antes do `</body>`):
```html
<script>
  window.BACKEND_URL = 'https://seu-backend.railway.app';
</script>
```

**Opção 2 — Via Nginx / Apache** (injetar a variável no servidor).

## Deploy sugerido
Vercel, Netlify, GitHub Pages (arquivos estáticos)
