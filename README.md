# Avali-o_On-line_PI_CP-CTI_PEN
PROJETO INTEGRADO 3: CIÊNCIA DE DADOS

Avalição On-line PI_CP-CTI_PEN
Usei o Colab Notebook para o script no python.

Abaixo apresentação da Matriz de confusão e acurácia do modelo:



Matriz de Confusão:
[[2 2]
[0 2]]



Análise da Matriz de Confusão:
Verdadeiro Negativo (VN): 2 - O modelo previu corretamente "nao" (0) para 2 casos onde a pessoa realmente não tinha dengue.
Falso Positivo (FP): 2 - O modelo previu "sim" (1) para 2 casos onde a pessoa não tinha dengue (falso alarme).
Falso Negativo (FN): 0 - O modelo previu "nao" (0) para 0 casos onde a pessoa tinha dengue (não detectou a dengue quando ela estava presente - aqui o 0 era realmente esperado!).
Verdadeiro Positivo (VP): 2 - O modelo previu corretamente "sim" (1) para 2 casos onde a pessoa realmente tinha dengue.
Total de casos no teste: 2(VN)+2(FP)+0(FN)+2(VP)=6 casos.


Acurácia do Modelo: 0.6667
A acurácia é calculada como (VN+VP)/Total=(2+2)/6=4/6≈0.6667.
Uma acurácia de aproximadamente 67% significa que o modelo acertou em 67% das previsões no conjunto de teste.

