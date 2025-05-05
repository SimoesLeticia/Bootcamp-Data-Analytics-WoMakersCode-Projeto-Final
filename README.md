# Projeto Final • Bootcamp Data Analytics • WoMakersCode

Este repositório contém o projeto final desenvolvido durante o **Bootcamp de Data Analytics da [WoMakersCode](https://womakerscode.org/)**. 

A proposta do projeto foi realizar uma análise completa dos preços de combustíveis no Brasil, utilizando dados públicos disponibilizados pela ANP (Agência Nacional do Petróleo) referentes ao período de 2022 a 2024.

O estudo inclui desde a preparação e exploração dos dados, até análises estatísticas, comparações regionais, investigação de correlações e projeções futuras com o uso de Machine Learning. 

O principal objetivo é gerar insights relevantes sobre a variação dos preços ao longo do tempo e entre as regiões do país, além de estimar os valores esperados para o último quadrimestre de 2024.

---

## 📊 Sobre os Dados

A base de dados utilizada neste projeto é de domínio público e foi disponibilizada pela ANP – Agência Nacional do Petróleo, Gás Natural e Biocombustíveis.

Ela contém informações semanais sobre os preços de revenda de diversos combustíveis no Brasil, incluindo:

- Data da coleta
- Região e estado
- Tipo de combustível
- Preço médio, mínimo e máximo de revenda
- Número de postos pesquisados

O arquivo utilizado foi tratado e consolidado em um CSV (`preco-combustivel-2022-2024.csv`) contendo os dados prontos para análise, abrangendo o período de **janeiro de 2022 até agosto de 2024**.

---

## 📌 O que foi feito

O projeto foi dividido em cinco frentes de análise:

1. **Exploração dos Dados**  
   Limpeza, padronização e análise descritiva da base.

2. **Análise Temporal dos Combustíveis**  
   Evolução dos preços ao longo do tempo, por produto.

3. **Comparação Regional**  
   Identificação de padrões regionais, variações e volatilidade por região.

4. **Correlação entre Preço e Número de Postos Avaliados**  
   Avaliação estatística da relação entre abrangência da pesquisa e preço médio.

5. **Previsão com Machine Learning**  
   Utilização do modelo Prophet para prever o preço do GLP por região no último quadrimestre de 2024.

---

## 🧪 Como visualizar o projeto

Para acessar toda a análise, basta abrir o arquivo Jupyter:

📁 `projeto_final.ipynb`

Nele você encontrará todos os passos, explicações e visualizações geradas ao longo do processo.

Você pode executar o notebook diretamente no Jupyter Notebook, JupyterLab, Google Colab ou VSCode com extensão Python/Jupyter.

---

## 📚 Bibliotecas Usadas

As seguintes bibliotecas Python foram utilizadas ao longo do projeto:

- `pandas` – manipulação e análise de dados
- `numpy` – operações numéricas
- `matplotlib.pyplot` – criação de gráficos
- `seaborn` – visualizações estatísticas mais elegantes
- `logging` – gerenciamento de logs de execução
- `prophet` – modelo de previsão de séries temporais
- `sklearn.metrics` – avaliação do desempenho preditivo (MAE, RMSE)

## Contribuições

Contribuições são sempre bem-vindas! Se você tem sugestões de melhorias, encontrou algum bug ou simplesmente quer dizer "olá 👋🏽", sinta-se à vontade para abrir uma issue ou enviar um pull request.

**Divirta-se aprendendo e analisando dados!** 🚀📊

<a href="https://womakerscode.org"><img src="https://womakerscode.org/wp-content/uploads/2023/05/womakerscode-icone.png" alt="Womakerscode" width="50" height="44"></a>
