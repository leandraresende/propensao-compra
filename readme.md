## 1 - PROBLEMA DE NEGÓCIO

Uma empresa de seguros de saúde pretende expandir seus negócios oferecendo aos seus clientes o seguro veicular. Para analisar a viabilidade desse produto, a empresa pesquisou,
em parte da sua base consumidora, se eles teriam interesse nesse novo seguro. Para o restante da base consumidora, a empresa decidiu que a oferta do novo produto se dará 
por meio de ligação telefônica. No entanto, a equipe tem capacidade de fazer 20 mil ligações. O desafio é treinar um classificador para analisar se o cliente teria interesse 
em comprar o seguro veicular, tendo como referência a pesquisa realizada.
   
## 2 - ESTRATÉGIA DA SOLUÇÃO

   1 - Análise descritiva: uso de métricas estatísticas para analisar os dados coletados.
   
   2 - Tratamento e limpeza dos dados: seleção e tratamento de colunas e linhas com informação de interesse.
   
   3 - Análise exploratória dos dados: explorar os dados para entender as variáveis e seus respectivos impactos na aprendizagem do modelo, além de obter insights sobre suas relações.
   
   4 - Preparação dos dados: preparar os dados para otimizar o aprendizado do modelo.
   
   5 - Seleção de features: seleção dos atributos com maior relevância para o treinamento do modelo.
   
   6 - Implementação do modelo de Machine Learning: escolha e treinamento dos algoritmos de Machine Learning.
   
   7 - Hyperparameter Fine Tuning: refinamento dos parâmetros do modelo selecionado.
   
   8 - Análise das métricas de negócio: converter o resultado do modelo de Machine Learning em resultados de negócio.
   
   9 - Deploy do modelo em produção: publicação do modelo em clouds possibilitando o acesso ao resultado obtido.



## 3 - TOP INSIGHTS DE DADOS

 1 - Quem gasta na faixa de 2700.0 com seguro-saúde é mais propenso a aderir ao seguro veicular.
 
 2 - Alguns meio de comunicação com o cliente tem resultados bem melhores na adesão ao seguro. 
 
 3 - Há uma tendência que indica a diminuição do gasto anual com o seguro-saúde com o aumento da idade do cliente.
 

## 4 - PRODUTO FINAL DO PROJETO 

O produto final é um modelo de classificação que pode ser armazenado em cloud e acessado via Api.

    
## 5 - CONCLUSÃO

O modelo treinado permite classificar os clientes com relação ao seu interesse em aderir à um seguro veicular baseando-se nos dados de clientes que já possuem o seguro saúde. 
Em uma escolha aleatória de clientes pelo time de vendas, fazendo as 20000 ligações, apenas 26% dos possíveis interessados em adquirir o seguro seriam contactados. Já em uma 
escolha seguindo o modelo treinado no projeto, o time de vandas contactaria quase 65% dos interessados. Ou seja, o resultado do modelo é 2,5 vezes melhor que uma escolha 
aleatória. Considerando que o valor do seguro veicular seja na faixa de 1500, para as porcentagens descritas acima, o modelo faturaria, aproximadamente, 44 milhões a mais 
que a escolha aleatória.


## 6 - PRÓXIMOS PASSOS

   - Colocar o modelo disponível para acesso através do GoogleSheets
   - Testar novos algoritmos avaliando se melhoram a performance.
