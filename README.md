# Shallow-Neural-Networks

## Abstract

> Quando se ouve falar em redes neuronais, associa-se ao conceito de que estas operam/con- sistem em múltiplas camadas ocultas. No entanto, existe um tipo de arquitetura que apenas consiste numa camada intermédia, Shallow Neural Networks. Entender este tipo de rede é fundamental para entender o que realmente acontece em redes neuronais profundas, pois com a simplificação oferecida por uma shallow network, relativamente a uma deep neural network, é possível compreender as operações compostas pelas diversas unidades de cálculo, denomina- das por neurónio. Estas unidades determinam a capacidade de generalização de uma rede e, com uma intuição razoável, é possível obter uma melhor interpretação de resultados quando se tratam de redes complexas.


## Introdução

> Shallow Neural Networks é um tipo de arquitetura utilizada nos tempos correntes não só pela sua eficiência, como muitas vezes pela sua efetividade. A utilização de apenas uma camada intermédia permite-nos uma melhor compreensão do funcionamento destes modelos.
Ao longo deste artigo, tenta-se evidenciar o porquê do uso de shallow neural networks e a resposta a uma das perguntas mais predominantes na área de deep learning, **Do Deep Nets Really Need to be Deep?**
Começa-se por uma explicação teórica de como opera este tipo de rede através de uma vertente matemática complementar.
Após a descrição do modelo, coloca-se este modelo em teste com uma base de dados simples e adequada ao problema, respetivamente o xor, devido tanto às propriedades intrínsecas de uma boa baseline como ao seu contexto histórico.
Esta operação binária representa o mais simples conjunto linearmente não separável, facilitando um potencial debugging do algoritmo e providenciando resultados relativamente simples de analisar. Após mostrar o propósito das Shallow Neural Networks, utilizam-se exemplos mais diversificados e complexos que o xor para que se consiga identificar o nível de generalização deste tipo de modelos
e o porquê da utilização de redes neuronais profundas.
As Shallow Neural Networks apresentam maior simplicidade, interpretabilidade e um menor
custo computacional. No entanto, dado que as redes mais profundas conseguem aprender distri- buições mais complexas, estas apresentam potencialmente melhores resultados, dependendo do problema em causa, apresentando custos computacionais mais elevados.
Nesse sentido, o principal objetivo deste trabalho é a análise e interpretação dos resultados, a nível de dados e capacidade de inferência, de utilização de apenas uma ou várias camadas numa rede neuronal.
