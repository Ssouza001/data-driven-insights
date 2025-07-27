Análise de Vendas de E-commerce (Data-Driven Insights)

Este projeto consiste em uma análise exploratória de dados (EDA) de um conjunto de dados de vendas de uma loja de itens colecionáveis. Utilizando Python e bibliotecas como Pandas, NumPy e Matplotlib, o notebook investiga a estrutura dos dados, extrai KPIs de negócio, analisa o desempenho de produtos e identifica padrões de compra para gerar insights estratégicos.

📖 Sobre o Dataset

O conjunto de dados utilizado é o Sample Sales Data, que contém informações de vendas, pedidos, clientes e envio. Ele foi originalmente criado por María Carina Roldán, membro da comunidade Pentaho, e é ideal para análises de varejo, segmentação de clientes e treinamento em simulação de vendas.

    Fonte: Sample Sales Data no Kaggle: https://www.kaggle.com/datasets/kyanyoga/sample-sales-data?select=sales_data_sample.csv

    Licença: Creative Commons Attribution-Noncommercial-Share Alike 3.0 Unported License.

💡 Principais Insights Gerados no Projeto

A análise contida no notebook revelou os seguintes pontos-chave sobre o negócio:

    Modelo de Negócio B2B: A análise dos nomes dos clientes (ex: "Land of Toys Inc.", "Corporate Gift Ideas Co.") e o alto Ticket Médio de R$ 3.553,89 indicam que a empresa opera principalmente no modelo B2B (business-to-business), focando em vendas para outras empresas.

    Estratégia de Preços Flexível: Ao comparar o preço de tabela (MSRP) com o preço praticado, notou-se que a empresa possui uma política de preços dinâmica. Em algumas vendas, os produtos foram vendidos com descontos significativos, enquanto em outras, o preço final chegou a ser superior ao de tabela, sugerindo negociações caso a caso.

    Concentração de Receita: A categoria "Classic Cars" é a líder absoluta de vendas, gerando quase R$ 4 milhões em faturamento e representando aproximadamente 39% da receita total, o que demonstra uma forte dependência deste nicho.

    Sazonalidade Marcante: O gráfico de evolução de vendas mostrou um padrão sazonal claro, com picos de faturamento expressivos no mês de novembro, indicando que o período de fim de ano é crucial para o desempenho da empresa.

🛠️ Tecnologias Utilizadas

    Python 3.x

    Pandas para manipulação e análise dos dados.

    NumPy para operações numéricas e cálculo de KPIs.

    Matplotlib para a criação das visualizações de dados.

    Google Colab como ambiente de desenvolvimento e apresentação.
