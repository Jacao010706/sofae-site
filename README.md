# Site do Sofae (sofae.com.br)

Site estático (HTML/CSS/JS, sem build). Publicado na Vercel.

- `index.html` — sofae.com.br. **Sem pagamento nem link para pagamento**: o domínio está nas fichas da Google Play e da Amazon.
- `ativar.html` — ativar.sofae.com.br (reescrita por host no `vercel.json`). MAC → páginas de PIX (`/app`) e de listas (`/dispositivo`) do painel, com `&r=sofae`.
- `vercel.json` — mantém `/privacidade`, `/privacidade/android`, `/excluir-dados` e `/sofae/*` servidos pelo painel (links das fichas das lojas).
- Links de download e contato: objeto `CONFIG` no fim do `index.html`.
