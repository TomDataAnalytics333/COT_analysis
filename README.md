# Análise de Estratégias para Forex usando Sinais do Commitment of Traders Report

Este projeto visa avaliar a viabilidade de estratégias de negociação no mercado Forex com base nos sinais obtidos do Commitment of Traders (COT) report. O objetivo é testar se os dados do COT podem fornecer insights valiosos para a negociação de pares de moedas.

## Funcionalidades

1. **Download e Extração de Dados**
   - Baixa e extrai dados históricos do COT report de vários anos.
   - Renomeia e organiza arquivos extraídos para fácil acesso.

2. **Processamento de Dados**
   - Filtra e processa os dados do COT para focar em moedas e colunas relevantes.
   - Adiciona colunas de posições líquidas para análises adicionais.

3. **Análise de Dados**
   - Seleciona e filtra dados de acordo com a moeda e categoria desejadas.
   - Cria visualizações como box plots e séries temporais para análise.

4. **Integração com Dados de Forex**
   - Obtém dados históricos de Forex para pares de moedas específicos.
   - Mescla dados do COT com dados de preços Forex, considerando atrasos na publicação do COT.

5. **Geração de Sinais de Compra e Venda**
   - Insere sinais de compra e venda nos dados de preços baseados em condições especificadas.
   - Calcula o impacto dos sinais e testa estratégias com base em take profit e take loss.

6. **Visualização e Avaliação de Resultados**
   - Cria gráficos para visualizar a evolução das negociações e resultados dos testes.
   - Fornece métricas como aproveitamento, média de dias para vitórias/derrotas, e retorno sobre investimento.

## Requisitos

- Python 3.x
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`, `requests`, `zipfile`, `yfinance`

Instale as dependências necessárias usando o `pip`:

```bash
pip install pandas numpy matplotlib seaborn requests yfinance
