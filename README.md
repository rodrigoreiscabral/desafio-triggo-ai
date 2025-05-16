# Teste Técnico - Programa Trainee triggo.ai de Excelência em Engenharia de Dados e DataOps 2025

Este projeto faz parte do Teste Técnico para o Programa de Excelência em Engenharia de Dados e DataOps 2025 da triggo.ai, utilizando o dataset da Olist, que contém dados detalhados do e-commerce brasileiro. Para executar o projeto, basta realizar o upload do arquivo desafio-triggo-ai.ipynb no Google Colab.

## Preparação e Integração dos Dados
Foram carregados e limpos diversos arquivos, removendo duplicatas e valores nulos, para construir um modelo relacional que serviu de base para as análises.

## Análise Exploratória
Identificou-se uma sazonalidade clara nas vendas, com pico em novembro e dezembro. O tempo médio de entrega ficou em torno de 10 dias, com variações significativas. O valor do frete mostrou correlação moderada com a distância, e as categorias “health_beauty”, “watches_gifts” e “bed_bath_table” foram as que mais faturaram. Estados do Norte e Nordeste apresentaram tickets médios mais altos, possivelmente devido a custos logísticos.

## Soluções de Negócio
- **Retenção de Clientes**: Apenas 3% dos clientes compraram mais de uma vez, indicando oportunidade para estratégias de fidelização.

- **Predição de Atrasos**: Modelo Random Forest com 96% de acurácia foi criado para prever atrasos nas entregas, embora com maior dificuldade para identificar entregas atrasadas.

- **Segmentação de Clientes**: Quatro grupos distintos foram identificados com base em comportamento de compra, permitindo ações de marketing mais direcionadas.

## Conclusão
O projeto demonstrou como dados podem guiar melhorias estratégicas no e-commerce, destacando oportunidades em fidelização, logística e personalização. Futuras análises podem aprofundar previsões e otimizar ainda mais a operação.
