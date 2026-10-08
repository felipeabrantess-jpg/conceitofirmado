# Direção Visual (Sistema e Tokens)

> Dono: `design-squad` (design-chief, Brad Frost — Atomic Design, ui-engineer, visual-generator).
> Documento-par de estratégia: `docs/03-identidade-visual.md` (aqui ficam tokens e componentes).
> Última atualização: 08/10/2026.

> 🎯 HEX e tipografia DECIDIDOS (contraste verificado) — ver `docs/03` para a tabela completa.

---

## 1. Tokens de cor (🎯 decididos)

```css
--bordo-profundo: #5B1A2B;   /* primária — títulos, base da marca */
--vinho:          #3E121E;   /* primária escura / "quase-preto" */
--rose-fechado:   #9E5A66;   /* secundária / apoio — texto só grande */
--marfim:         #F5EFE6;   /* fundo claro base */
--dourado:        #C9A24B;   /* ACENTO — máx ~10%; nunca texto sobre marfim */
--texto-escuro:   #2A0E15;   /* corpo sobre marfim (15.67:1, AAA) */
--texto-claro:    #F7F2EA;   /* texto sobre bordô/vinho (AAA) */
```

Regras (contraste WCAG verificado — tabela em `docs/03` §2):
- Dourado só em detalhes (filetes, ícones). **Nunca** texto dourado sobre marfim (2.1:1
  reprova). Dourado como texto só sobre fundo escuro (AA).
- Corpo de texto: vinho-tinta sobre marfim. Em fundo bordô/vinho, texto marfim-claro.
- Rosé é apoio/UI e texto grande; não usar em corpo.

## 2. Tipografia (🎯 decidida — Google Fonts)

- **Títulos: Playfair Display** (serifada didone). Fallback: Georgia, serif.
- **Texto/UI: Mulish** (humanista, legível). Fallback: Segoe UI, Arial, sans-serif.
- **Escala (web):** 44/34/26/20 títulos (Playfair); corpo 17–18, legenda 14 (Mulish);
  entrelinha 1.5 no corpo.
- Playfair só em títulos/destaques; corpo sempre Mulish.
- Ambas disponíveis no Canva (a cliente consegue produzir sozinha depois).

## 3. Componentes (Atomic Design)

- **Átomos:** cor, tipografia, ícone (linha fina), botão, filete dourado.
- **Moléculas:** cabeçalho de card, citação, item de FAQ, selo "você sabia".
- **Organismos:** capa de carrossel, página interna de carrossel, capa de Reel, card de
  destaque, bloco de CTA ético, cabeçalho de página de site.
- **Templates:** carrossel (capa + internas + CTA), Reel (capa + lower-thirds), stories
  (pergunta, enquete, FAQ, bastidor), página de benefício (site).

## 4. Capas de destaque (Instagram)

Nomes: Comece aqui, Aposentadoria, Incapacidade, BPC/LOAS, Maternidade, Rural, Acidente de
trabalho, Sobre, Perguntas. Fundo bordô/marfim + ícone dourado consistente.

## 5. Iconografia

Estilo linha fina, peso uniforme, dourado como acento. Evitar ícones jurídicos clichê
(balança/martelo). Preferir ícones de pessoas, documentos, proteção, cuidado.

## 6. Fotografia

Retratos profissionais (luz suave, paleta de fundo), espaço para texto, expressão acolhedora.
Evitar banco de imagem de "justiça". (Detalhe em `docs/03` §5.) ⏳ ensaio.

## 7. Acessibilidade visual

Corpos grandes, alto contraste, legendas em todos os vídeos, não depender só de cor para
transmitir informação.

## 8. Entregáveis de design (kit)

- [ ] Paleta validada + verificação de contraste.
- [ ] Famílias tipográficas + licenças.
- [ ] Logotipo + monograma EF.
- [ ] Kit de templates (carrossel, Reel, stories, capas de destaque).
- [ ] Modelos de página do site.
- [ ] Banco de fotos profissionais.

---

## Pendências
- ⏳ Validar tokens e tipografia; verificar contraste.
- ⏳ Produzir logo/monograma e kit de templates.
- ⏳ Ensaio fotográfico (custo/agenda).
