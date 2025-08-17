# AluraStore

Alura Store - Análise de Vendas e Desempenho de Lojas
📌 Sobre o Projeto

O Alura Store é um desafio de Data Science que consiste em analisar os dados de vendas de quatro lojas de um e-commerce fictício para ajudar o Sr. João a decidir qual loja vender.

O objetivo é identificar a loja com menor desempenho, usando métricas de faturamento, avaliação de clientes, custo médio do frete e popularidade dos produtos e categorias.

O projeto utiliza Python, pandas, matplotlib e técnicas de análise de dados para gerar insights claros sobre cada loja.

🛠 Tecnologias e Bibliotecas Utilizadas

Python 3.x – Linguagem de programação

pandas – Manipulação e análise de dados

matplotlib – Visualização de dados

numpy – Operações numéricas

📊 Métricas Analisadas

Para cada loja, o código calcula:

Faturamento Total – Soma de todas as vendas da loja.

Média de Avaliação – Média das notas atribuídas pelos clientes.

Custo Médio do Frete – Média do valor pago pelo frete em cada pedido.

Produtos Mais e Menos Vendidos – Top 3 produtos mais vendidos e 3 produtos com menor venda.

Categoria Mais Popular – Categoria de produto mais vendida e percentual de participação.

Além disso, o código cria um score combinado ponderando essas métricas para identificar a loja com pior desempenho.

📈 Visualizações

O projeto gera três gráficos principais:

Comparativo de Faturamento e Avaliação

Gráfico de barras lado a lado mostrando o faturamento total e a média de avaliação por loja.

Relação entre Custo Médio do Frete e Faturamento

Gráfico de dispersão mostrando a relação entre custo do frete e faturamento, ajudando a identificar padrões.

Distribuição das Categorias Mais Vendidas

Gráfico de pizza mostrando a proporção das categorias mais vendidas entre todas as lojas.

💻 Como Executar

Clone este repositório ou baixe os arquivos.

Certifique-se de ter o Python 3 instalado.

Instale as bibliotecas necessárias:

pip install pandas matplotlib numpy


Execute o código no Google Colab ou em outro ambiente Python.

Os dados das lojas são carregados diretamente do GitHub, portanto não é necessário ter os CSVs localmente.

Analise os gráficos e os resultados impressos no console para identificar a loja com menor desempenho.

📝 Resultados Esperados

Ao executar o código, você verá:

Ranking das lojas (da pior para a melhor), com base no score combinado.

Detalhes da loja com pior desempenho, incluindo faturamento, avaliação média, custo médio de frete, categoria mais vendida e top 3 produtos.

⚡ Observações

O código lida automaticamente com variações no nome da coluna de quantidade (Quantidade ou Quantidade de parcelas).

Os pesos do score (faturamento 50%, avaliação 30%, frete 20%) podem ser ajustados conforme necessidade.

📌 Conclusão

Este projeto demonstra como a análise de dados e a visualização gráfica podem auxiliar na tomada de decisões estratégicas em negócios. Ele pode ser facilmente expandido para incluir mais métricas, lojas ou produtos.
