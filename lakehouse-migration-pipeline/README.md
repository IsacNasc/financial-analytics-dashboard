# 🏗️ Lakehouse Migration Pipeline — SAS → Databricks/PySpark

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-3.5-orange?logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-2.4-blue)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

> Pipeline completo de migração de arquitetura legada (SAS) para Lakehouse moderno (Databricks/PySpark) com camadas **Bronze → Silver → Gold** — resultando em redução de **95% no lead time** de processamento.

---

## 💡 O Problema de Negócio

Ambientes SAS foram construídos para volumes menores e processos mais lentos. No setor financeiro, o crescimento do volume de dados tornou os limites evidentes:

| Problema | Impacto |
|---|---|
| Processamento serial | Jobs de **6 horas** bloqueando análises diárias |
| Sem versionamento | Retrabalho sem possibilidade de rollback |
| Escalabilidade limitada | Impossível acompanhar o crescimento de dados |

---

## 🏗️ Arquitetura

```
FONTE (SAS)     →    BRONZE          →    SILVER           →    GOLD
.sas7bdat            Ingestão bruta       Limpeza +             Agregações
                     + metadados          regras negócio        prontas para BI
                                          + qualidade
```

### Por que Bronze / Silver / Gold?

- **Bronze** — dado exatamente como chegou + rastreabilidade total
- **Silver** — tipagem, validação e features derivadas
- **Gold** — agregações prontas para consumo (Power BI, APIs, relatórios)

---

## 📈 Resultados

| Métrica | Antes (SAS) | Depois (Lakehouse) |
|---|---|---|
| Lead Time | 360 min | ~10 min |
| Redução | — | **-95%** |
| Escalabilidade | Limitada | Horizontal |
| Versionamento | Manual | Delta Time Travel |

---

## 🚀 Como Executar

```bash
pip install pyspark delta-spark pandas pyarrow
jupyter notebook notebooks/lakehouse_pipeline.ipynb
```

---

## 🛠 Stack

`Python` · `PySpark` · `Delta Lake` · `Databricks` · `Pandas` · `NumPy`

---

**Isac Oliveira** · [LinkedIn](https://linkedin.com/in/isac-oliveira-nascimento) · [GitHub](https://github.com/isac-oliveira-nascimento)
