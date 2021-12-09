# Previsão de vendas de uma rede de drogarias  

A Dirk Rossmann GmbH, é uma das maiores redes de drogarias da Europa, com cerca de 56.200 funcionários e mais de 4.000 lojas. Em 2019, a Rossmann faturou mais de € 10 bilhões na Alemanha, Polônia, Hungria, República Tcheca, Turquia, Albânia, Kosovo e Espanha. 

![csm_buehne_mobil_unternehmen_5_1000x848_1bd7e72387](https://user-images.githubusercontent.com/69815426/144940356-a00abf79-b51b-47ce-b458-c706e326fdb1.jpg)  

**Qual é o problema do negócio?**  
Os gerentes de loja da Rossmann têm a tarefa de prever suas vendas diárias com até seis semanas de antecedência. As vendas da loja são influenciadas por muitos fatores, incluindo promoções, competição, feriados escolares e estaduais, sazonalidade e localidade. 

A questão é: realizar a previsão de vendas com seis semanas de antecedência. 

**Fonte dos dados**  
https://www.kaggle.com/c/rossmann-store-sales 

**Método utilizado para a solução do problema**  
Para efetuar a previsão de vendas da rede de drogarias Rossmann foi utilizado o Cross Industry Standard Process for Data Mining (CRISP-DM).  Neste trabalho é apresentado o primeiro ciclo do CRISP-DM. 

Ressalta-se que no mundo real é fundamental entender a questão de negócio. Por esta razão é estratégico entender o problema. Perguntas direcionadas ao time de negócios podem auxiliar nesse entendimento, como por exemplo: por que é importante essa análise para o negócio? / a análise estará direcionada a que contexto? / quem iremos analisar? (compradores, fornecedores...) / o que iremos analisar (comportamento de compra...)? / qual período será considerado para as análises?  Após esse entendimento, então iniciam-se os trabalhos de coleta dos dados e outros passos que são descritos a seguir, e que podem ser acompanhados detalhadamente no notebook.        

Inicialmente no notebook são apresentados:  
- A) Bibliotecas
- B) Funções auxiliares
- C) Carregamento dos dados

E a seguir:
- Passo 1 - Descrição dos dados: descrição dos dados, substituição dos dados faltantes e estatística descritiva.
  
- Passo 2 - Feature engineering:  brainstorming de hipóteses e feature engineering.   

- Passo 3 - Filtragem das variáveis: de acordo com o time de negócios as variáveis são filtradas.
  
- Passo 4 - Análise exploratória dos dados: análise univariada, análise bivariada e análise multivariada. 
 
- Passo 5 - Preparação dos dados: rescaling, encoding, esponse variable transformation, nature transformation.  

- Passo 6 - Seleção de features: divisão do dataframe em treinamento e conjunto de dados de teste, boruta.

- Passo 7 - Machine learning modelling: estabelecendo a média, regressão linear e cross validation, lasso e cross validation, random forest e cross validation,XGBoost regressor e cross validation.
 
- Passo 8 - Hyperparameter fine tunning: single performance e cross validation, real performance e cross validation.  
**Observação:**  XGBoost Regressor selecionado: custo/benefício da implementação. 

- Passo 9 - Tradução e interpretação do erro  

**Conclusão (primeiro ciclo do CRISP-DM):**  

No final do trabalho obtém-se a seguinte previsão de valores para as próximas 6 semanas:
![testeA](https://user-images.githubusercontent.com/69815426/144938450-e2e490b6-5e29-44c1-8fa6-c37505cda5c0.png)  

**Referências**  

- Fonte da imagem e dados básicos da empresa: https://en.wikipedia.org/wiki/Rossmann_(company)  
- Comunidade DS: https://www.comunidadedatascience.com/blog/  
- CRISP-DM: https://pt.wikipedia.org/wiki/Cross_Industry_Standard_Process_for_Data_Mining  
  
