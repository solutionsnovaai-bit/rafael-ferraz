# Rafael Ferraz — Embracon Anália Franco

Site estático (HTML + CSS + JS puro). Sem build, sem dependência.

## Estrutura

```
index.html
css/style.css
js/script.js
assets/
  ├── rafael-hero.jpg        ← foto do hero (retrato escritório)
  ├── casal-1.jpg / casal-2.jpg  ← fotos do casal (seção "Sobre nós")
  ├── simbolo-vermelho.png   ← mão Embracon vermelha, fundo transparente
  ├── simbolo-branco.png     ← mão Embracon branca, fundo transparente
  └── mao-*-p1..p4.png       ← peças da mão (loader + seção Modalidades)
```

## Deploy

1. `git init` → `git add .` → `git commit -m "first"`
2. Push pro GitHub
3. Vercel → Import repo → Framework: **Other** → Deploy
   (root da pasta, sem build command, sem output directory)

## Antes de publicar — trocar

| O quê | Onde |
|---|---|
| Número do WhatsApp | `js/script.js`, linha `var WPP = '5511993016158';` — muda em um lugar só, o script reescreve todos os links |
| Instagram | buscar `embracon.analiafranco` no `index.html` |
| Endereço da unidade | rodapé, bloco "Unidade" (já preenchido: Rua Itapura, 1603) |
| Texto do comparativo | `index.html`, seção `#comparativo` — sem valores, só qualitativo |

## Cores da marca

Segue o manual da Embracon: fundo sempre claro, vermelho + branco + carvão.

- Vermelho Embracon: `#E30613` (oficial)
- Vermelho do símbolo: `#C90C10` (detalhes e hover)
- Carvão (texto): `#1A1A1A`
- Papel (fundo): `#FAF8F5`
- Papel alternado: `#F3EEE7`
- Branco puro: `#FFFFFF`

O marquee e o CTA final usam vermelho sólido, com a mão branca fundindo no fundo.

## Tipografia

- **Archivo Expanded** — títulos em caixa alta, peso 800 (o impacto)
- **Bodoni Moda itálico em vermelho** — os fechos de cada título (o refinamento)
- **Sora** — corpo de texto
- **JetBrains Mono** — rótulos e dados

---
Nova AI Solutions

## Seção "Sobre nós"

É a mesma estrutura nos dois sites (camila / rafael), com o texto individual
invertido e a barra vermelha destacando a frente de quem é dono daquele site:

- **Rafael Ferraz** — Comercial
- **Camila Casco** — Financeiro e administrativo

Os dois aparecem como **casados e proprietários da franquia Embracon Anália
Franco**. As fotos do casal ficam em `assets/casal-1.jpg` e `casal-2.jpg`,
sem filtro e sem overlay.
