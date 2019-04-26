# Redes Neurais Artificiais

1. Um neurônio artificial é uma implementação de uma abstração do neurônio biológico, cujo o funcionamento tem inspiração no mesmo e suas partes. Os terminais de entrada representam os dendritos, o terminal de saída o axônio e os pesos fazem referência às sinapses. 
1. A utilização do Bias ou Tendência causa uma diferença sistemática em relação ao valor de referência, conforme mostra o hiperplano abaixo:
![Bias Effect](https://cdn-images-1.medium.com/max/1600/0*-fy5FhuunyvTHJpj.png "https://medium.com/deeper-learning/glossary-of-deep-learning-bias-cf49d9c895e2")
1. A utilização dos pesos auxilia o algoritmo a ponderar o valor de cada entrada, facilitando assim a priorização de variáveis mais importantes em oposição às demais, permitindo um aprendizado mais dinâmico.
1. O neurônio Adaline, diferente do Perceptron, utiliza em seu treinamento a Regra Delta (Mínimos Quadrados) para o cálculo do erro (para ajustes dos pesos), buscando minimizar a diferença entre o valor esperado e o obtido no intuito de traçar a (única) reta ótima que separa as classes.
1. A função de ativaçao tem como objetivo regular o valor de saída (totalização dos produtos entre entradas e pesos) dentro de um intervalo determinado, decidindo pela sua ativação ou não.
1. A taxa de aprendizagem é o passo de atualização dos pesos no treinamento de um neurônio, ou seja, taxas pequenas atualizam os pesos de forma suave (passos pequenos) enquanto que taxas grandes atualizam de forma mais agressiva (passos grandes).
1. Cada neurônio (perceptron) tem a abilidade de aplicar apenas uma função sobre as entradas de dados, sendo assim, a adição de neurônios em uma mesma camada permite a aplicação de mais de uma função sobre os mesmos dados. Em casos como o problema da porta lógica XOR, onde não é possível traçar apenas uma reta para separação das classes, a adição de mais um neurônio pode ser utilizada para traçar duas retas, resolvendo o problema.
1. Ao adicionarmos neurônios em uma mesma camada estamos aumentando a quantidade de saída de dados, ou seja, se cada neurônio produz apenas uma saída teremos tantas saídas quanto neurônios (mesmo que seus valores sejam 0). A adição de mais camadas de neurônios permite a unificação e/ou a aplicação de novas funções sobre elas.
1. A adição de mais entradas permite a assimilação de mais variáveis por aquele neurôrio.
1. 10
   1. https://gist.github.com/MwillianM/cc06c0d47fbcbbca2c5c2bdc5bc2dbad
   2. https://gist.github.com/MwillianM/876303c196f05cda40fa8fdcfe485974
