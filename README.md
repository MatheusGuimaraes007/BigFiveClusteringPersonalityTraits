# 🧠 Five Personality Traits – Clusterização de Traços de Personalidade

Este projeto utiliza técnicas de **Machine Learning não supervisionado (K-Means)** para identificar **grupos de personalidade** com base nos cinco grandes traços: Extroversão, Neuroticismo, Amabilidade, Conscienciosidade e Abertura à experiência.

---

## 📊 Objetivo

- Explorar dados psicológicos de indivíduos.
- Agrupar pessoas com perfis semelhantes de personalidade usando **KMeans**.
- Visualizar e interpretar os clusters resultantes.
- Prever em qual grupo um novo indivíduo pode se encaixar.

---

## 🧠 Os 5 Grandes Traços de Personalidade

Este estudo se baseia no modelo conhecido como **Big Five**, que considera os seguintes traços:

1. **Extroversão**
2. **Neuroticismo**
3. **Amabilidade (Agreeableness)**
4. **Conscienciosidade**
5. **Abertura à experiência (Openness)**

---

## 📁 Dataset

Os dados utilizados no projeto estão disponíveis para download no Google Drive:

🔗 [Clique aqui para baixar o arquivo `data-final.csv`](https://drive.google.com/file/d/1f1biExSR9VOpcaJKcePLvR8fAvXEXi3f/view?usp=drive_link)

> ⚠️ **Atenção:** O arquivo tem aproximadamente **397 MB** e não está incluído diretamente no repositório.  
> Após o download, coloque o arquivo `data-final.csv` na **pasta raiz** do projeto.

---

## 🚀 Tecnologias Utilizadas

- Python 3.11
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 🧪 Como executar o projeto

### 1. Clone o repositório:

```bash
git clone https://github.com/MatheusGuimaraes007/BigFiveClusteringPersonalityTraits.git
cd FivePersonalityTraits
```

### 2. Instale as dependências:

#### Opção 1:

```bash
pip install -r requirements.txt
```

#### Opção 2:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Coloque o arquivo de dados na pasta do projeto:

Após baixar o arquivo data-final.csv, mova-o para o diretório principal do projeto.

### 4. Execute o notebook Jupyter:

```bash
jupyter notebook FivePersonalityTraits.ipynb
```
