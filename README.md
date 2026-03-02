# FinFlow Beta — Deploy Instructions

## Deploy no Vercel (3 passos)

### Opção A — Terminal
```bash
cd finflow-beta
npx vercel --prod
```
Na primeira vez vai pedir para logar. Depois é automático.

### Opção B — Arrastar e soltar (mais fácil)
1. Acesse vercel.com e faça login
2. Clique em "Add New Project"
3. Clique em "Deploy without Git"
4. Arraste a pasta `finflow-beta` inteira
5. Clique Deploy

## URL final
Após deploy, você terá uma URL tipo:
`https://finflow-beta-xxxx.vercel.app`

Essa é a URL para mandar para os amigos.

## Código de acesso
`testedomilhao`

## Como instalar como app no iPhone (para seus amigos)
1. Abrir o link no Safari (não Chrome)
2. Tocar no botão Compartilhar (□↑)
3. Rolar e tocar "Adicionar à Tela de Início"
4. Tocar "Adicionar"
5. Abrir pelo ícone na tela inicial ✅

## Arquivos
- `index.html` — Tela de senha (pública)
- `app.html`   — App real (protegido por sessão + código)
- `manifest.json` — Config PWA
- `sw.js`      — Service worker (offline)
- `icon-*.png` — Ícones
- `vercel.json` — Config Vercel
