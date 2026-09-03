# AutoVans — Landing Page

Landing page institucional da **AutoVans Locação e Transportes** (Belo Horizonte/MG).

Referência em transporte executivo desde 2000, atendendo BH, região metropolitana e viagens nacionais.

## 🌐 Stack

- HTML5 / CSS3 / Vanilla JavaScript (sem frameworks)
- Hospedagem: **Netlify** (CDN global + HTTPS automático)
- Domínio: `autovanstransportes.com.br` (Registro.br)

## 📁 Estrutura

```
/
├── index.html              # Landing page principal
├── redirecionar.html       # Página intermediária de redirecionamento (3s) → WhatsApp
├── _redirects              # Regras de redirecionamento 301 (site legado .asp)
├── /assets                 # Imagens (.jpg, .webp, .avif, .png)
└── .gitignore
```

## 🚀 Deploy

**Automático via Netlify:**
1. Push na `main` da `agenciaadsbr/autovans-landing-page`
2. Netlify detecta, faz build e publica em produção (~30s)

**Para visualizar local:**
Não há build step. Basta servir a pasta com qualquer static server:
```bash
python3 -m http.server 8080
```

## 📞 Contato

- **Site:** https://autovanstransportes.com.br
- **WhatsApp:** (31) 9868-50382
- **E-mail:** autovanstransportes@gmail.com
- **Endereço:** Rua Bernardes de Carvalho, 39 — Santa Terezinha, Belo Horizonte/MG

---

© Autovans Locação, Transporte e Serviços — CNPJ 30.974.871/0001-77
