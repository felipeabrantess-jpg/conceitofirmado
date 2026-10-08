# 03 — Identidade Visual

> Dono: `design-squad` (design-chief, Brad Frost, ux-designer, visual-generator).
> Documento-par de execução: `brand/direcao-visual.md`.
> Última atualização: 08/10/2026.

---

## 1. Direção aprovada (✅)

Direção visual **BORDÔ**, já definida/preferida pela cliente. Sensação-alvo: **autoridade,
elegância, acolhimento, feminilidade, sofisticação, confiança e clareza.**

---

## 2. Paleta de cores (🎯 DECIDIDA — HEX fechados, contraste verificado)

| Papel | Cor | HEX | Uso |
|-------|-----|-----|-----|
| Primária | Bordô profundo | `#5B1A2B` | Títulos, fundo de autoridade, base da marca |
| Primária escura | Vinho | `#3E121E` | "Quase-preto", profundidade, texto escuro |
| Secundária | Rosé fechado | `#9E5A66` | Apoio feminino, detalhes, estados; **texto só grande** |
| Neutra clara | Marfim | `#F5EFE6` | Fundo claro principal, respiro, legibilidade |
| Acento | Dourado | `#C9A24B` | **Só acento** — filetes, ícones, detalhes |
| Texto escuro | Vinho-tinta | `#2A0E15` | Corpo de texto sobre marfim |
| Texto claro | Marfim-claro | `#F7F2EA` | Texto sobre bordô/vinho |

**Contraste WCAG verificado (sobre marfim, salvo indicação):**

| Combinação | Razão | Nível |
|------------|-------|-------|
| Texto vinho-tinta sobre marfim | 15.67 | AAA ✓ corpo |
| Vinho sobre marfim | 14.02 | AAA ✓ |
| Bordô sobre marfim | 11.29 | AAA ✓ títulos |
| Texto claro sobre bordô | 11.58 | AAA ✓ |
| Dourado sobre vinho | 6.68 | AA ✓ (texto em fundo escuro ok) |
| Dourado sobre bordô | 5.38 | AA ✓ |
| Rosé sobre marfim | 4.47 | AA grande ✓ (não usar em corpo) |
| **Dourado sobre marfim** | **2.10** | **REPROVA ✗ — nunca texto dourado em fundo claro** |

**Regras de cor (🎯):**
- Dourado é **acento**, teto ~10% da composição. **Nunca** como texto sobre marfim (reprova);
  só como filete/ícone/detalhe, ou como texto sobre fundo escuro (aí passa AA).
- Base de leitura: marfim com texto vinho-tinta (`#2A0E15`). Em fundo bordô/vinho, texto
  marfim-claro.
- Rosé é cor de apoio/UI e de **texto grande**; não usar em corpo de texto.
- Evitar preto puro; usar vinho como "quase-preto".

---

## 3. Tipografia (🎯 DECIDIDA)

Par serifada + humanista, ambas **Google Fonts** (licença livre, disponíveis no Canva — bom
para a cliente produzir sozinha depois).

- **Títulos (display): Playfair Display** (serifada didone). Autoridade + elegância +
  feminilidade, com peso suficiente para legibilidade (mais robusta que opções muito finas).
- **Texto / UI: Mulish** (sem serifa humanista). Acolhedora, muito legível em tela e em
  corpos maiores — importante para o público idoso do previdenciário.
- **Fallbacks:** Playfair Display → Georgia, serif. Mulish → "Segoe UI", Arial, sans-serif.
- **Alternativa de corpo** (se quiser ainda mais neutro/legível): Inter.

**Escala sugerida (web):** 44 / 34 / 26 / 20 (Playfair) · corpo 17–18, legenda 14 (Mulish).
Entrelinha confortável (1.5 no corpo), parágrafos curtos.

- ⚠️ Playfair só em títulos/destaques; nunca em corpo longo (serifada didone cansa em texto
  pequeno). Corpo é sempre Mulish.

---

## 4. Logotipo e marca gráfica (🎯 CONCEITO DECIDIDO)

Não existe logo anterior (cliente começa do zero — F9), então construímos do zero.

- **Logotipo principal:** **tipográfico**, com "Elisangela Fonseca" em Playfair Display +
  descritor "Advogada Previdenciária" em Mulish (caixa alta, tracking amplo), abaixo do nome.
  Sem símbolo jurídico óbvio.
- **Monograma "EF":** versão reduzida para avatar (Instagram/GBP), selo e favicon. Letras em
  Playfair, com **filete dourado** como assinatura (um traço fino sob ou ao lado do monograma).
- **Assinatura gráfica:** um **filete/arco dourado** fino como elemento recorrente (divisórias,
  detalhes de card), reforçando identidade sem poluir.
- **Versões:** principal (bordô sobre marfim), negativa (marfim sobre bordô), monograma, e
  preto/branco para documentos.
- **Proibições:** balança, martelo, colunas, excesso de dourado, preto puro.
- ⏳ Produzir os arquivos do logo (vetor) a partir deste conceito.

---

## 5. Direção fotográfica (🎯)

- Fotos **profissionais** da Elisangela: iluminação suave, fundo em tons da paleta (marfim,
  bordô), vestuário sóbrio e elegante. Expressão acolhedora e confiante, não "dura".
- Composição deixa **espaço para texto** (para capas de Reels/carrossel).
- Evitar bancos de imagem clichê de "justiça". Preferir retratos reais + detalhes de
  ambiente de trabalho sofisticado.
- ⏳ Agendar ensaio fotográfico profissional (pendência operacional e de custo).

---

## 6. Sistema visual aplicado (🎯)

- **Templates** para: capa de carrossel, páginas internas, capa de Reel, citações, "você
  sabia", FAQ, aviso de atualização jurídica, card de boas-vindas.
- **Grid e respiro:** generosos, estética "editorial premium", não poluída.
- **Iconografia:** linha fina, dourada como acento, estilo consistente.
- **Acessibilidade visual:** corpos de fonte grandes, alto contraste, legendas em vídeos.

> O sistema de componentes (abordagem Atomic Design — Brad Frost) é detalhado em
> `brand/direcao-visual.md`, que é o dono dos tokens e templates.

---

## 7. Aplicações

- Instagram: foto de perfil, destaques (capas na paleta), feed coeso.
- Site: paleta + tipografia + fotografia (ver `docs/08` e `site/`).
- WhatsApp Business: foto, nome e mensagem visualmente alinhados.
- Materiais ricos: e-books/guias com a mesma identidade.

---

## 8. Pendências de identidade visual

- ⏳ Validar HEX finais e verificar contraste de acessibilidade.
- ⏳ Definir famílias tipográficas e licenças.
- ⏳ Auditar/definir logotipo e monograma.
- ⏳ Ensaio fotográfico profissional (custo + agenda).
- ⏳ Produzir kit de templates no editor escolhido.
