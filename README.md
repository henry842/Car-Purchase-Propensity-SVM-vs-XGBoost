# 🚗 Car Purchase Propensity — XGBoost vs SVM

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-Latest-orange?style=flat-square)
![SVM](https://img.shields.io/badge/SVM-Scikit--Learn-F7931E?style=flat-square)
![Status](https://img.shields.io/badge/Status-Concluído-00d4ff?style=flat-square)

**Previsão de propensão à compra de carros com comparação rigorosa entre XGBoost e SVM.**

</div>

---

## 📋 Sobre o Projeto

Projeto de classificação binária para prever a **probabilidade de um cliente comprar um carro** com base em variáveis demográficas e comportamentais. Inclui comparação entre dois algoritmos com diferentes kernels.

---

## 🎯 Objetivo de Negócio

Identificar clientes com alta propensão à compra permite que equipes comerciais priorizem esforços de prospecção, aumentando a taxa de conversão e reduzindo o custo de aquisição.

---

## 🔬 Experimentos Realizados

| Modelo | Configuração | Resultado |
|--------|-------------|-----------|
| XGBoost | Padrão + tuning | ✅ Melhor performance |
| SVM Linear | Kernel linear | Boa separação |
| SVM Polinomial | Kernel poly grau 3 | Ligeiramente inferior |

---

## 📊 Pipeline

```
EDA → Limpeza → Normalização → Modelagem → Comparação → Análise de Erros
```

### Análise Exploratória inclui:
- Distribuição das variáveis por classe
- Matriz de correlação
- Análise de outliers
- Importância das features (XGBoost)

---

## 📈 Métricas de Avaliação

- **Acurácia** — performance geral
- **Precisão / Recall** — equilíbrio entre falsos positivos e negativos
- **F1-Score** — métrica harmônica
- **AUC-ROC** — capacidade discriminativa
- **Matriz de confusão** — análise detalhada de erros

---

## 🛠️ Tecnologias

- **XGBoost** — gradient boosting de alta performance
- **Scikit-Learn** — SVM, métricas, preprocessamento
- **Pandas / NumPy** — manipulação de dados
- **Matplotlib / Seaborn** — visualizações

---

## 🚀 Como Executar

```bash
git clone https://github.com/henry842/CarPurchaseXGBoost.git
cd CarPurchaseXGBoost
pip install -r requirements.txt
jupyter notebook car_purchase.ipynb
```

---

<div align="center">
  <a href="https://github.com/henry842">👤 henry842</a> •
  <a href="https://github.com/henry842?tab=repositories">📂 Outros projetos</a>
</div>
