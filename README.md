## Redução de Cancelamentos de Clientes
Este projeto utiliza Python e as bibliotecas Pandas e Plotly para analisar uma base de dados de cancelamentos, identificar os principais gargalos que levam à perda de clientes e propor estratégias de retenção baseadas em dados.
# Contexto
O objetivo principal foi entender por que mais de 50% da base de clientes estava cancelando o serviço e como reduzir esse número através de ações direcionadas.
# Tecnologias Utilizadas
Python 3.x
Pandas: Manipulação e limpeza de dados.
Plotly Express: Visualização de dados e criação de gráficos interativos.
# Principais Insights
Através da análise exploratória, identificamos três gatilhos críticos de cancelamento:
Forma de Pagamento: Clientes no modelo de contrato mensal têm uma taxa de churn muito superior aos demais.
Suporte ao Cliente: Usuários que ligam mais de 4 vezes para o Call Center tendem a cancelar imediatamente.
Inadimplência: Atrasos no pagamento superiores a 20 dias são um forte indicador de cancelamento iminente.
# Resultados
Ao simular a correção desses problemas (migração de contratos mensais para planos mais longos e melhoria na eficiência do suporte/cobrança), a taxa de cancelamento foi reduzida de 56% para 18%.
# Como Executar o Projeto
Clone este repositório.
Certifique-se de ter o arquivo cancelamentos.csv no mesmo diretório.
Instale as dependências:
pip install pandas plotly
Execute o script principal para visualizar as análises e os gráficos gerados.