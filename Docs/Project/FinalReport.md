<p align="center">
 <img src="https://github.com/AlexanderVieira/EcommerceAnalytics/blob/master/infnet.png" width="150" >
</p>

  <h3 align="center">INSTITUTO INFNET</h3>

  <p align="center">
    <strong>ENGENHARIA DE COMPUTAÇÃO</strong>
    <br>
    <strong>ALEXANDER VIEIRA DA SILVA</strong>
    <br>
    <strong>PROJETO DE BLOCO: IoT e DATA SCIENCE</strong>
    <br>
    <strong>2022</strong>
  </p>
</p>

****

- [RESUMO](#resumo)
- [1 INTRODUÇÃO](#1-introdução)
- [1.1 MOTIVAÇÃO](#11-motivação)
- [1.2 OBJETIVOS](#12-objetivos)
- [2 CENÁRIO ATUAL](#2-cenário-atual)
- [3 BASE DE DADOS](#3-base-de-dados)
- [3.1 SELEÇÃO DOS DADOS](#31-seleção-dos-dados)
- [3.2 PROCESSAMENTO](#32-processamento)
- [3.3 MODELAGEM E AVALIAÇÃO](#33-modelagem-e-avaliação)
- [4 CONCLUSÃO (SEÇÃO PRIMÁRIA)](#4-conclusão-seção-primária)
- [REFERÊNCIAS](#referências)
- [ESTRUTURA REPOSITÓRIO](#estrutura-repositório)

## RESUMO

## 1 INTRODUÇÃO

<p style='text-align: justify;'>O projeto de sistema embarcado depende de diversas questões que são analisadas desde aspectos de mercado até as ações tecnológicas de implementação. Este tópico inicia uma breve introdução dos conceitos relativos ao projeto de sistema eletrônico com ênfase às ferramentas de apoio ao projeto. No processo de compra atual, especialmente no empregado em supermercados, as filas no caixa consomem uma parcela significativa do tempo gasto na compra. Sendo assim, proponho um Sistema Embarcado chamado carrinho de compras inteligente integrado a inteligência artificial, aplicando algoritmo de machine learning, a fim de prever tendências, bem como auxiliar na tomada de decisão.</p>

## 1.1 MOTIVAÇÃO

<p style='text-align: justify;'>Realizar análise exploratório com auxílio de ferramentas para tratamento de dados como o pandas, numpy e afins, gerar um modelo machine learning para treinamento, teste e predição.</p>

## 1.2 OBJETIVOS

<p style='text-align: justify;'>Tendo em vista o tempo empregado no registro de itens, o protótipo em questão tem como objetivo diminuir o tempo gasto no processo de compras, através da descentralização do processo de registro de itens nos caixas que é a parte mais demorada da compra, provocando descontentamento dos clientes e, consequentemente, perda de fidelidade, sendo assim, otimizar o processo, listar e somar os produtos adicionados pelo consumidor antes de chegarem ao caixa. Finalmente, apresentar o resultado processado em um dispositivo de saída, ressaltando que o sistema apresentado visa ser acoplável ao sistema existente na organização, além disso com auxílio da AI aplicar algoritmos de machine learning, a fim de realizar análise exploratória da base de dados, bem como gerar gráficos que apresentem estatísticas ou números sobre o negócio para predição e tomada de decisão.</p>

## 2 CENÁRIO ATUAL

* A Olist é uma loja de departamentos (marketplace) brasileira que atua no segmento de e-commerce, mas não é um e-commerce em si (como ela diz). Atua como uma empresa de tecnologia SaaS (Software as a Service) desde 2015. Oferece uma solução de marketplace (do segmento de e-commerce) para lojistas de todos os portes (e para a maioria dos segmentos) para aumentar suas vendas com presença online ou não. Lojas física com sistemas embarcados para automatizar processo de compra e evitar filas, através de sensores instalados nos carrinhos de compras, que geram dados de pedidos enviados às APIs.

* Depois que um cliente compra o produto da Olist Store, um vendedor é notificado para atender esse pedido. Assim que o cliente recebe o produto, ou vence a data prevista de entrega, o cliente recebe uma pesquisa de satisfação por e-mail onde pode dar uma nota da experiência de compra e anotar alguns comentários. 

## 3 BASE DE DADOS
- <a href="https://github.com/AlexanderVieira/EcommerceAnalytics/blob/master/Docs/DataReport/DataDictionary.md">Relatório base de dados</a>
  
## 3.1 SELEÇÃO DOS DADOS
- <a href="https://github.com/AlexanderVieira/EcommerceAnalytics/blob/master/Data/Processed/processed.md">Conjunto de dados processados</a>

## 3.2 PROCESSAMENTO
- <a href="https://github.com/AlexanderVieira/EcommerceAnalytics/blob/master/Code/DataPrep/eda.ipynb">Pré-processamento (EDA)</a>

## 3.3 MODELAGEM E AVALIAÇÃO
- <a href="https://github.com/AlexanderVieira/EcommerceAnalytics/blob/master/Code/Model/Experiment1/model_evaluation.ipynb">Avaliação de modelos</a>

## 4 CONCLUSÃO (SEÇÃO PRIMÁRIA)
- Portanto, após realizar o EDA foi possível gerar vários insights, modelos de aprendizado de máquina, métricas e tomada de decisão.
-  
## REFERÊNCIAS
- DEEP Learning com Python de A a Z - O Curso Completo. udemy.com. Disponivel em: <https://www.udemy.com/course/deep-learning-com-python-az-curso-completo/learn/lecture/10748990#overview>. Acesso em: 06 nov. 2021.
- MOHRI, M.; AFSHIN ROSTAMIZADEH; AMEET TALWALKAR. Foundations of Machine Learning. second edition. ed. [S.l.]: [s.n.], 2018.
- NORVIG, S. J. R. A. P. Artificial Intelligence A Modern Approach. Fourth. ed. [S.l.]: Pearson, 2020.
- PROJETO de Bloco em IoT e Data Science. lms.infnet.edu.br. Disponivel em: <https://lms.infnet.edu.br/moodle/course/view.php?id=4797#>. Acesso em: 07 nov. 2021.
- OLIST eCommerce-Analytics, Quasi Poisson+Poly Regs. kaggle.com. Disponivel em: <https://www.kaggle.com/anshumoudgil/olist-ecommerce-analytics-quasi-poisson-poly-regs/report>. Acesso em: 04 dez. 2021.

## ESTRUTURA REPOSITÓRIO

```text
EcommerceAnalytics/
├── Code/
│    └── DataPrep/
│    └── Model/
│    │    └── Experiment1/
│    │    └── Experiment2/
│    │    └── Final/
│    └── Operationalization/
├── Data/
│     ├── Modeling
│     └── Processed
│     └── Raw
└──Docs/
    └── Project/
    └── Model/
    └── DataReport/    
```