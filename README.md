# 📊 Financial Analytics Dashboard — PySpark + Power BI

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-3.5-orange?logo=apachespark&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-DAX-yellow?logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

> Pipeline analítico que processa indicadores comerciais financeiros em larga escala com PySpark e entrega dashboards executivos — eliminando **65% do esforço manual** da equipe.

---

## 💡 O Problema de Negócio

A área comercial precisava de indicadores atualizados diariamente. O processo manual envolvia extração no Teradata → consolidação em Excel → atualização manual de dashboards. Resultado: **3-4h de trabalho analítico repetitivo** todo dia, com alto risco de erro humano.

---

## 🔬 Pipeline

```
Teradata/SQL Server  →  PySpark (ETL)  →  Delta Tables  →  Power BI  →  Gestão
```

### O que o pipeline entrega

- **Performance por Canal** — receita, meta, atingimento e gap por canal de venda
- **Mix por Regional** — distribuição de produto e volume por região
- **Ranking de Vendedores** — top performers com score de atingimento de meta

---

## 📈 Resultados

| Indicador | Valor |
|---|---|
| Receita Processada | R$ 21+ Bilhões |
| Registros Analisados | 200K+ operações |
| Redução de Esforço Manual | **-65%** |
| Canais Monitorados | 4 |
| Regionais | 5 |

---

## 🚀 Como Executar

```bash
pip install pyspark pandas matplotlib
jupyter notebook notebooks/financial_dashboard.ipynb
```

---

## 🛠 Stack

`Python` · `PySpark` · `SQL` · `Pandas` · `Matplotlib` · `Power BI (DAX)` · `Teradata`

---

**Isac Oliveira** · [LinkedIn](https://linkedin.com/in/isac-oliveira-nascimento) · [GitHub](https://github.com/isac-oliveira-nascimento)
