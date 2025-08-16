Análise de Evasão de Clientes (Churn) da TelecomX

Este notebook contém uma análise exploratória dos dados de clientes da TelecomX com o objetivo de identificar padrões associados à evasão de clientes (Churn).

A análise realizada neste notebook compreende as seguintes etapas:

- Extração e Limpeza de Dados: Carregamento dos dados, combinação de estruturas aninhadas, renomeação de colunas, tratamento de valores nulos e "falso nulos".
- Transformação de Dados: Criação de novas colunas (ex., cobranças diárias) e conversão de tipos de dados.
- Análise Exploratória:
  - Comparativo entre clientes idosos e jovens em relação a tempo de permanência e cobranças.
  - Análise da distribuição de clientes e taxas de cancelamento por gênero.
  - Comparativo entre clientes com pacote de serviços completo e incompleto e suas taxas de cancelamento.
  - Identificação dos métodos de pagamento mais comuns entre clientes que cancelaram.
  - Determinação do grupo com a maior taxa de cancelamento.
- Visualizações: Geração de gráficos (barras, histogramas) para ilustrar os principais achados.
- Relatório Final: Compilação das descobertas, conclusões e recomendações.

Para executar este Notebook faça as seguintes etapas:
1. Abra o notebook em um ambiente Python com as bibliotecas necessárias instaladas (pandas, numpy, matplotlib).
2. Execute as células sequencialmente para replicar a análise.
