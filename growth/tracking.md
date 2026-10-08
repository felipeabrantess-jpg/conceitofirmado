# Tracking e Mensuração

> Dono: `data-squad` (Avinash Kaushik) + `traffic-masters` (pixel-specialist). Liga com
> `docs/14` e `operations/dashboard-metricas.md`. Compliance/LGPD `docs/13`.
> Última atualização: 08/10/2026.

> ⚠️ Todo rastreamento respeita LGPD: consentimento de cookies, finalidade, minimização e
> segurança (`docs/13` §6). 🔬/⏳ até o site existir e o consentimento estar implementado.

---

## 1. Stack de medição (🎯)
| Ferramenta | Função |
|------------|--------|
| Google Analytics 4 (GA4) | Comportamento no site, conversões |
| Google Search Console | Busca orgânica (consultas, posições) |
| Google Tag Manager (opcional) | Gerenciar tags sem mexer no código |
| Meta Pixel / Conversions API | Medição de campanhas Meta (se houver) |
| Google Ads tag | Conversões de Search (se houver) |
| Instagram Insights | Conteúdo/alcance/salvamentos |
| CRM/planilha | Contatos por tema (origem → desfecho) |

## 2. Eventos de conversão a medir (🎯)
- Clique no botão/link de WhatsApp.
- Envio de formulário de contato.
- Download de material rico (opt-in).
- Clique em "ligar" (se aplicável).
- Visualização de página-pilar de benefício (micro-conversão).

## 3. Modelo de UTM (padronização)
```
?utm_source= (instagram | google | meta | whatsapp | email)
&utm_medium= (organic | cpc | bio | story | post)
&utm_campaign= (nome-da-campanha-ou-tema)
&utm_content= (criativo/variação)
```
Usar UTMs consistentes para separar orgânico de pago e atribuir contatos.

## 4. Governança de dados (LGPD)
- Banner de consentimento de cookies antes de disparar tags de marketing.
- Anonimização de IP quando possível; retenção mínima.
- Política de Privacidade publicada (`docs/13`, `site/`).
- Nenhum dado sensível rastreado em marketing.

## 5. Painel e cadência
- Fonte do `operations/dashboard-metricas.md`.
- Semanal (conteúdo), mensal (funil/SEO), trimestral (autoridade/metas) — `docs/14`.

---

## Pendências
- ⏳ Site no ar + banner de consentimento.
- ⏳ Criar GA4/GSC; instalar tags; definir eventos.
- ⏳ Escolher CRM/planilha; definir baseline (`docs/14`).
