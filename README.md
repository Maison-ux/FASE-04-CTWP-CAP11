# 📘 FIAP – Faculdade de Informática e Administração Paulista

## 🌾 IR ALÉM: Classificação de Grãos com Machine Learning

Projeto realizado como parte da atividade **"IR ALÉM – Da Terra ao Código"**  
Disciplina: Data Driven Decision Making | Fase 04 · CTWP · Capítulo 11

---

## 🎯 Objetivo

Desenvolver um sistema de **classificação automática de sementes de trigo** utilizando algoritmos de **Machine Learning** aplicados ao **Seeds Dataset** (UCI Repository).  
O projeto segue as etapas do processo CRISP-DM:

1. Análise e exploração dos dados  
2. Treinamento de modelos  
3. Otimização de hiperparâmetros  
4. Avaliação e interpretação dos resultados

---

## 📊 Dataset

**Seeds Dataset** (UCI Machine Learning Repository)  
- 210 amostras de sementes  
- 7 atributos medidos:
  - Área
  - Perímetro
  - Compacidade
  - Comprimento do núcleo
  - Largura do núcleo
  - Coeficiente de assimetria
  - Comprimento do sulco  
- **3 classes (tipos de trigo):**
  - Kama
  - Rosa
  - Canadian

🔗 [Link para o dataset](https://archive.ics.uci.edu/ml/datasets/seeds)

---

## 🧪 Algoritmos Utilizados

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest

📐 Métricas de avaliação:
- Acurácia
- Precisão
- Recall
- F1-Score
- Matriz de Confusão

---

## ⚙️ Etapas do Projeto

### 🟩 Etapa 1 – Análise e Pré-processamento
- Carregamento dos dados do repositório UCI
- Visualizações (histogramas, boxplots, correlação, dispersão)
- Padronização dos atributos com `StandardScaler`
- Nenhum valor ausente encontrado

### 🟩 Etapa 2 – Treinamento dos Modelos
- Divisão dos dados: 70% treino, 30% teste
- Treinamento de KNN, SVM e Random Forest
- Avaliação inicial com métricas quantitativas

### 🟩 Etapa 3 – Otimização de Hiperparâmetros
- Utilização de `GridSearchCV` para ajuste fino dos modelos
- Reavaliação dos modelos com os melhores parâmetros

### 🟩 Etapa 4 – Interpretação e Insights
- Comparação entre desempenho antes e depois da otimização
- Random Forest foi o modelo com melhor equilíbrio entre precisão, recall e acurácia
- Aplicabilidade prática em sistemas de classificação de grãos em ambientes industriais

---

## 📈 Resultados (exemplo)

| Modelo         | Acurácia (Antes) | Acurácia (Depois) |
|----------------|------------------|-------------------|
| KNN            | 91%              | 94%               |
| SVM            | 93%              | 95%               |
| Random Forest  | 94%              | **97%** ✅         |

> ⚠️ Substitua pelos valores reais após executar o notebook!

---

## 🧠 Conclusão

O projeto demonstrou que é possível usar técnicas de aprendizado de máquina para classificar sementes de forma automatizada e eficiente.  
O modelo **Random Forest otimizado** apresentou o melhor desempenho geral.

---

## 🧑‍💻 Execução

1. Abra o notebook `IR_Alem_Seeds_Classification.ipynb` no Google Colab
2. Execute todas as células, de cima para baixo
3. Verifique os resultados e visualize os gráficos
4. (Opcional) Modifique os hiperparâmetros para novos testes

---

## 👥 Integrantes

- Italo Domingues – RM: 561787  
- Maison Wendrel Bezerra Ramos – RM: 565616  
- Jocasta de Kacia Bortolacci – RM: 564730  

---

## 👨‍🏫 Professores

- **Tutor(a)**: Lucas Gomes Moreira  
- **Coordenador(a)**: André Godoi Chiovato

---

## 📜 Licença

Uso educacional. Dados públicos fornecidos pelo UCI Machine Learning Repository.

---

## 🔗 Referências

- https://archive.ics.uci.edu/ml/datasets/seeds  
- https://scikit-learn.org/  
- FIAP – Data Driven Decision Making
