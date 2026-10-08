# 14 — Métricas e KPIs

> Dono: `data-squad` (Avinash Kaushik — analytics; Peter Fader — valor de cliente; Sean Ellis
> — growth). Execução em `operations/dashboard-metricas.md` e `growth/tracking.md`.
> Última atualização: 08/10/2026.

> Princípio (Avinash Kaushik): medir **resultado**, não vaidade. O norte do projeto é
> **autoridade encontrável + contato qualificado ético**, não curtidas.

---

## 1. North Star Metric (🎯)

**Contatos qualificados por mês** (pessoas certas, no tema certo, que chegam por confiança) —
ponderados por **qualidade**, não só volume. Sustentada por duas métricas de apoio:
- **Busca por marca** ("Elisangela Fonseca advogada") — sinal de autoridade/lembrança.
- **Tráfego orgânico de intenção** (páginas de benefício no Google) — sinal de
  encontrabilidade.

---

## 2. KPIs por camada da jornada

### Descoberta / Alcance
- Alcance e impressões (Instagram), novos seguidores, visualizações de Reels.
- Impressões e cliques orgânicos (GSC), posições médias por cluster.
- Alcance de campanhas (quando houver mídia — `docs/10`).

### Engajamento / Autoridade
- **Salvamentos e compartilhamentos** (sinal de referência > curtida).
- Tempo em página, páginas por sessão (GA4).
- Crescimento de busca por marca; menções/backlinks.

### Consideração / Confiança
- Visitas às páginas de benefício; cliques em "tirar dúvida".
- Taxa de conclusão de FAQ/artigos.

### Conversão (ética)
- Contatos por canal e por tema (WhatsApp/formulário).
- Taxa contato → atendimento → cliente (funil).
- **Custo por contato qualificado** (se houver mídia).
- Qualidade do contato (dentro do tema/praça, não lead frio).

### Retenção / Valor (Peter Fader)
- Indicações recebidas; recorrência (planejamento previdenciário, novas demandas).
- 🔬 LTV por tipo de caso (quando houver dados).

---

## 3. Metas (🔬 — placeholders a calibrar)

Metas reais dependem da linha de base (ainda inexistente — conta nova) e da capacidade de
atendimento (⏳ `docs/01`). Estrutura de metas por fase em `docs/15`. Exemplo de formato:

| Métrica | Baseline | Meta 30d | Meta 60d | Meta 90d |
|---------|----------|----------|----------|----------|
| Contatos qualificados/mês | ⏳ | 🔬 | 🔬 | 🔬 |
| Seguidores (IG) | ⏳ | 🔬 | 🔬 | 🔬 |
| Páginas ranqueando (top 10) | 0 | 🔬 | 🔬 | 🔬 |
| Busca por marca/mês | ⏳ | 🔬 | 🔬 | 🔬 |

> Preencher baseline assim que contas forem criadas e medidas (GSC/GA4/IG Insights).

---

## 4. Instrumentação (liga com `growth/tracking.md`)

- **GA4** no site (eventos: contato, clique WhatsApp, download de material).
- **Google Search Console** (busca orgânica).
- **Instagram Insights** (conteúdo/alcance/salvamentos).
- **Pixel/Tag** (se houver mídia) com eventos de conversão.
- **Planilha/CRM** de contatos por tema (origem → desfecho).
- ⚠️ Tudo em conformidade com LGPD (`docs/13`).

---

## 5. Ritmo de análise

- **Semanal:** conteúdo (o que performou, salvamentos, dúvidas novas → pautas).
- **Mensal:** funil completo, SEO (GSC), contatos por tema, ajuste de prioridades.
- **Trimestral:** autoridade (marca, menções), revisão de metas e roadmap.

Dashboard e modelos de relatório em `operations/dashboard-metricas.md`.

---

## 6. Pendências

- ⏳ Criar e acessar GSC, GA4, IG Insights; definir baseline.
- ⏳ Definir capacidade de atendimento (teto de contatos que vira cliente).
- ⏳ Calibrar metas reais por fase.
- ⏳ Escolher CRM/planilha de contatos (custo).
