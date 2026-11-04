# Casa Tica · Landing page

Página institucional da Casa Tica: história, salgados e contato. Sem formulário e sem preços; os pedidos vão pelo WhatsApp.

Site estático (HTML e CSS puros). Não tem build: o que está no repositório é o que vai para o ar.

## Estrutura

```
index.html        landing page
assets/
  css/styles.css
  img/            logo, favicon e imagem de compartilhamento (og-casatica.jpg)
```

## Contatos usados na página

| O quê | Valor | Onde trocar |
|---|---|---|
| WhatsApp de pedidos | (92) 99387-6006 | `index.html` (procure `5592993876006`) |
| Instagram | @casatica.oficial | `index.html` (procure `casatica.oficial`) |

## Publicar na Vercel

1. Em vercel.com: **Add New… → Project** e importe este repositório.
2. **Framework Preset:** Other. **Build Command** e **Output Directory:** em branco.
3. **Deploy.** Cada commit na branch principal publica de novo.

## Endereço

https://casatica-two.vercel.app/ (também em `index.html`: canonical, og:url e og:image)
