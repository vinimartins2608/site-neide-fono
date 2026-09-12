# Landing Page — Neide Gonçalves (Fonoaudióloga)

Site institucional simples, em HTML/CSS/JS puro (sem frameworks, sem instalação, sem build).

## Estrutura da pasta

```
neide-landing/
├── index.html          → estrutura da página
├── css/
│   └── style.css       → todo o visual (cores, fontes, layout, animações)
├── js/
│   └── script.js       → efeito de fade-in ao rolar a página
├── img/
│   ├── hero-photo.png
│   ├── gallery-1.jpg
│   ├── gallery-2.jpg
│   └── gallery-3.jpg
└── README.md
```

## Como abrir no VS Code

1. Abra o VS Code
2. Arquivo → Abrir Pasta... → selecione a pasta `neide-landing`
3. Instale a extensão **Live Server** (opcional, mas recomendado) para pré-visualizar
4. Clique com botão direito em `index.html` → "Open with Live Server"

Não precisa rodar `npm install` nem nada parecido — é um site 100% estático.

## Como publicar (deixar online de graça)

### Opção 1 — Netlify (mais simples)
1. Acesse https://app.netlify.com/drop
2. Arraste a pasta inteira `neide-landing` para a página
3. Em segundos você recebe um link (ex: `https://nome-aleatorio.netlify.app`)
4. Cole esse link na bio do Instagram

### Opção 2 — Vercel
1. Crie uma conta em https://vercel.com
2. Instale a CLI: `npm i -g vercel`
3. Dentro da pasta do projeto, rode: `vercel`
4. Siga as instruções no terminal

### Opção 3 — GitHub Pages
1. Crie um repositório novo no GitHub e suba os arquivos desta pasta
2. Vá em Settings → Pages
3. Em "Source", selecione a branch `main` e a pasta `/root`
4. O GitHub gera um link tipo `https://seu-usuario.github.io/nome-do-repo`

## Editar textos ou número de WhatsApp

- Todos os textos estão em `index.html`
- O número de WhatsApp aparece em 3 lugares no `index.html`, sempre no formato:
  `https://wa.me/5592992142101?text=...`
  Para trocar o número, edite o `5592992142101` (55 = Brasil, 92 = DDD, resto é o número).
- Cores e fontes ficam em `css/style.css`, no topo do arquivo (bloco `:root`).
