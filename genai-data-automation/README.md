# 🤖 GenAI Data Automation — Databricks Genie & Copilot

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-1.5_Flash-4285F4?logo=google&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-Genie-FF3621?logo=databricks&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

> Automação de tarefas analíticas repetitivas com IA Generativa: geração de SQL, documentação de pipelines e relatórios de qualidade de dados — demonstrando os mesmos conceitos do **Databricks Genie** via API.

---

## 💡 O Problema de Negócio

Engenheiros de dados gastam tempo excessivo em tarefas repetitivas que não agregam valor intelectual:

| Tarefa | Tempo Manual | Com GenAI |
|---|---|---|
| Escrever 3 queries SQL | ~30 min | ~10 seg |
| Documentar pipeline | ~45 min | ~15 seg |
| Relatório de qualidade | ~20 min | ~10 seg |

---

## 🔬 3 Casos de Uso

### Caso 1 — Geração de SQL via Linguagem Natural
Engenheiro descreve o que precisa em português → LLM gera SQL otimizado para Spark SQL com comentários.

### Caso 2 — Documentação Automática de Pipelines
PySpark code → Documentação técnica estruturada em Markdown com inputs, outputs e observações.

### Caso 3 — Relatório de Qualidade de Dados
Métricas de qualidade → Relatório executivo classificado (Excelente/Boa/Regular/Crítica) com ações corretivas.

---

## 🔗 Relação com Databricks Genie

Este projeto usa a **Gemini API** como proxy para demonstrar os mesmos princípios que o Databricks Genie aplica nativamente dentro da plataforma:
- NL → SQL com contexto do catálogo de dados
- Documentação automática de notebooks
- Análise de qualidade via linguagem natural

---

## 🚀 Como Executar

```bash
pip install google-generativeai pandas
export GEMINI_API_KEY="sua_chave"  # aistudio.google.com (gratuito)
jupyter notebook notebooks/genai_automation.ipynb
```

> Sem API Key: roda em modo simulado com outputs pré-computados.

---

## 🛠 Stack

`Python` · `Google Gemini API` · `Prompt Engineering` · `Databricks Genie` · `Pandas`

---

**Isac Oliveira** · [LinkedIn](https://linkedin.com/in/isac-oliveira-nascimento) · [GitHub](https://github.com/isac-oliveira-nascimento)
