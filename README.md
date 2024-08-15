# Redes Neurais Artificiais (RNA)

Por muito tempo, a computação buscou imitar a capacidade do cérebro humano. Essa busca deu origem à área da **Inteligência Artificial (IA)** dentro da Ciência da Computação. A IA pode ser dividida em três áreas principais:

![Diagrama das áreas da Inteligência Artificial](https://github.com/user-attachments/assets/80efc18b-a5fa-4a26-90f3-dd413f7ee64e)

Dentro dessas áreas, o **Aprendizado de Máquina (Machine Learning - ML)** e o **Aprendizado Profundo (Deep Learning - DL)** se destacam. Eles utilizam neurônios artificiais, que são algoritmos projetados para simular o comportamento dos neurônios biológicos através de cálculos matemáticos.

Esses neurônios artificiais funcionam com base em dois processos principais: a **soma ponderada** e a **função de ativação**. A soma ponderada multiplica as entradas pelos pesos sinápticos **(w)** e adiciona um viés **(b)**. O resultado dessa soma é enviado para a função de ativação, que decide se o neurônio será ativado ou não.

![Esquema de um neurônio artificial](https://github.com/user-attachments/assets/8964288e-e8ab-4e64-a489-149868ae37ed)

### Conceitos Principais:

* **Soma ponderada**: A soma das entradas multiplicadas pelos seus respectivos pesos, acrescida do viés.
* **Pesos sinápticos (w)**: Determinam a importância de cada entrada e são ajustados durante o treinamento. É onde ocorre o aprendizado da rede.
* **Viés (b)**: Ajusta a saída do neurônio para evitar que a rede fique enviesada ou "decore" padrões específicos.
* **Funções de ativação**: Decidem se o neurônio será ativado. Para explorar mais sobre as funções de ativação, confira este [código com exemplos](https://github.com/LeandroRodriguesCarneiro/EstudosRedesNeurais/blob/main/FuncoesAtivacao/ActivactionFunctions.ipynb).

## Neurônios Artificiais

Os neurônios artificiais são implementações matemáticas inspiradas nos neurônios biológicos. Vamos explorar dois tipos básicos:

### Perceptron

O **Perceptron** é um dos primeiros modelos de neurônio artificial. Ele usa uma função de ativação simples, conhecida como "step function", e sua regra de aprendizado é chamada de **Perceptron Rule**, que só informa se a classificação está correta ou não. O perceptron é um classificador linear binário, ou seja, ele só consegue separar dados em duas classes distintas e resolver problemas simples.

Confira um [código de implementação do perceptron](https://github.com/LeandroRodriguesCarneiro/EstudosRedesNeurais/blob/main/PerceptronSimples/Perceptron.ipynb).

### Adaline

O **Adaline** (Adaptative Linear Neuron) é uma evolução do perceptron. Ele também é um classificador linear binário, mas introduz algumas melhorias, incluindo uma nova regra de aprendizado chamada **Delta Rule**.

Veja a implementação do Adaline neste [código de exemplo]().
