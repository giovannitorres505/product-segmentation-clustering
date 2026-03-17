# product-segmentation-clustering
🇺🇸 English Version
Product Segmentation & Clustering


This project applies Unsupervised Machine Learning to group products from the Amazon dataset based on their performance and pricing characteristics.

Project Objective
The goal is to identify distinct patterns in the product catalog using clustering, enabling targeted marketing strategies and inventory optimization.

Methodology

Data Scaling: Applied StandardScaler to normalize features, ensuring that variables with different scales (like price vs. rating) contribute equally to the model.

Algorithm: KMeans Clustering.

Optimization: Used the Elbow Method (WCSS) to determine the ideal number of clusters (3).

Features Used: price, discount_percent, quantity_sold, rating, review_count, and total_revenue.

Clustering Results
The model successfully divided the products into 3 distinct segments:

Segment analysis: Visualization through scatter plots (Price vs. Quantity Sold) reveals how different groups of products behave in the marketplace.


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


🇧🇷 Versão em Português
Segmentação de Produtos e Clustering


Este projeto aplica Aprendizado de Máquina Não Supervisionado para agrupar produtos do dataset da Amazon com base em suas características de desempenho e preço.

Objetivo do Projeto
O objetivo é identificar padrões distintos no catálogo de produtos através de agrupamento (clustering), permitindo estratégias de marketing direcionadas e otimização de estoque.

Metodologia

Esconamento de Dados: Utilização do StandardScaler para normalizar os atributos, garantindo que variáveis com escalas diferentes (como preço vs. avaliação) contribuam igualmente para o modelo.

Algoritmo: KMeans Clustering.

Otimização: Uso do Método Elbow (WCSS) para determinar o número ideal de clusters (3).

Atributos Utilizados: price, discount_percent, quantity_sold, rating, review_count e total_revenue.

Resultados do Agrupamento
O modelo dividiu os produtos com sucesso em 3 segmentos distintos:

Análise de Segmentos: A visualização através de gráficos de dispersão (Preço vs. Quantidade Vendida) revela como diferentes grupos de produtos se comportam no mercado.
