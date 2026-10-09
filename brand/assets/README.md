# Brand Assets

Arquivos de marca do projeto Elisangela Fonseca. Especificações em `../direcao-visual.md` e
`../logo-specs.md`.

| Arquivo | O que é | Status |
|---------|---------|--------|
| `elisangela-perfil-avatar.webp` | **Foto de perfil oficial** — 1:1, fundo bordô uniforme | ✅ APROVADA (avatar do Instagram/GBP) |
| `elisangela-retrato-01.webp` | Retrato original (fundo com brilho) | referência; fonte do ajuste |

> Regra: retratos da advogada são **sempre fotos reais**, nunca geradas por IA (ver
> `../../docs/03-identidade-visual.md`).
>
> Ajustes sugeridos para o retrato 01: uniformizar o leve brilho alaranjado no canto superior
> direito para o bordô da paleta; produzir versão com espaço ao lado do rosto para texto
> (carrossel). Ensaio futuro: mais ângulos e planos.

---

## Prompts de ajuste do retrato 01 (editar no ChatGPT)

> Regra de segurança: em foto real, a IA só mexe no **fundo/enquadramento**. **Nunca** altere
> rosto, cabelo, óculos, pele, roupa ou pose, e nunca "embeleze" — tem que continuar sendo ela.
> Suba a foto `elisangela-retrato-01.webp` e cole o prompt.

**Principal — Foto de perfil (avatar 1:1)** — usar este primeiro
`Edite esta foto para ser a foto de perfil oficial de uma advogada. Mantenha a pessoa exatamente como está — mesmo rosto, cabelo, óculos, pele, expressão, maquiagem, blazer branco e pose. Não altere nenhum traço, não rejuvenesça e não "embeleze": tem que continuar sendo ela, de forma realista e natural. Ajuste apenas: Fundo bordô profundo #5B1A2B totalmente uniforme e liso, removendo o brilho alaranjado do canto superior direito, com iluminação de estúdio suave e homogênea. Acabamento de retrato profissional, nítido, cores elegantes e naturais, pele com textura real (sem plastificar). Enquadramento quadrado 1:1, pessoa centralizada, da cabeça aos ombros, com folga ao redor para caber no recorte circular do perfil do Instagram sem cortar o rosto nem o cabelo. Sem texto, sem logotipo e sem elementos gráficos.`

**A) Uniformizar o fundo (sem mudar enquadramento)**
`Edite esta foto mantendo a pessoa exatamente igual — rosto, cabelo, óculos, roupa e pose intactos, sem alterar nenhum traço. Mexa só no fundo: deixe o bordô profundo #5B1A2B totalmente uniforme, removendo o brilho alaranjado do canto superior direito. Iluminação de estúdio suave e homogênea. Não adicione texto nem elementos.`

**B) Versão com espaço para texto (carrossel 4:5)**
`Amplie (outpaint) esta imagem para o formato vertical 4:5 (1080x1350), estendendo o fundo bordô #5B1A2B de forma uniforme para a ESQUERDA, de modo que a pessoa fique deslocada para a direita e sobre uma grande área lisa de bordô à esquerda, livre para inserir texto depois. Mantenha a pessoa idêntica, sem alterar rosto, roupa ou pose. Sem texto, sem elementos novos.`

**C) Capa vertical para Reel/Story (9:16)** — se precisar
`Amplie (outpaint) esta imagem para 9:16 (1080x1920), estendendo o fundo bordô #5B1A2B uniforme para cima e para baixo, mantendo a pessoa idêntica e deixando área lisa para texto. Sem texto, sem novos elementos.`

> Alternativa mais segura (sem IA): no **Canva**, coloque a foto atual sobre um fundo bordô
> #5B1A2B, alinhada à direita, deixando o terço esquerdo livre para o texto. Zero risco de a
> IA mexer no rosto. Recomendado para a versão com espaço de texto.

---

## Logotipo (Selo EF + Masthead) — construído em vetor
| Arquivo | O que é |
|---------|---------|
| `selo-ef-marfim.png` | Selo EF principal, fundo transparente (sobre claro) |
| `selo-ef-bordo.png` | Selo EF negativo, sobre bordô |
| `avatar-ef.png` | Monograma EF para avatar/favicon (bordô, sem microtexto) |
| `wordmark-ef.png` | Masthead "ELISANGELA FONSECA" (fundo transparente) |
| `logo-final-elisangela.pdf` | Folha de apresentação do logotipo |
| `logo-build.html` | **Fonte vetorial** (SVG + Playfair/Mulish) — editar aqui e re-renderizar |

> Construído à mão em SVG (texto exato, não IA). Playfair Display (monograma/nome) + Mulish
> (microtexto). Dourado só no filete. 🎯 Decisão de design **pendente de validação da cliente**
> (`docs/17`). ⏳ Exportar SVG final a partir do `logo-build.html` quando aprovado.

⏳ A produzir: capas de destaque, templates de carrossel.
