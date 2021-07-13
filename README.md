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
| col 3 is      | Capacitor | $1600 |
| col 2 is      | Diodo de Zener |   $12 |
| zebra stripes | Resistores |    $1 |
| col 3 is      | Transformador | $1600 |
| col 3 is      | Capacitor | $1600 |
| col 2 is      | Diodo de Zener |   $12 |
| Total |  |    1 BTC |

## :camera: Fotos das Simulações e Circuitos:

(colocar fotos aqui)
### :chicken: Esquemático no Eagle : 
![alt text](https://user-images.githubusercontent.com/65844604/124635147-7ae3b400-de5d-11eb-9229-59a7308ce5b2.jpg "Imagem do esquemático no Eagle")
### :electric_plug: PCB no Eagle:
![alt text](https://user-images.githubusercontent.com/65844604/124635149-7b7c4a80-de5d-11eb-987f-f3e81e98af8b.jpg "Imagem do PBC no Eagle")
### :battery: Circuito no Falstad:
![alt text](https://user-images.githubusercontent.com/65844604/124635729-20972300-de5e-11eb-8fa2-968b43ea7099.jpg "Imagem do circuito no Falstad")


## :link: Links 

[Link do circuito no Falstad versão 1](https://tinyurl.com/ygxmeaq4 "Falstad")

[Link do circuito no Falstad versão 2](https://tinyurl.com/yfcj22wa "Falstad")

[Link do circuito no Falstad versão 3](https://tinyurl.com/yggp82k5 "Falstad")

[Link do circuito no Falstad versão 4](https://tinyurl.com/ygtvqxmx "Falstad")

[Link do circuito no Falstad versão 5](https://tinyurl.com/ygcgxo6z "Falstad")

## :mortar_board: Alunos:

Otávio Ferracioli Coletti

Kenzo Yves Yamashita Nobre

Bernardo Rodrigues Tameirão Santos
