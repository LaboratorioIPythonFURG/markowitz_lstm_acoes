# Fronteira Eficiente de Markowitz com Simulação de Monte Carlo e LSTM em Python

Repositório contendo a implementação computacional do trabalho apresentado no **XLIV Congresso Nacional de Matemática Aplicada e Computacional (CNMAC)**.

## Autores
- **Luís F. S. Souza** (UFPel / FURG)
- **Régis S. de Quadros** (UFPel)
- **Bárbara D. do A. Rodriguez** (FURG)
- **Cristiana A. Poffal** (FURG)
- **Adilson da S. Nunes** (FURG)

## Resumo do Trabalho
Este projeto apresenta uma aplicação combinada do modelo média-variância de **Markowitz** com previsões por redes neurais ***Long Short-Term Memory* (LSTM)** para a construção da fronteira eficiente de carteiras de investimento em Python.

A geração e avaliação de carteiras foi realizada por **Simulação de Monte Carlo**, por amostragem aleatória de 10.000 portfólios factíveis para mapear o espaço risco-retorno sob o Índice de Sharpe.

## Conteúdo do Repositório
- markowitz_monte_carlo_lstm.ipynb: *Jupyter Notebook* completo com a extração de dados via yfinance, modelagem LSTM com TensorFlow/Keras, simulação de Monte Carlo e construção das fronteiras eficientes.
