# 💸 Análise de Dados Financeiros com Python

## 🔖 Descrição
Este projeto realiza uma análise de dados financeiros de grandes bancos brasileiros e do Índice Bovespa utilizando a biblioteca `yfinance`. O objetivo é visualizar a evolução das cotações, calcular retornos diários e analisar a correlação entre os ativos.

## 📌 Bibliotecas Utilizadas
As seguintes bibliotecas são utilizadas no projeto:
- `yfinance`: Para obter dados financeiros.
- `pandas`: Para manipulação de dados.
- `numpy`: Para operações matemáticas.
- `matplotlib.pyplot`: Para visualização de dados.
- `seaborn`: Para gerar gráficos estatísticos.
- `warnings`: Para suprimir avisos desnecessários.

## 🔄 Instalação
Antes de rodar o código, instale as dependências executando:
```bash
!pip install yfinance --upgrade --no-cache-dir
```

## 📥 Coleta de Dados
O código baixa dados históricos desde 2008 para os seguintes ativos:
- **ITUB3.SA** (Itaú Unibanco)
- **BBDC3.SA** (Bradesco)
- **BBAS3.SA** (Banco do Brasil)
- **SANB3.SA** (Santander Brasil)
- **^BVSP** (Ibovespa)

Os dados são armazenados em um `DataFrame` e renomeados para facilitar a análise. O índice Bovespa é ajustado para valores em milhares.

## 📊 Visualização de Dados
### Cotação x Tempo
Um gráfico de linha é gerado para visualizar a evolução dos preços ao longo do tempo.

### Médias Móveis
Um gráfico é criado para mostrar a cotação diária do **ITUB3** juntamente com suas médias móveis trimestral e anual.

### Correlação entre Ativos
Uma matriz de correlação é gerada utilizando um heatmap para visualizar a relação entre os ativos.

## 🧮 Cálculo de Retornos
Os retornos diários dos ativos são calculados e analisados por meio de:
- **Pairplot:** Para identificar padrões e relações entre os retornos.
- **Estatísticas descritivas:** Para entender distribuições e variabilidade.
- **Distribuição do Retorno do IBOV:** Um histograma é criado para visualizar a distribuição dos retornos do Índice Bovespa.

## ↪ Retorno Acumulado
Um gráfico de linhas exibe a evolução do retorno acumulado ao longo do tempo para cada ativo.

## ✅ Como Usar
1. Execute o script no Google Colab ou em um ambiente Python.
2. Verifique os gráficos gerados para entender a evolução dos ativos.
3. Utilize os cálculos de retorno para tomar decisões baseadas em dados.

## 📄 Licença
Este projeto foi desenvolvido para fins educacionais e de análise de dados financeiros.
