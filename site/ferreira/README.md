# Site institucional — Elisângela Ferreira (Advocacia)

> Projeto de site refeito do zero na direção visual. **WIP — proposta visual para aprovação.**
> Nada publicado. O site antigo é preservado até existir versão nova revisável.
> Última atualização: 09/10/2026.

## Status
- ✅ **Proposta visual (etapa 1):** abertura editorial (hero) + Áreas de atuação (`proposal.html`).
- ✅ **Site completo (etapa 2):** `index.html` — direção **Bordô noturno** (fundos escuros
  bordô/grafite + dourado), estrutura inspirada na referência enviada (site Maier), traduzida
  para a identidade feminina da Elisângela. Seções: hero, manifesto, como trabalho, áreas,
  "mais que advogada, uma aliada", passo a passo, CTA, sobre, atendimento (presencial+online),
  FAQ, contato, rodapé. Responsivo, animações discretas, `prefers-reduced-motion`, menu mobile,
  filtro de áreas, acordeão de FAQ, âncoras com offset de header. Revisado em desktop e mobile.
- ⏳ Aguardando dados reais (contatos, OAB, endereço) e revisão jurídica para publicar.

> Referência: a estrutura veio do site do criminalista Yonatan Maier (preto+dourado,
> masculino). **Não** foi copiada — só a arquitetura/profundidade foi reaproveitada, na pele
> bordô/marfim/grafite/dourado da Elisângela (decisão da cliente: "bordô noturno dramático").

## Arquivos
| Arquivo | O que é |
|---------|---------|
| `proposal.html` | Proposta (hero + Áreas) — abrir com a pasta `assets/` ao lado |
| `assets/portrait.png` | Retrato recortado (fundo removido, para compor sobre bordô) |
| `assets/portrait-studio.png` | Retrato original tratado (fundo estúdio, 2x) — reserva |
| `assets/logo-ef.png` | Brasão EF com fundo transparente (a logo fornecida, mantida) |
| `proposta/*.png` | Capturas desktop e mobile (hero e página) para avaliação |

## Direção visual (resumo)
- **Linguagem:** editorial — serifada grande e fina (Cormorant Garamond) + sans legível (Mulish).
- **Paleta:** marfim `#F5EFE6`, bordô `#5B1A2B`, grafite `#292527`, dourado `#C9A24B` (só detalhes).
- **Hero:** campo bordô→grafite à esquerda (título, filete dourado, botões de contorno), retrato
  à direita com o cabelo escuro se fundindo no fundo escuro (mesmo efeito do post de referência).
- **Cabeçalho** em marfim para o brasão EF aparecer com fidelidade (EF bordô + filete dourado).
- **Movimento:** entradas suaves (IntersectionObserver), hover delicado; respeita
  `prefers-reduced-motion`; navegação por teclado; sem rolagem horizontal.

## Fotografia
- Foto real da cliente. Rosto, óculos, cabelo, roupa e proporções **preservados** — sem gerar
  outra pessoa, sem "embelezar". Upscale 2x **não-generativo** (Lanczos).
- Recorte de fundo feito localmente (OpenCV grabCut + matte protegido do blazer).
- ⚠️ Resolução útil do retrato ≈ 749×953 originais (upscalada para 1498×1906). Suficiente para o
  uso atual; para aplicações muito grandes, recomenda-se ensaio fotográfico futuro.

## Pendências
- ⏳ Aprovação da direção (hero + seção) pela cliente/Felipe.
- ⏳ Referência do Pinterest não pôde ser aberta aqui (rede bloqueada); direção derivada da
  descrição textual + post de referência. Enviar a imagem se quiser casar com o pin específico.
- ⏳ Contatos reais (WhatsApp/telefone/e-mail), endereço, redes — só entram quando fornecidos.
- ⏳ Revisão jurídica (OAB) dos textos antes de publicar. Sem promessa de resultado.
- ⏳ Nome do projeto nos docs antigos consta como "Fonseca"; cliente confirmou **Ferreira**.
