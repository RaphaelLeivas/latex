## Dúvidas e Pendências

- Problema P9.69: porque i_GND é igual a zero? Não seria igual a corrente na malha 2?
O solucionário do Nilsson considerou ela nula, porque?
    * eu fiz considerando zero mesmo, como se fosse um erro na imagem aparecer um curto entre os terminais
    + e - do AmpOp.
- Problema P10.46: quando a maxima transferencia de potencia é ajustada para um resistor, temos
R = |Zth*| ou R = Real{Zth*} ?
    * eu fiz considerando o que esta no solucionário, ou seja, R = |Zth*|
- O fasor de uma onda senoidal Acos(wt + theta) é A\phase ou é (A/sqrt(2))\phase? Eu uso o valor de pico ou o 
valor RMS no modulo do fasor? 
    * Depende, tem vez que pe conviente usar um ou outro. Nao é 100% definido em regra.

## Problemas com a linguagem


## Melhorias

- Considerar refazer P7.53 usando variaveis. Subsitui numeros no inicio e ficou uma bagunça (apesar de correto)
- corrigir e padronizar o 'Figure' das figuras
- Melhorar label de equations (https://tex.stackexchange.com/questions/278712/numbering-many-equations-automatically-plus-allowing-to-add-new-equations)
    * nao parece ser ideal colocar o numero da equação no label de referencia
    * sem o numero do label, seria possivel referenciar equacoes de outros problemas, evitando repeticao
- Corrigir warnings da extensão do VS Code no arquivo principal
- P8.33, entender porque deu pau nas condições iniciais, deveria ter funcionado
