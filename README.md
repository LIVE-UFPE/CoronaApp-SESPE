# CoronaApp-SESPE
Produto destinado ao uso pela Secretaria Estadual de Saúde de PE, uma página web com gráficos e heatmap sobre o COVID

## Normas de commits e branches
* Cada tela deve ser criada como uma __page__ em `src\pages`, cada __component__, em `src\components`
* Qualquer um pode dar merge na master, desde que não interfira na estrutura atual
* Qualquer feature deve ser, obviamente, criada em uma branch a parte, para, quando estiver concluída, merjada na master e, se não houver mais necessidade, deletada a branch



### Em relação a estrutura de React / Ionic
---
Um __Componente__ é a estrutura mínima do projeto. Tudo é feito de componentes, e cada conjunto de componentes são outros componentes em si, apenas recebem outro nome para facilitar na categorização, como as __pages__, que se referem a tela em si, mas na verdade é um grande componente composto de componentes menores
