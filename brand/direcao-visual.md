# Direção Visual (Sistema e Tokens)

> Dono: `design-squad` (design-chief, Brad Frost — Atomic Design, ui-engineer, visual-generator).
> Documento-par de estratégia: `docs/03-identidade-visual.md` (aqui ficam tokens e componentes).
> Última atualização: 08/10/2026.

> 🔬 HEX e tipografia abaixo são sugestões de partida a validar (ver `docs/03`).

---

## 1. Tokens de cor (🔬)

```
--bordo-profundo: #5B1A2B;   /* primária */
--vinho:          #3E121E;   /* primária escura / "quase-preto" */
--rose-fechado:   #9E5A66;   /* secundária / apoio feminino */
--marfim:         #F5EFE6;   /* fundo claro base */
--dourado:        #C9A24B;   /* ACENTO — máx ~10% */
--texto-escuro:   #2A0E15;   /* texto sobre claro */
--texto-claro:    #F7F2EA;   /* texto sobre bordô */
```

Regras:
- Dourado só em detalhes (linhas, ícones, filetes). Nunca blocos grandes.
- Fundo padrão de leitura: marfim; títulos em bordô/vinho.
- Verificar contraste AA/AAA (público idoso/baixa visão) — ⏳ validar pares.

## 2. Tipografia (🔬)

- **Display/títulos:** serifada elegante (didone suave ou serifada humanista).
- **Texto/UI:** sem serifa humanista de alta legibilidade.
- **Escala sugerida:** 40/32/24/18/16/14 (desktop); corpos ≥16px; respiro generoso.
- ⏳ Definir famílias com licença (preferir Google Fonts) e disponibilidade no editor.

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
