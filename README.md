# Dashboard de Análise de Salários na Área de Dados

Este é um dashboard interativo criado com Streamlit para analisar salários na área de dados. A aplicação permite que os usuários explorem dados salariais, aplicando filtros por ano, nível de senioridade, tipo de contrato e tamanho da empresa.

## 📊 Funcionalidades

* **Métricas Gerais:** Visualize o salário médio, salário máximo, o número total de registros e o cargo mais frequente com base nos filtros aplicados.
* **Filtros Interativos:** Refine a análise com filtros por:
    * Ano
    * Senioridade (Júnior, Pleno, Sênior, etc.)
    * Tipo de Contrato (CLT, PJ)
    * Tamanho da Empresa
* **Visualizações Gráficas:**
    * **Top 10 Cargos:** Gráfico de barras com os 10 cargos que possuem a maior média salarial.
    * **Distribuição de Salários:** Histograma que mostra a distribuição dos salários anuais.
    * **Proporção de Tipos de Trabalho:** Gráfico de pizza que detalha a proporção entre trabalho remoto, híbrido e presencial.
    * **Média Salarial por País:** Mapa interativo (choropleth) que exibe a média salarial para Cientistas de Dados em diferentes países.
* **Dados Detalhados:** Uma tabela interativa que exibe os dados brutos filtrados.

## 🚀 Tecnologias Utilizadas

* **Python**
* **Streamlit:** Para a criação do dashboard interativo.
* **Pandas:** Para manipulação e análise dos dados.
* **Plotly:** Para a criação dos gráficos.

## ⚙️ Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/Alan-Franca/DashBoard-Empresarial.git](https://github.com/Alan-Franca/DashBoard-Empresarial.git)
    ```

2.  **Navegue até o diretório do projeto:**
    ```bash
    cd seu-repositorio
    ```

3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Execute a aplicação Streamlit:**
    ```bash
    streamlit run app.py
    ```

5.  Abra o seu navegador e acesse o endereço fornecido no terminal (geralmente `http://localhost:8501`).

## 📄 Fonte dos Dados

Os dados utilizados neste dashboard foram obtidos a partir do seguinte arquivo CSV: `https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv`.
