# Google Search (Ads) + Infraestrutura Google

> Dono: `traffic-masters` (Kasim Aslam) + `data-squad`. Estratégia em `docs/10`; SEO em
> `docs/09`. Compliance `docs/13`.
> Última atualização: 08/10/2026.

> ⚠️ **Anúncios só após validação de compliance** (impulsionamento/anúncio por advogado —
> `docs/13`). Até lá, este documento é 🔬/⏳.

---

## Parte A — Google Ads (Search)

### 1. Estrutura de conta (🎯)
```
Conta
└── Campanha (por benefício ou por objetivo)
    └── Grupo de anúncios (tema específico)
        ├── Palavras-chave (de alta intenção)
        ├── Anúncios (informativos)
        └── Página de destino coerente (site/landing-pages.md)
```

### 2. Seleção de campanhas iniciais (🔬)
Começar por intenção-problema de alto valor:
- Campanha "Incapacidade" (ex.: "INSS negou benefício").
- Campanha "Aposentadoria/Planejamento".
(Expandir conforme orçamento e resultado.)

### 3. Palavras-chave
- Fonte: `growth/seo-clusters.md` (termos transacionais/problema/local).
- Correspondência: iniciar frase/exata para controle de custo.
- **Negativas:** "grátis", "sozinho", "como fazer sem advogado", "concurso", "vaga",
  "simulador", nomes de concorrentes (se vedado), termos fora do escopo.

### 4. Anúncios (informativos — compliance)
- Títulos claros e sóbrios ("Dúvidas sobre o INSS? Atendimento com clareza").
- **Sem** promessa de resultado, "garantido", "rápido", urgência artificial.
- Extensões: sitelinks (páginas de benefício), local (se GBP), chamada (se permitido).

### 5. Páginas de destino
- Específicas por benefício (`site/landing-pages.md`), informativas, com CTA ético e política
  de privacidade (LGPD).

### 6. Métricas
- CTR, índice de qualidade, CPC, conversões (contato qualificado), **custo por contato
  qualificado**. Norte: qualidade, não cliques.

---

## Parte B — Infraestrutura Google (orgânico)

### 7. Google Search Console (GSC)
- Verificar propriedade; enviar sitemap.xml; monitorar indexação, desempenho e erros.
- Usar relatórios de consulta para achar novas pautas (long tail).

### 8. Google Analytics 4 (GA4)
- Instalar no site; configurar eventos de conversão (clique WhatsApp, envio de formulário,
  download de material). Detalhe em `growth/tracking.md`.

### 9. Google Business Profile (GBP) — SEO local
- Quando aplicável (atendimento presencial/endereço — ⏳). Categoria "Advogado"; dados NAP
  consistentes; posts; avaliações dentro da ética (⚠️ `docs/13`).

### 10. Indexação
- sitemap.xml + robots.txt; enviar no GSC; dados estruturados (FAQ, LegalService, Person).

---

## Pendências
- ⏳ Validação OAB de anúncios (bloqueante).
- ⏳ Conta Google Ads + verificação de anunciante; orçamento; praça.
- ⏳ Criar/verificar GSC, GA4, GBP; domínio e site no ar.
- ⏳ Páginas de destino prontas.
