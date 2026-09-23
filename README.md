# Prisma 🔺 — Agent X-Ray

**O raio-x da sua operação de agentes de IA.** Um protótipo em um único arquivo HTML — sem build, sem backend, sem dependências — que avalia a qualidade de agentes a partir do catálogo e das interações em produção.

> **The x-ray of your AI agent operation.** A single-file HTML prototype — no build, no backend, no dependencies — that evaluates agent quality from the catalog and production interactions.

---

## 🇧🇷 Português

**O problema:** 27.000 agentes, 92% de adoção — e só 2% movem o ponteiro de verdade. Cada pergunta mal respondida vira retry, custo e confiança que evapora.

**O que o Prisma faz:** lê o catálogo de agentes e as interações reais, avalia **16 critérios em 5 pilares** (incluindo o pilar de qualidade da resposta com as **6 métricas do agent-eval do iFood** — DeepEval: Plan Quality, Plan Adherence, Tool Correctness, Argument Correctness, Task Completion, Step Efficiency) e devolve um raio-x claro.

**As duas jornadas conectadas:**
- 🧭 **Quem usa** → encontra o agente certo, conhece, aprende a perguntar no formato exato e compara na régua de maturidade
- 🧑‍💻 **Quem cria** → inventário do catálogo, qualidade em seis métricas, receitas antes × depois e acompanhamento da evolução

**Detalhes técnicos:**
- SPA vanilla: HTML + CSS (design system por tokens) + JS puro, zero dependências
- Todos os números derivam das fontes — nada inventado
- Acessibilidade: `:focus-visible`, `aria-current`, `prefers-reduced-motion`
- Dados 100% fictícios (catálogo de demonstração)

## 🇺🇸 English

**The problem:** 27,000 agents, 92% adoption — and only 2% really move the needle. Every poorly answered question becomes retry, cost and evaporated trust.

**What Prisma does:** reads the agent catalog and real interactions, evaluates **16 criteria across 5 pillars** (including the answer-quality pillar with the **6 iFood agent-eval metrics** — DeepEval: Plan Quality, Plan Adherence, Tool Correctness, Argument Correctness, Task Completion, Step Efficiency) and returns a clear x-ray.

**The two connected sides:**
- 🧭 **Who uses** → finds the right agent, meets it, learns to ask in the exact format and compares on the maturity ruler
- 🧑‍💻 **Who creates** → catalog inventory, six-metric quality, before × after recipes and evolution tracking

**Technical notes:**
- Vanilla SPA: HTML + CSS (token-based design system) + pure JS, zero dependencies
- Every number derives from the sources — nothing invented
- Accessibility: `:focus-visible`, `aria-current`, `prefers-reduced-motion`
- 100% fictitious data (demo catalog)

---

## 🚀 Como rodar / How to run

```bash
git clone git@github.com:andressafacundo-maker/prisma-agent-xray.git
cd prisma-agent-xray
python3 -m http.server 8080
# 🇧🇷 http://localhost:8080/index.html
# 🇺🇸 http://localhost:8080/index-en.html
```

Ou abra os arquivos diretamente no navegador (file://). / Or open the files directly in the browser (file://).

## 📁 Estrutura / Structure

| Arquivo | Descrição |
|---|---|
| `index.html` | 🇧🇷 versão em português |
| `index-en.html` | 🇺🇸 English version |
| `Futura.ttc` | fonte display local (sem CDN) |
| `docs/screenshots/` | prints de referência |

---

**Live demo:** https://andressafacundo-maker.github.io/prisma-agent-xray/
