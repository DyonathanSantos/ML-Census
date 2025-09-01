
# 🧑‍💻 Previsão com Naive Bayes - Censo

Este projeto tem como objetivo treinar um modelo de **Machine Learning** para prever uma variável-alvo (classe) a partir de atributos do **Census Dataset**.  
O modelo escolhido foi o **Naive Bayes** com a distribuição **BernoulliNB**.

---

## 📂 Estrutura do Projeto
- `census.csv` → Dataset usado
- `census.ipynb` → Notebook com o tratamento de dados e modelo
- `census.pkl` → Arquivos serializados (se houver, para reuso dos dados/variáveis)

---

## ⚙️ Etapas do Projeto
1. **Importação dos dados**
   - Carregamento do dataset do Censo.
   
2. **Tratamento e limpeza**
   - Verificação de valores nulos e inconsistências  
   - Codificação de variáveis categóricas (`LabelEncoder`)  
   - Padronização dos dados  

3. **Divisão em treino e teste**
   - 75% treino  
   - 25% teste  

4. **Treinamento do modelo**
   - Modelo utilizado: `BernoulliNB` do `scikit-learn`

5. **Avaliação**
   - Acurácia obtida: **78%**  
   - Relatório de classificação  
   - Matriz de confusão  

---

## 📊 Resultados
O modelo apresentou uma acurácia de **78%**.  
Apesar de simples, o Naive Bayes mostrou resultados satisfatórios para este dataset.  
Possíveis melhorias incluem:
- Testar outros algoritmos (Logistic Regression, Random Forest, SVM)  
- Ajustar hiperparâmetros  
- Balancear as classes (se houver desbalanceamento)

---

## 🚀 Tecnologias
- Python 3.x  
- Pandas  
- Scikit-learn  
- Numpy  
- Matplotlib / Seaborn  

---

## 📌 Como rodar
Clone este repositório e instale as dependências:

```bash
git clone https://github.com/SEU-USUARIO/census-naive-bayes.git
cd census-naive-bayes
pip install -r requirements.txt
```
Execute o Jupyter Notebook:

```bash
jupyter notebook census.ipynb
```
✍️ Autor: Dyonathan Santos
