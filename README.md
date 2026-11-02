# 4 Fearless & Free

Landing page estática (HTML + CSS, sem build). A Vercel publica-a diretamente.

## Estrutura
- `index.html` – a página
- `favicon.svg` – ícone do separador
- `images/` – fotografias (ver `images/LEIA-ME.txt`)

## Publicar
1. Substitui os ficheiros do repositório GitHub ligado à Vercel por estes.
2. Faz commit e push – a Vercel faz o deploy automaticamente.
3. Na Vercel, em Settings → Build & Development: Framework Preset = **Other**, sem Build Command, Output Directory vazio (raiz).

## Ativar o botão do guia (Payhip)
No fim do `index.html`, preenche: `var PAYHIP_URL='https://payhip.com/b/XXXX';`
