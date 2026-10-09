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

## 10. Direções premium (método visual-generator do design-squad) — v2
> Três direções DISTINTAS, não variações da mesma. Estrutura de prompt: assunto · estilo ·
> referência · composição · cor · técnico · negativos. ⚠️ GPT erra texto; o nome final é
> fixado em vetor. Gerar 1:1, alta resolução.

**Direção 1 — Selo de maison (emblema couture)** · o mais seguro no GPT
`Emblema de marca de luxo. Monograma "E" e "F" entrelaçados em serifada didone de altíssimo contraste, traços capilares. Referência: monogramas de maison de alta-costura e restrição Art Déco. Composição: circular, simétrico, centralizado, muito respiro, dentro de um anel fino com pequeno detalhe geométrico déco no topo. Cor: bordô profundo #5B1A2B, filetes em dourado #C9A24B tipo foil metálico, fundo marfim #F5EFE6. Técnico: vetorial, nítido, 1:1, alta resolução. Negativos: sem balança, martelo, coluna, sem gradiente berrante, sem texto além de E e F, sem sombra pesada.`

**Direção 2 — Wordmark editorial (masthead de revista)** · fixar o nome em vetor
`Wordmark de luxo para "ELISANGELA FONSECA". Estilo: didone de alto contraste (energia de masthead de revista de moda premium), espaçamento entre letras amplo e impecável, hairline dourada sob o nome. Referência: tipografia editorial de luxo, letterpress com relevo sutil. Composição: centralizado, altíssimo respiro, duas linhas (nome + "ADVOGADA PREVIDENCIÁRIA" menor e espaçado). Cor: bordô #5B1A2B sobre marfim #F5EFE6, filete dourado #C9A24B. Técnico: 1:1, alta resolução. Negativos: sem ícone, sem símbolo jurídico, sem gradiente. Escreva EXATAMENTE "ELISANGELA FONSECA".` (recomendado: compor o nome em fonte real; usar o GPT só para referência de clima.)

**Direção 3 — Insígnia heráldica moderna (legado + confiança)**
`Insígnia de marca sofisticada e atemporal. Escudo/brasão minimalista e moderno com o monograma "EF" ao centro em serifada didone, emoldurado por linhas douradas finas e um único florão botânico discreto (folha de louro estilizada) muito sutil. Referência: heráldica contemporânea de luxo, sobriedade. Composição: simétrica, vertical, centralizada, respiro generoso. Cor: bordô #5B1A2B e dourado #C9A24B sobre marfim #F5EFE6. Técnico: vetorial, 1:1, alta resolução. Negativos: sem balança, martelo, coluna, espada; sem aparência de carimbo pesado; sem texto além de "EF".`

> Fluxo de qualidade (design-chief): gerar conceitos → revisar legibilidade em pequeno
> (favicon 32px) e contraste → reconstruir o escolhido em vetor com o nome em curvas.
