# Site do Sofae (sofae.com.br)

Site estático (HTML/CSS/JS, sem build). Publicado na Vercel.

- `index.html` — sofae.com.br. **Sem pagamento nem link para pagamento**: o domínio está nas fichas da Google Play e da Amazon.
- `ativar.html` — ativar.sofae.com.br (redirecionamento por host no `vercel.json`: `/` → `/ativar`; rewrite não vale porque o `index.html` estático tem prioridade). MAC → `/app` (PIX) e `/dispositivo` (listas) com `&r=sofae`, no próprio ativar.sofae.com.br: o `vercel.json` repassa `/app`, `/dispositivo` e `/_next/*` ao painel **só nesse host** (no sofae.com.br não existe página de pagamento).
- `vercel.json` — mantém `/privacidade`, `/privacidade/android`, `/excluir-dados` e `/sofae/*` servidos pelo painel (links das fichas das lojas).
- Links de download e contato: objeto `CONFIG` no fim do `index.html`.
