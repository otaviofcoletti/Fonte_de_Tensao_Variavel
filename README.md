# Fonte de Tensão Variável
Projeto de uma fonte de tensão váriavel de 3V-12V com uma corrente de 100mA.
## Proposta do projeto:
Construção de uma fonte reficadora capaz de transformar corrente alternada de tensão eficaz de 127 volts (pico de 179,6 volts) em uma corrente contínua, com valor de tensão ajustável entre 3 e 12 volts.

Teremos a partir da tomada: tensão 127 volts, corrente alternada e frequência de 60 hz.
## :pencil: Componentes utilizados:
* Transformador:

O transformador é um componente elétrico capaz de alterar o valor da tensão elétrica em um circuito. Para o projeto, foi utilizado um transformador capaz de mudar uma tensão de 127 volts para aproximadamente 19 volts.

* Ponte de diodo:

A ponte de diodo é um dispositivo retificador de tensão, ou seja, ele transforma uma tensão alternada em uma tensão contínua, permitindo que o circuito seja alimentado pelos dois ciclos da corrente alternada.

* Capacitor:

O capacitor é um componente elétrico que armazena cargas elétricas e libera corrente quando a tensão interna é maior que a tensão externa. Ele foi utilizado no projeto para acumular as cargas da corrente alternada vinda da fonte para diminuir o ripple. Foi selecionado um capacitor de 680 uF no circuito para reduzir o ripple em aproximadamente 7.7%.  

* Diodo de Zener:

O diodo de Zener é um diodo especifico que só conduz corrente se ele estiver submetido a uma tensão maior que a sua tensão de trabalho. Dessa maneira, ele limita o maior valor de voltagem que passará pelo resto do circuito. Ele foi utilizado para manter a tensão máxima dos terminais do projeto em 12V. 

* Resistores:

Os resistores são componentes responsáveis por evitar que a corrente ultrapasse altos valores que podem comprometer o circuito. Assim, eles foram utilizados para garantir a segurança e funcinamento de outros componentes.

* Potenciômetro:

O potenciômetro é um componente elétrico de resistência variável capaz de limitar o fluxo de corrente, alterando também a voltagem do circuito. No caso do projeto, ele foi usado para permitir a variação da tensão no intervalo de 3V até 12V.

* Transistor:

O transistor é um componente eletríco utilizado para permitir a passagem da corrente de forma ajustável.

