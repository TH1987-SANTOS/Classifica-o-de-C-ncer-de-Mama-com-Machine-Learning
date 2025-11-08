# cancer_classification_ml

## 🩺 Classificação de Câncer de Mama com Machine Learning

### 🎯 Resumo

Projeto de exemplo que treina e compara modelos de classificação (Regressão Logística e Random Forest) para prever se um tumor é **benigno** ou **maligno** a partir do dataset *Breast Cancer Wisconsin (Diagnostic)*. O notebook inclui pré-processamento, seleção de features, treinamento, avaliação e visualizações.

---

## 📁 Estrutura do repositório

```
cancer_classification_ml/
├─ README.md
├─ requirements.txt
├─ cancer_classification_ml.ipynb
├─ data/ 
│  └─cancer_data.csv

```

---

## 📦 Bibliotecas principais

* pandas
* numpy
* matplotlib
* scikit-learn

---

## 🧭 Objetivo

Construir um pipeline de classificação que permita comparar modelos (Regressão Logística e Random Forest) e escolher o mais adequado para o problema, dando ênfase à minimização de **falsos negativos** (impacto clínico maior).

---

## 🧾 Dataset

* **Nome:** Breast Cancer Wisconsin (Diagnostic)
* **Fonte:** Kaggle
* **Variável alvo:** `diagnosis` / `alvo` (Benigno / Maligno)

---

## 🛠️ Como executar (local)

1. Clone este repositório:

```bash
git clone https://github.com/<seu-usuario>/cancer_classification_ml.git
cd cancer_classification_ml
```

2. Crie um ambiente virtual (recomendado):

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate
```

3. Instale dependências:

```bash
pip install -r requirements.txt
```

4. Abra o notebook no Jupyter:

```bash
jupyter notebook Projeto_Cancer_Mama.ipynb
```

---

## 🚀 O que o notebook contém

* Carregamento e inspeção dos dados
* Limpeza e pré-processamento (mapeamento da variável alvo, tratamento de outliers e missing values se houver)
* Análise exploratória: distribuição da variável alvo, estatísticas descritivas, top features correlacionadas
* Pipelines de treinamento para:

  * Regressão Logística (com StandardScaler)
  * Random Forest Classifier
* Avaliação: Acurácia, Recall, Precision, F1-score, Matriz de Confusão, Curva ROC e AUC
* Comparação entre modelos e discussão sobre trade-offs

