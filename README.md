# Repositório do Projeto de Previsão de Ações

Este repositório contém um script Python chamado `app.py` que permite aos usuários coletar e visualizar os dados de ações financeiras, bem como realizar previsões para o período desejado. O script utiliza diversas bibliotecas Python para tornar a experiência completa e informativa.

<p> Acesse em: https://preditiva-acoes.streamlit.app/</p>

<div align="center">
    <img src="https://github.com/catianemarinho/analise_preditiva_acoes/assets/97571709/915af182-8ab4-401e-a43d-9b59966c77ff">
</div>

## Funcionalidades

- Coleta de Dados de Ações: O script utiliza a biblioteca `yfinance` para coletar dados históricos de ações. Os usuários podem escolher entre as ações cadastradas e definir o período de início e término para a coleta dos dados.

- Previsões de Médio Prazo: O script utiliza a biblioteca `prophet` para realizar previsões de médio prazo para as ações selecionadas. Os usuários podem escolher quantos meses de previsão desejam visualizar, variando de 1 a 24 meses.

## Como Usar

1. Certifique-se de ter as bibliotecas necessárias instaladas. Você pode instalá-las executando o seguinte comando:

   ```bash
   pip install -r requirements.txt
2. Execute o script `app.py`:

   ```bash
   streamlit run app.py
3. A interface Streamlit será aberta em seu navegador. Lá, você poderá selecionar a ação desejada, definir o período de início e término para a coleta de dados, e escolher o número de meses de previsão.

## Bibliotecas utilizadas

- `streamlit`: Biblioteca para criar interfaces de usuário interativas e compartilháveis.

- `yfinance`: Biblioteca para coletar dados financeiros, incluindo preços históricos de ações.

- `prophet`: Biblioteca para análise de séries temporais e previsões de dados temporais.

- `plotly`: Biblioteca para criar gráficos interativos.

## Contribuição

Se você deseja contribuir para este projeto, fique à vontade para abrir uma issue ou enviar um pull request. Todas as contribuições são bem-vindas!

## Nota

Lembre-se de que os dados financeiros são voláteis e podem mudar rapidamente. As previsões fornecidas pelo script não garantem resultados precisos e são apenas para fins informativos.
