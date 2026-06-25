# E-commerce Analytics & Clustering: Olist Dataset 🇧🇷

##  Sobre o Projeto
Este repositório contém o pipeline completo de dados para a análise e clusterização de informações públicas do e-commerce brasileiro (Olist). O objetivo principal é integrar conceitos de mineração de dados, análise exploratória (EDA), medidas de similaridade e algoritmos de aprendizado não supervisionado na resolução de problemas reais de negócios, como segmentação de clientes e regras de associação.

**Contexto Acadêmico:** Projeto desenvolvido para a disciplina de Ciência de Dados 2 do curso de Sistemas de Informação da Universidade Federal de Uberlândia (UFU).

**Autor(es):**
* Caio Cusinato Figueiredo
* Diego Marques Amorim
* Gabriel Andrade Lima de Freitas
* Ítalo Nunes Tillmann de Abreu
* Pedro henrique Salles dos Santos
---

## ⚙️ Arquitetura e Entregas do Pipeline

O projeto foi estruturado em quatro etapas progressivas:

### 1. Coleta e Pré-processamento (Etapa 1)
* **Objetivo:** Aquisição dos dados, tratamento de valores faltantes e limpeza.
* **Técnicas:** Normalização/Padronização (StandardScaler/MinMaxScaler), remoção de outliers e transformações iniciais.
* 🎥 Link para o Vídeo de Apresentação da Etapa 1: https://youtu.be/X8DCP4WdYHw

<<<<<<< HEAD
### 📊 2. Análise Exploratória de Dados - EDA (Etapa 2)
* **Objetivo:** Compreensão da distribuição dos dados e extração de padrões preliminares.
* **Técnicas:** Estatísticas descritivas, Boxplots/Histogramas (Escala Log), Correlação de Spearman e Redução de Dimensionalidade (PCA).
* 🎥 **[Link para o Vídeo de Apresentação da Etapa 2](insira-o-link-aqui)**
=======
### 2. Análise Exploratória de Dados - EDA (Etapa 2)
* **Objetivo:** Compreensão do comportamento das variáveis e redução de dimensionalidade.
* **Técnicas:** Estatísticas descritivas, matriz de correlação, visualizações (histogramas, boxplots) e aplicação de PCA/t-SNE/UMAP.
* 🎥 Link para o Vídeo de Apresentação da Etapa 2: https://youtu.be/GVDpzHv1ncQ
>>>>>>> 786f9a3c098ed8eb30ac66434cd6bd55b021d5d3

### 3. Clusterização e Avaliação (Etapa 3)
* **Objetivo:** Agrupamento não supervisionado dos dados.
* **Algoritmos Testados:** K-Means, Clustering Hierárquico e DBSCAN.
* **Métricas:** Silhouette Score, Davies-Bouldin, Calinski-Harabasz e testes de estabilidade (Adjusted Rand Index).
* 🎥 [Link para o Vídeo de Apresentação da Etapa 3]

### 4. Padrões Frequentes e Conclusões (Etapa 4)
* **Objetivo:** Mineração de regras de associação e documentação final.
* **Técnicas:** Algoritmos Apriori/FP-Growth.
* 📄 [Link para o Relatório Técnico em PDF]
* 📊 [Link para os Slides da Apresentação Final]

---

##  Como Reproduzir o Projeto

Para executar as análises e reproduzir os resultados deste repositório na sua máquina, siga os passos abaixo:

**1. Clone o repositório:**
```bash
git clone https://github.com/Gab-Andrade/Minera-o-de-dados---E-commerce-e-comportamento-de-compra.git
cd Minera-o-de-dados---E-commerce-e-comportamento-de-compra
```

## 🗂️ Base de Dados

Devido ao tamanho dos arquivos e às boas práticas de versionamento (Git), a base de dados original não foi enviada para este repositório. 

Para reproduzir as análises, faça o download do dataset público no Kaggle:
* 🔗 **[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)**

Após o download, extraia os arquivos e insira-os dentro da pasta `data/raw/` na raiz do projeto.
