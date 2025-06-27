# Estratégias de Interpolação Espacial para Análise de Medidas Climáticas no Contexto de Energias Renováveis

**Autor:** Rafael Abreu de Carvalho

**Orientador:** Diego de Freitas Bezerra

---

## 📖 Sobre o Projeto

Apresentado e aprovado em 19 de junho de 2025 como requisito para a obtenção do título de Bacharel em Ciência da Computação pela CESAR School, este trabalho investiga e avalia diferentes estratégias de interpolação espacial para estimar variáveis climáticas em regiões com poucas estações meteorológicas. O foco da análise é a viabilidade de projetos de energia renovável, especialmente eólica e solar, no estado de Pernambuco.

O estudo utiliza dados de 12 estações do Instituto Nacional de Meteorologia (INMET) para analisar variáveis como velocidade do vento, radiação solar e temperaturas. Foram aplicadas e comparadas três principais técnicas de interpolação: **IDW (Inverso do Quadrado da Distância)**, **Krigagem** e **Random Forest**, com os resultados validados a partir de dados de usinas reais. A pesquisa conclui que a interpolação, especialmente o método IDW, é uma ferramenta estratégica e técnica valiosa para o planejamento energético sustentável, fornecendo dados precisos em locais com baixa densidade de medições.

---

## 🎯 Objetivos

### Objetivo Geral
Avaliar estratégias de interpolação espacial aplicadas a medidas climáticas para análise de viabilidade de projetos de energias renováveis, com foco especial em energia solar e eólica.

### Objetivos Específicos
* Identificar as principais técnicas de interpolação espacial utilizadas na análise de dados climáticos.
* Avaliar o desempenho dessas técnicas em áreas com distribuição desigual de estações meteorológicas.
* Analisar o potencial de uma região para geração de energia renovável com base nos dados interpolados.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

* **Linguagem:** Python
* **Bibliotecas Principais:**
    * Pandas
    * NumPy
    * Scikit-learn (para os modelos de Krigagem e Random Forest)
    * Matplotlib e Seaborn (para visualização de dados)
    * Folium (para criação de mapas interativos)
* **Ambiente:** Google Colab / Jupyter Notebook

---

## 🚀 Como Executar o Projeto

O código-fonte da análise está disponível no notebook Jupyter `TCC.ipynb`. Para executá-lo, siga os passos abaixo:

1.  **Clone o repositório:**
    ```sh
    git clone https://github.com/RafaCarvalh0/Trabalho-de-Conclusao-de-Curso.git
    ```

2.  **Ambiente de Execução:**
    * É recomendado utilizar o **Google Colab** para abrir e executar o arquivo `TCC.ipynb`, pois ele já possui a maioria das bibliotecas necessárias pré-instaladas.
    * Caso execute localmente, certifique-se de ter o Python e as bibliotecas listadas acima instaladas.

3.  **Estrutura de Dados:**
    * O notebook utiliza dados do INMET que devem estar organizados em uma estrutura de pastas específica no Google Drive, conforme indicado no código e disponível para download na pasta zipada.
    * O código realiza a limpeza de *outliers* e dados faltantes antes de prosseguir com a análise.

4.  **Execução do Notebook:**
    * Abra o `TCC.ipynb` e execute as células em ordem. O notebook está dividido em seções claras:
        1.  Carregamento e tratamento da base de dados.
        2.  Análise e remoção de outliers.
        3.  Aplicação das técnicas de interpolação (IDW, Krigagem e Random Forest) através de um processo de validação cruzada *Leave-One-Out*.
        4.  Cálculo dos erros (MSE, RMSE, MAE) para cada modelo.
        5.  Criação de visualizações e mapas para os resultados.

---

## 🔑 Palavras-Chave

Modelos Híbridos, Aprendizado Supervisionado, Análise Geoespacial, Viabilidade Energética.