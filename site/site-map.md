# Site Map (Arquitetura de Páginas)

> Dono: `design-squad` (ux-designer) + `data-squad` (SEO). Estratégia em `docs/08` e `docs/09`.
> Última atualização: 08/10/2026.

> Fase atual: arquitetura e copy (sem desenvolvimento). Taxonomia casa com marca (`docs/02`),
> destaques do IG (`docs/06`) e clusters de SEO (`growth/seo-clusters.md`).

---

## 1. Árvore do site

```
/                                   Home
/sobre                              Sobre Elisangela
/direito-previdenciario             Hub (pilar-mãe)
/aposentadorias                     Pilar
/aposentadorias/planejamento        Planejamento Previdenciário
/aposentadoria-especial             Pilar
/aposentadoria-rural                Pilar
/auxilio-incapacidade-temporaria    Pilar
/acidente-de-trabalho               Pilar
/salario-maternidade                Pilar
/bpc-loas                           Pilar (subtema: deficiência → 🔬 autismo)
/conteudos                          Blog / Artigos (satélites de SEO)
/perguntas-frequentes               FAQ geral
/contato                            Contato (+ formulário LGPD)
/politica-de-privacidade            LGPD
```

(URLs são sugestões 🔬; ajustar ao CMS e à praça/local se houver SEO local.)

## 2. Navegação

- **Menu principal:** Início · Sobre · Direito Previdenciário (dropdown com benefícios) ·
  Conteúdos · Perguntas · Contato.
- **Rodapé:** dados profissionais + OAB (⏳) · benefícios · política de privacidade · contato ·
  redes.
- **Interlinking:** hub ↔ pilares ↔ satélites (`docs/09` §4).

## 3. Hierarquia de páginas-pilar
Cada benefício é pilar com estrutura padrão (`docs/08` §3) e recebe os artigos do seu cluster
(`growth/seo-clusters.md`). O hub "Direito Previdenciário" apresenta e linka todos.

## 4. Elementos globais
- Cabeçalho com identidade bordô e CTA ético discreto.
- Bloco "Como funciona o atendimento" reutilizável.
- Aviso de cookies (LGPD) + Política de Privacidade.
- Dados estruturados: Person/LegalService + FAQ nas páginas aplicáveis.

## 5. Prioridade de construção (🎯 — casa com `docs/15`)
1. Home + Sobre + Hub.
2. 3–4 pilares de maior intenção (Incapacidade, Aposentadoria, BPC/LOAS, +1).
3. Blog + FAQ.
4. Demais pilares + landing pages de campanha.

---

## Pendências
- ⏳ CMS/domínio (`docs/08`).
- ⏳ Dados reais para "Sobre".
- ⏳ Decisão de SEO local (páginas por cidade).
