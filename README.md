# Rafael Ferraz — Embracon Anália Franco

Site estático (HTML + CSS + JS puro). Sem build, sem dependência.

## Estrutura

```
index.html
css/style.css
js/script.js
assets/
  ├── rafael-hero.jpg        ← foto do hero (retrato escritório)
  ├── rafael-ceo.jpg         ← foto da seção CEO (corpo inteiro)
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
| Número do WhatsApp | `js/script.js`, linha `var WPP = '5511999999999';` — muda em um lugar só, o script reescreve todos os links |
| Instagram | buscar `embracon.analiafranco` no `index.html` |
| Endereço da unidade | rodapé, bloco "Unidade" |
| Taxas do simulador | `js/script.js`, objeto `PLANOS` (auto 17%, imóvel 22%, serviços 20%, pesados 18%) |
| Números do comparativo | `index.html`, seção `#comparativo` |

## Cores da marca

Extraídas direto do logo:

- Vermelho Embracon: `#C90C10`
- Vermelho luminoso (hover/glow): `#FF2A31`
- Grafite base: `#0D0D0F`
- Off-white: `#F2EEE8`

O marquee e o CTA final usam `#C90C10` puro para o logo fundir no fundo.

---
Nova AI Solutions
