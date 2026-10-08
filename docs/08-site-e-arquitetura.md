# 08 — Site e Arquitetura

> Dono: `design-squad` (ux-designer, design-chief) + `data-squad` (SEO) + `copy-squad` (copy).
> Execução detalhada em `site/`.
> Última atualização: 08/10/2026.

> Nesta fase: **arquitetura e copy**, não desenvolvimento (sem código de produção).

---

## 1. Função estratégica do site (🎯)

O site é a base que a cliente **controla** (diferente das redes). Ele é, ao mesmo tempo:
autoridade + conteúdo + Google/SEO + confiança + relacionamento. **Não** é um cartão de
visitas institucional parado. É o destino das buscas de intenção e a prova definitiva de
competência.

---

## 2. Arquitetura de páginas (✅ base do briefing + 🎯 refinamento)

```
Home
├── Sobre Elisangela
├── Direito Previdenciário (hub/pilar-mãe)
│   ├── Aposentadorias
│   │   └── Planejamento Previdenciário
│   ├── Aposentadoria Especial
│   ├── Aposentadoria Rural
│   ├── Auxílio por Incapacidade Temporária
│   ├── Acidente de Trabalho
│   ├── Salário-Maternidade
│   └── BPC / LOAS   (subtema: Deficiência — abriga 🔬 autismo)
├── Conteúdos / Artigos (blog)
├── Perguntas Frequentes (FAQ)
└── Contato
```

Observações:
- 🎯 "Direito Previdenciário" funciona como **página-hub** que linka para cada benefício
  (estrutura pilar → cluster, boa para SEO — ver `docs/09`).
- 🎯 "Planejamento Previdenciário" como subpágina de Aposentadorias (alto valor percebido).
- Cada página de benefício é uma **página-pilar** com seu cluster de artigos.

---

## 3. Padrão de página de benefício (🎯)

Cada página de benefício segue a mesma estrutura (consistência + SEO + conversão ética):
1. **H1 claro** com o benefício e a dúvida central.
2. **Resumo humano** (o que é, para quem, sem juridiquês).
3. **"Você pode ter direito se..."** (situações, linguagem informativa).
4. **Como funciona / passo a passo** (educativo). ⏳ revisão técnica.
5. **Documentos / o que organizar.**
6. **Dúvidas frequentes** (FAQ específico — rich snippet).
7. **Conteúdos relacionados** (links internos para artigos do cluster).
8. **CTA ético** (tirar dúvida / agendar análise), sem promessa de resultado.

Copy em `site/site-copy.md`; mapa em `site/site-map.md`; FAQ em `site/faq.md`; páginas de
destino de campanha em `site/landing-pages.md`.

---

## 4. Home (estrutura)

- Herói: quem é + o que resolve + convite a explorar (clareza em 1 frase).
- Blocos por território (cards para cada benefício).
- Prova de autoridade (⏳ depende de dados reais: títulos, experiência, depoimentos
  autorizados).
- Últimos conteúdos.
- Bloco "Como funciona o atendimento" + CTA ético.
- Rodapé com dados profissionais, OAB (⏳), política de privacidade (LGPD) e contato.

---

## 5. SEO on-page e técnico (resumo; detalhe em `docs/09`)

- URLs limpas por benefício (ex.: `/aposentadoria-rural`).
- Title/description por página com termo de intenção + marca.
- Headings hierárquicos, dados estruturados (FAQ, LegalService, Person).
- Interlinking hub ↔ clusters.
- Performance e mobile-first (público idoso; muitos em celular).
- Acessibilidade (contraste, fontes grandes — casa com `docs/03`).

---

## 6. Confiança e conformidade

- Página "Sobre" com credibilidade real (⏳ dados).
- Dados profissionais e OAB visíveis (⏳).
- **Política de Privacidade e aviso de cookies** (LGPD — `docs/13`).
- Formulário de contato com base legal e consentimento; sem captação indevida (`docs/13`).

---

## 7. Decisões técnicas em aberto (⏳)

- Plataforma/CMS (ex.: WordPress para blog/SEO vs. construtor). ⏳ decidir — impacto de custo.
- Domínio próprio. ⏳ definir e registrar.
- Hospedagem, e-mail profissional, certificado SSL. ⏳.
- Ferramenta de agendamento/contato. ⏳.

---

## 8. Pendências

- ⏳ Dados reais para "Sobre" e provas de autoridade.
- ⏳ Plataforma, domínio, hospedagem (custo).
- ⏳ Revisão técnica jurídica das páginas de benefício.
- ⏳ Política de privacidade (jurídico + LGPD).
