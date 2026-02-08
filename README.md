# 📊 Análise Estatística de Internações Hospitalares (DATASUS)
# 📊 Statistical Analysis of Hospital Admissions (DATASUS)

---

## 🇧🇷 Descrição do Projeto

Este projeto realiza uma **análise estatística completa** de dados reais de internações hospitalares do Sistema Único de Saúde (SUS), obtidos a partir do DATASUS. O objetivo é aplicar conceitos de estatística descritiva e inferencial utilizando programação em Python, com foco na análise de população e amostras.

Os dados analisados correspondem ao **número de internações hospitalares mensais por município gestor**, no período de **janeiro de 2008 a outubro de 2020**. Trata-se de uma variável **quantitativa discreta**, representando contagens de eventos (internações).

O projeto aborda:
- Estatísticas descritivas da população  
- Análise da distribuição de frequências e simetria  
- Amostragem aleatória em diferentes proporções  
- Comparação entre parâmetros populacionais e estimadores amostrais  
- Simulações para verificação do **Teorema Central do Limite**  
- Construção e avaliação de **intervalos de confiança** para a média  

---

## 🇺🇸 Project Description

This project performs a **complete statistical analysis** of real-world hospital admission data from the Brazilian public health system (DATASUS). The objective is to apply descriptive and inferential statistical concepts using Python programming, focusing on population and sampling analysis.

The dataset represents the **monthly number of hospital admissions per municipality**, covering the period from **January 2008 to October 2020**. It consists of **discrete quantitative data**, representing event counts (hospital admissions).

The project includes:
- Descriptive statistics of the population  
- Frequency distribution and symmetry analysis  
- Random sampling at different proportions  
- Comparison between population parameters and sample estimators  
- Simulations to verify the **Central Limit Theorem**  
- Construction and evaluation of **confidence intervals** for the mean  

---

## 📂 Dados Utilizados
## 📂 Dataset Information

**🇧🇷**
- Fonte: DATASUS (Sistema Único de Saúde – Brasil)  
- Tipo de dado: Quantitativo discreto  
- Variável analisada: Número de internações hospitalares  
- Unidade de análise: Município gestor  
- Periodicidade: Mensal  
- Tamanho da população: 242.603 observações  

**🇺🇸**
- Source: DATASUS (Brazilian Public Health System)  
- Data type: Discrete quantitative  
- Analyzed variable: Number of hospital admissions  
- Unit of analysis: Municipality  
- Frequency: Monthly  
- Population size: 242,603 observations  

---

## 🧮 Análises Realizadas
## 🧮 Performed Analyses

### 🔹 Estatística Descritiva (População)
### 🔹 Descriptive Statistics (Population)

**🇧🇷**
- Número de elementos  
- Média aritmética  
- Variância  
- Desvio padrão  
- Mediana  
- Moda  
- Histogramas da distribuição de frequências  
- Análise da simetria da distribuição  

**🇺🇸**
- Number of elements  
- Arithmetic mean  
- Variance  
- Standard deviation  
- Median  
- Mode  
- Frequency distribution histograms  
- Distribution symmetry analysis  

---

### 🔹 Amostragem com tamanhos variáveis (Parte 2.1)
### 🔹 Sampling with varying sizes (Part 2.1)

**🇧🇷**
- Amostras aleatórias de:
  - 1%
  - 5%
  - 10% da população  
- Cálculo de média, variância, desvio padrão, mediana e moda  
- Comparação entre estatísticas amostrais e populacionais  
- Histogramas das distribuições amostrais  

**🇺🇸**
- Random samples of:
  - 1%
  - 5%
  - 10% of the population  
- Computation of mean, variance, standard deviation, median, and mode  
- Comparison between sample statistics and population parameters  
- Histograms of sample distributions  

---

### 🔹 Amostragem com tamanho fixo (Parte 2.2)
### 🔹 Fixed-size sampling (Part 2.2)

**🇧🇷**
- Geração de 100 amostras com tamanho fixo (1% da população)  
- Cálculo da esperança das médias, variâncias e desvios padrão amostrais  
- Análise da soma das amostras  
- Verificação empírica do **Teorema Central do Limite**  
- Construção de intervalos de confiança (95%) para a média  
- Avaliação da cobertura do intervalo de confiança  

**🇺🇸**
- Generation of 100 samples with fixed size (1% of the population)  
- Estimation of the expected value of sample means, variances, and standard deviations  
- Analysis of the sum of the samples  
- Empirical verification of the **Central Limit Theorem**  
- Construction of 95% confidence intervals for the mean  
- Evaluation of confidence interval coverage  

---

## 📈 Principais Conclusões
## 📈 Main Conclusions

**🇧🇷**
- A distribuição da população apresenta forte assimetria à direita, não sendo aproximadamente normal.  
- À medida que o tamanho da amostra aumenta, as estatísticas amostrais se aproximam dos parâmetros populacionais.  
- A distribuição da soma das amostras tende a uma forma aproximadamente normal, conforme previsto pelo Teorema Central do Limite.  
- A cobertura empírica dos intervalos de confiança evidencia limitações práticas da aproximação normal em populações altamente assimétricas.  

**🇺🇸**
- The population distribution shows strong right skewness and is not approximately normal.  
- As sample size increases, sample statistics converge to population parameters.  
- The distribution of the sum of samples tends toward an approximately normal shape, as predicted by the Central Limit Theorem.  
- The empirical coverage of confidence intervals highlights practical limitations of the normal approximation for highly skewed populations.  

---

## 🛠️ Tecnologias Utilizadas
## 🛠️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- SciPy  

---

## 📁 Estrutura do Repositório
## 📁 Repository Structure

