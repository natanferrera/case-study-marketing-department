# case-study-marketing-department
Neste estudo de caso, o principal intuito foi praticar funções e métodos de análise, padronização de dados
e redução de dimensionalidade

Contexto
Fomos contratados por uma empresa privada para analisar os dados e dividir os clientes em pelo menos 3 grupos

Avaliando 
1.     Um dos pontos cruciais do marketing é conhecer seus clientes e reconhecer suas necessidades
2.     Entendendo os consumidores podemos oferecer serviços específicos para necessidades específicas
3.     Se os dados sobre os clientes estão disponíveis, podemos aplicar a segmentação no mercado com Ciência de dados

Etapa de redução de dimensionalidade com PCA:
O nosso processo com o autoencoder será um pouco diferente. 
Iremos comprimir as 18 características para 10(ele vai juntar os atributos mais correlacionados), após definir a compressão vamos aplicar novamente o método Elbow Method, onde vamos analisar a melhor quantidade de cluster para nosso dataframe, após a clusterização, aplicamos o k-means e finalizamos fazendo o uso do PCA.
