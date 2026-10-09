# Especificação do Logotipo

> Dono: `design-squad` (design-chief, ui-engineer). Conceito aprovado em `docs/03` §4 (D19).
> Este documento permite reproduzir o logo com fidelidade em vetor ou no Canva.
> Última atualização: 08/10/2026.

> A cliente começa do zero (F9): não há logo anterior. Mockup visual no brand board e no kit
> de Instagram (artefatos da sessão). Abaixo, a construção para gerar os arquivos finais.

---

## 1. Versão principal (lockup vertical)

```
            Elisangela Fonseca            ← Playfair Display, peso 600
            ───────────                    ← filete dourado, centralizado
          ADVOGADA PREVIDENCIÁRIA          ← Mulish 600, caixa alta, tracking 0.30em
```

- **Nome:** "Elisangela Fonseca" em **Playfair Display 600**, cor bordô `#5B1A2B`.
- **Filete:** linha dourada `#C9A24B`, largura ≈ 40% da largura do nome, espessura 2px (em
  proporção ao tamanho), centralizada, com respiro de ~0.4× a altura da maiúscula acima e
  abaixo.
- **Descritor:** "ADVOGADA PREVIDENCIÁRIA" em **Mulish 600**, caixa alta, tracking `0.30em`,
  cor bordô ou vinho `#3E121E`; tamanho ≈ 22% do tamanho do nome.

## 2. Versão horizontal (assinatura em rodapé/cabeçalho)
- Nome e descritor na mesma linha de base quando o espaço for largo, com o filete dourado
  como separador vertical curto entre nome e descritor. Usar quando a altura for limitada.

## 3. Monograma "EF" (avatar, selo, favicon)
- Letras **E** e **F** em **Playfair Display 700**.
- Formato: círculo. Duas versões:
  - **Sobre bordô:** fundo `#5B1A2B`, letras `#F5EFE6`, borda/anel dourado `#C9A24B` (2–3px).
  - **Sobre marfim:** fundo `#F5EFE6`, letras `#5B1A2B`, anel dourado `#C9A24B`.
- Favicon: versão sobre bordô, sem o anel se ficar ilegível em 32px.

## 4. Cores
- Bordô `#5B1A2B` · Vinho `#3E121E` · Dourado `#C9A24B` · Marfim `#F5EFE6`.
- Dourado só no filete/anel (acento). Nunca o logo todo em dourado.

## 5. Área de proteção e tamanho mínimo
- **Clearspace:** margem livre ao redor = altura da letra "E" do monograma.
- **Tamanho mínimo:** nome legível a partir de ~24px de altura; monograma a partir de 32px.

## 6. Versões a entregar (arquivos)
- [ ] Principal — bordô sobre transparente (SVG + PNG).
- [ ] Principal negativo — marfim sobre bordô (SVG + PNG).
- [ ] Horizontal (SVG + PNG).
- [ ] Monograma sobre bordô e sobre marfim (SVG + PNG).
- [ ] Favicon (32px, 180px).
- [ ] Preto e branco (documentos/petições).

## 7. Proibições
- Sem balança, martelo, colunas ou símbolo jurídico óbvio.
- Sem preto puro (usar vinho).
- Sem distorcer proporções, trocar as fontes ou encher de dourado.

## 8. Produção
- Fontes: Playfair Display e Mulish (Google Fonts, licença livre; disponíveis no Canva).
- Ao exportar vetor final, **converter o texto em curvas** para não depender da fonte.
- ⏳ Gerar os arquivos a partir desta especificação.

## 9. Prompts premium para o GPT (gerar e depois refinar em vetor)
> ⚠️ O gerador erra texto. Se o nome sair com letra trocada, gere só o **emblema/monograma** e
> componha o nome em vetor/Canva com Playfair Display. O emblema é o que o GPT faz bem.

**Opção A — Emblema/monograma (recomendado, mais confiável)**
`Emblema de marca de luxo para uma advogada, estética de alta joalheria e alta-costura. Monograma circular elegante com as letras "E" e "F" entrelaçadas, desenhadas em serifada didone de alto contraste, traços finos e refinados, dentro de um aro circular delicado com um filete dourado tipo foil metálico sutil. Paleta: bordô profundo #5B1A2B e dourado #C9A24B sobre fundo marfim #F5EFE6. Minimalista, muito espaço em branco, atemporal, acabamento premium, vetorial e limpo, simétrico, centralizado, alta resolução. SEM balança, martelo, coluna ou símbolos jurídicos; sem gradientes berrantes; sem texto além das letras E e F.`

**Opção B — Logotipo completo (nome + monograma)**
`Logotipo de luxo para "ELISANGELA FONSECA", advogada previdenciária, identidade sofisticada e feminina, estética de maison de alto padrão. No topo, um monograma circular com as letras "E" e "F" entrelaçadas em serifada didone, aro dourado fino (foil sutil). Abaixo, o nome em serifada fina e elegante, com amplo espaçamento entre letras: "ELISANGELA FONSECA". Em uma linha menor: "ADVOGADA PREVIDENCIÁRIA". Paleta: bordô profundo #5B1A2B e marfim #F5EFE6, dourado #C9A24B só nos filetes. Fundo marfim liso. Minimalista, premium, atemporal, vetorial, centralizado, alta resolução. Escreva o texto EXATAMENTE "ELISANGELA FONSECA". SEM balança, martelo, coluna ou clichês jurídicos.`

**Opção C — Selo/crista moderna (mais sofisticado)**
`Selo de marca premium para uma advogada, estilo monograma de maison de luxo. Monograma "EF" em serifada didone de alto contraste, centralizado, emoldurado por um anel duplo fino dourado com um pequeno detalhe geométrico art déco minimalista no topo e na base. Bordô profundo #5B1A2B e dourado #C9A24B sobre marfim #F5EFE6. Elegante, discreto, atemporal, vetorial, simétrico, alta resolução. Sem símbolos jurídicos; sem texto além de "EF".`

> Depois de gerar, para refinar: peça "fundo marfim perfeitamente liso", "linhas douradas mais
> finas", "mais espaço em branco" ou "versão em uma cor (só bordô)". Variações úteis: fundo
> bordô com monograma marfim; monograma dourado sobre bordô.
