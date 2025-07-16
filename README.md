# 🚢 Projeto Titanic - Classificação de Sobrevivência

Este projeto de Data Science tem como objetivo prever a sobrevivência de passageiros a bordo do navio Titanic, utilizando aprendizado de máquina (Machine Learning) e técnicas modernas de pré-processamento de dados com `scikit-learn`.

---

## 📌 Objetivos do Projeto

- Realizar **análise exploratória** de dados reais.
- Tratar dados faltantes e variáveis categóricas.
- Criar uma **pipeline robusta** de pré-processamento.
- Treinar e avaliar um modelo de classificação com **Random Forest**.
- Aplicar **GridSearchCV** para otimizar hiperparâmetros.
- Gerar métricas como Acurácia, Precisão, Recall, F1-Score e AUC.

---

## 🧠 Tecnologias e Bibliotecas Utilizadas

- `Python`
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn` (pipeline, imputer, encoder, modelo e métricas)

---

## 📊 Etapas do Projeto

1. **Importação de Dados**  
   Dados públicos do Titanic disponíveis no [repositório do Data Science Dojo](https://github.com/datasciencedojo/datasets).

2. **Análise Exploratória**  
   - Verificação de tipos e valores nulos
   - Entendimento das variáveis mais relevantes
   - Exclusão de colunas irrelevantes como `Cabin`, `Name`, `Ticket`

3. **Pré-processamento com Pipeline**
   - **Numéricas**: imputação de valores ausentes e padronização com `StandardScaler`
   - **Categóricas**: imputação e codificação com `OneHotEncoder`
   - Colunas como `Pclass` foram mantidas diretamente

4. **Modelagem**
   - Divisão da base (`train_test_split`)
   - Treinamento com **RandomForestClassifier**
   - Ajuste fino com **GridSearchCV**

5. **Avaliação do Modelo**
   - Métricas de performance:
     - `accuracy_score`
     - `precision_score`
     - `recall_score`
     - `f1_score`
     - `roc_auc_score`
   - Visualização com matriz de confusão

---

## ✅ Resultados

O modelo final foi avaliado com diversas métricas e obteve desempenho satisfatório, mostrando boa capacidade preditiva para a tarefa de classificação binária (sobreviveu ou não).

---

## 📂 Como executar

1. Acesse o notebook via Google Colab:  
   [🔗 Notebook no Colab](COLE_AQUI_SEU_LINK_DO_COLAB)

2. Ou clone o repositório e rode localmente:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
