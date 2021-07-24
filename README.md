# Fonte de Tensão Variável
Projeto de desemvolvimento de uma fonte de tensão váriavel de 3V-12V com uma corrente de 100mA.
## Proposta do projeto:
Construção de uma fonte reficadora capaz de transformar corrente alternada de tensão eficaz de 127 volts (pico de 179,6 volts) em uma corrente contínua, com valor de tensão ajustável entre 3 e 12 volts.

Teremos a partir da tomada: tensão 127 volts, corrente alternada e frequência de 60 hz.
## :pencil: Componentes utilizados:
* Transformador:

O transformador é um componente elétrico capaz de alterar o valor da tensão elétrica em um circuito através de duas ou mais bobinas acopladas em um núcleo ferromagnético. Para o projeto, foi utilizado um transformador capaz de mudar uma tensão de 127 volts para aproximadamente 17 volts.

* Ponte de diodo:

A ponte de diodo é um dispositivo retificador de tensão, ou seja, ele transforma uma tensão alternada em uma tensão contínua, permitindo que o circuito seja alimentado pelos dois ciclos da corrente alternada.

* Capacitor:

O capacitor é um componente elétrico que armazena cargas elétricas e libera corrente quando a tensão interna é maior que a tensão externa. Ele foi utilizado no projeto para acumular as cargas da corrente alternada vinda da fonte para diminuir o ripple. Foi selecionado um capacitor de 680 uF, reduzindo o ripple em aproximadamente 6%~7%.  

* Diodo de Zener:

O diodo de Zener é um diodo especifico que só conduz corrente se ele estiver submetido a uma tensão maior que a sua tensão de trabalho. Dessa maneira, ele limita o maior valor de voltagem que passará pelo resto do circuito. Ele foi utilizado para manter a tensão máxima dos terminais do projeto em 12V. 

* Resistores:

Os resistores são componentes responsáveis por evitar que a corrente ultrapasse altos valores que podem comprometer o circuito. Assim, eles foram utilizados para garantir a segurança e funcinamento de outros componentes.

* Potenciômetro:

O potenciômetro é um componente elétrico de resistência variável capaz de limitar o fluxo de corrente, alterando também a voltagem do circuito. No caso do projeto, ele foi usado para permitir a variação da tensão no intervalo de 3V até 12V.

* Transistor:

## :heavy_dollar_sign: Preço dos componentes e o custo total da fonte:
| Quatidade     | Componente | Preço |
| ------------- |:-------------| :-----|
|     1x | [Transformador](https://www.baudaeletronica.com.br/transformador-trafo-12v-200ma-110-220vac.html) | R$ 21,35 |
| 1x      | [Capacitor](https://www.acheicomponentes.com.br/capacitor-eletrolitico-680uf-10v-105oc-8x13-pre-cortado?parceiro=3811)  | R$ 0,70 |
| 1x      | [Diodo de Zener](https://www.baudaeletronica.com.br/diodo-zener-1n4743-13v-1w.html) | R$ 0,19 |
| 1x 1.2k e 2x 2k | [Resistores](https://produto.mercadolivre.com.br/MLB-1756151761-resistor-de-carbono-2k-5-14w-cr25-100pcs-_JM#position=4&search_layout=grid&type=item&tracking_id=1acba448-6fae-4b1d-ad05-824455a9e04c) |R$ 0,2 + 2x (0,23) = R$ 0,66 |
| 4x     | [Diodos](https://www.baudaeletronica.com.br/diodo-1n4001.html) | 4x (R$0,15) = R$ 0,60 |
| 1x      | [Led](https://www.baudaeletronica.com.br/led-difuso-5mm-vermelho.html) | R$ 0,19|
| 1x | [Transistor](https://www.baudaeletronica.com.br/transistor-npn-bc548.html) |   R$ 0,17 |
| 1x | [Potenciômetro](https://www.baudaeletronica.com.br/potenciometro-linear-de-5k-5000.html) | R$ 1,99 |
| Total |  |  R$ 25,85 |

## :camera: Fotos das Simulações e Circuitos:

### :chicken: Esquemático no Eagle : 
![alt text](https://user-images.githubusercontent.com/65844604/125877613-3b22d568-c141-4f44-8235-5377413f8bcb.jpg "Imagem do esquemático no Eagle")
### :electric_plug: PCB no Eagle:
![alt text](https://user-images.githubusercontent.com/65844604/126878027-13d61170-cd34-4a2e-bc91-fd6da0839474.jpg "Imagem do PBC no Eagle")
### :battery: Circuito no Falstad:
![alt text](https://user-images.githubusercontent.com/65844604/125877636-9c25eb5d-9904-4d9f-83df-b45c53045375.jpg "Imagem do circuito no Falstad")


## :link: Links 

[Circuito no Falstad versão 1](https://tinyurl.com/ygxmeaq4 "Falstad")

[Circuito no Falstad versão 2](https://tinyurl.com/yfcj22wa "Falstad")

[Circuito no Falstad versão 3](https://tinyurl.com/yggp82k5 "Falstad")

[Circuito no Falstad versão 4](https://tinyurl.com/ygtvqxmx "Falstad")

[Circuito no Falstad versão 5](https://tinyurl.com/yzpdvhwk "Falstad")

[Circuito no Falstad versão 6](https://tinyurl.com/yds5xvhu "Falstad")

## :mortar_board: Alunos:

Otávio Ferracioli Coletti

Kenzo Yves Yamashita Nobre

Bernardo Rodrigues Tameirão Santos
