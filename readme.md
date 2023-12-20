
# Rede neural para classificação de dígitos MNIST


## Link de funcionamento: https://drive.google.com/file/d/1wmfjLjDzLi5_tsnMFkxfTCok6K62Iink/view?usp=sharing 

Este modelo de rede neural foi projetado para realizar a classificação de dígitos manuscritos usando o conjunto de dados MNIST. A arquitetura é uma versão simplificada, adequada para tarefas de classificação mais leves.

Arquitetura da Rede Neural:

1. Camada de Convolução (Conv2D):
+ Número de Filtros: 16
+ Tamanho do Kernel: (3, 3)
+ Função de Ativação: ReLU
+ Entrada: Imagens de 28x28 pixels em escala de cinza (1 canal)
  
2. Camada de MaxPooling:
+ Tamanho do Pooling: (2, 2)

3. Outra Camada de Convolução e MaxPooling:
+ Número de Filtros: 32;
+ Tamanho do Kernel: (3, 3)
+ Função de Ativação: ReLU
+ Tamanho do Pooling: (2, 2)

4. Camada de Flattening:
+ Transforma a saída da camada anterior em um vetor unidimensional.

5. Camada Densa (Totalmente Conectada):
+ Número de Neurônios: 64
+ Função de Ativação: ReLU

6. Camada de Saída:

+ Número de Neurônios: 10 (um para cada classe)
+ Função de Ativação: Softmax

## Execução 

    Abra o notebook contendo o código da rede neural no ambiente de sua escolha (por exemplo, Jupyter Notebook, JupyterLab).

    Execute as Células: Execute cada célula do notebook sequencialmente. As células podem ser executadas pressionando Shift + Enter após selecionar a célula.