## :heavy_dollar_sign: Preço dos componentes e o custo total da fonte:
| Quatidade     | Componente | Preço |
| ------------- |:-------------| :-----|
|     1x | [Transformador](https://produto.mercadolivre.com.br/MLB-1542461664-transformador-entrada-110220v-saida-17v-16a-uso-geral-_JM#position=9&search_layout=stack&type=item&tracking_id=33a7d7f3-1d1d-4c43-85eb-fd94d08b4dc6) | R$ 22,80 |
| 1x      | [Capacitor](https://www.acheicomponentes.com.br/capacitor-eletrolitico-680uf-10v-105oc-8x13-pre-cortado?parceiro=3811)  | R$ 0,70 |
| 1x      | [Diodo de Zener](https://www.baudaeletronica.com.br/diodo-zener-1n4743-13v-1w.html) | R$ 0,19 |
| 1x 1.2k ohm e 2x 2k ohm | [Resistores](https://www.baudaeletronica.com.br/resistor-2k-5-1-4w.html) |R$ 0,20 + 2x (0,05) = R$ 0,30 |
| 4x     | [Diodos](https://www.baudaeletronica.com.br/diodo-1n4007.html) | 4x (R$0,09) = R$ 0,36 |
| 1x      | [Led](https://www.wjcomponentes.com.br/led-5mm-amarelo?parceiro=6298) | R$ 0,17|
| 1x | [Transistor](https://www.filipeflop.com/produto/transistor-s8050-npn-x10-unidades/) |   R$ 0,59 |
| 1x | [Potenciômetro](https://www.baudaeletronica.com.br/potenciometro-linear-de-5k-5000.html) | R$ 1,99 |
| Total |  |  R$ 27,10 |

## :camera: Fotos das Simulações e Circuitos:

### :chicken: Esquemático no Eagle : 
![alt text](https://user-images.githubusercontent.com/65844604/127213365-f904d8c0-9be8-4b67-94ad-37910302654d.jpg)
### :electric_plug: PCB no Eagle:
![alt text](https://user-images.githubusercontent.com/65844604/127213316-669f87f2-d5d5-4069-88f0-aad2b81f8724.jpg)
### :battery: Circuito no Falstad:
![alt text](https://user-images.githubusercontent.com/65844604/125877636-9c25eb5d-9904-4d9f-83df-b45c53045375.jpg "Imagem do circuito no Falstad")

## :movie_camera: Vídeos:

Apresentação da fonte e detalhamento dos componentes pelos alunos:

https://www.youtube.com/watch?v=KvUwdQwJLZA

## :pencil: Calculos:
<img src="https://render.githubusercontent.com/render/math?math=\large V_{1}"> é a tensão pico após o transformador e <img src="https://render.githubusercontent.com/render/math?math=\large V_{2}"> é a tensão após a ponte de diodo.

Como <img src="https://render.githubusercontent.com/render/math?math=\large V_{1} = 19.05V, V_{2} = 17.6V">
, sabe-se que a ponte de diodo consome aproximadamente <img src="https://render.githubusercontent.com/render/math?math=\large 1.4V">, pois <img src="https://render.githubusercontent.com/render/math?math=\large V_{2} = V_{1} - 1.4V">

Para calcular as correntes : 

<img src="https://render.githubusercontent.com/render/math?math=\large i_{carga} = \dfrac{V_{zener} - V_{be}}{120 \Omega} = \dfrac{12.8 - 0.714}{120 \Omega} = 99.817 mA">
<img src="https://render.githubusercontent.com/render/math?math=\large i_{zener} = \dfrac{V_{2} - V_{zener}}{1200 \Omega} = 1.015 mA">

<img src="https://render.githubusercontent.com/render/math?math=\large i_{led} = \dfrac{V_{2} - V_{led}}{2000 \Omega} = 7.877 mA">

<img src="https://render.githubusercontent.com/render/math?math=\large i_{pontenciometro} = \dfrac{12.8}{6.5 \Omega} = 1.96 mA">

<img src="https://render.githubusercontent.com/render/math?math=\large i = i_{carga} %2B i_{zener} %2B i_{led} %2B i_{pontenciometro}">

Para calcular a capacitância :

<img src="https://render.githubusercontent.com/render/math?math=\large C = \dfrac{i}{f \cdot U}">

<img src="https://render.githubusercontent.com/render/math?math=\large i = 110.669mA">

<img src="https://render.githubusercontent.com/render/math?math=\large f = 2 \cdot 60Hz">

<img src="https://render.githubusercontent.com/render/math?math=\large U = V2 \cdot Ripple = 17,6 \cdot 0.077">

<img src="https://render.githubusercontent.com/render/math?math=\large C = 680 \mu F">



## :link: Links 

[Circuito no Falstad versão 1](https://tinyurl.com/ygxmeaq4 "Falstad")

[Circuito no Falstad versão 2](https://tinyurl.com/yfcj22wa "Falstad")

[Circuito no Falstad versão 3](https://tinyurl.com/yggp82k5 "Falstad")

[Circuito no Falstad versão 4](https://tinyurl.com/ygtvqxmx "Falstad")

[Circuito no Falstad versão 5](https://tinyurl.com/yzpdvhwk "Falstad")

[Drive com o circuito no eagle](https://drive.google.com/drive/folders/1UiNvsiAKiuCJ46LNKRNM5V2l7OR_PTXA?usp=sharing)

## :mortar_board: Alunos:

[Otávio Ferracioli Coletti 11767796](https://github.com/otaviofcoletti)

[Kenzo Yves Yamashita Nobre 5028772](https://github.com/kenzonobre)

[Bernardo Rodrigues Tameirão Santos](https://github.com/BernaTameirao)
## Agradecimentos
Os alunos (Nerds da Computação) agradecem o empenho do professor Simões e pelos conhecimentos de eletrônica passados para construção da fonte.:nerd_face:
E também em especial o monitor Kuabara que muito nos ajudou no desenvolvimento do projeto.:sunglasses:
