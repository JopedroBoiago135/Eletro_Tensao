# Fonte de Tensão
Trabalho de Eletronica BCC23


# Membros
Os integrantes pertencentes a este grupo são:
  - Henrique Drago
  - Henrique Yukio Sekido
  - Driely Fernanda Oliveira de Abreu
   - João Pedro Boiago Gomes Santana
  
# Objetivo
Projetar e construir uma fonte de tensão ajustavel entre 3V e 12V a partir de uma fonte energia alternada (60 hertz) de 127V com pico de 180V.


# Componentes Utilizados
| Quantidade | Componentes                       | Valor R$ |
|------------|-----------------------------------|----------|
| 4          | Diodo                             |  |
| 1          | Capacitor 1mF                     |  |
| 1          | Resistor 5.6k                     |  |
| 1          | Resistor 1.2k                     |  |
| 1          | Potenciômetro  10k                |  |
| 1          | Diodo Zener (13V)                 |  |
| 1          | Transistor NPN 2N3904             |  |
| 1          | Transformador (127V -> 12V 300mA) |  |
| Total      |                                   | 99999999 |


# Explicação das Peças

- Transformador: Responsável por converter a tensão da rede eletrica (127V rms, 180V de pico) para a desejada no circuito (12V de rms, 18V de pico). Funciona por meio de indução magnetica, a razão entre o numero de voltas do fio em cada lado do transformador dita a taxa de conversão da corrente.

- Diodos: Permitem a passagem de corrente em só um sentido. A Ponte de Diodos é construida de forma que independentemente da fase da tensão, sempre chegará um valor positivo ao outro lado da ponte, tornando a corrente continua.

- Capacitor: Armazena eletrons durante os picos e libera durante os vales, diminuindo a variação da tensão.

- Diodo Zenner: Limita a corrente maxima que chega no resistor final.

- Resistor 1.2k: Utilizado para reduzir o desperdicio de energia.

- Resistor 5.6k: Utilizado para ajustar o limite inferior para 3V.

- Potenciômetro: Permite o ajuste entre 3V e 12V.

- Transistor: Trabalha junto do potenciômetro permitir o ajuste entre 3V e 12V.


# Esquema do Projeto no Falstad

<img src="./Imagens/Imagem Falstad.png">

Link: https://tinyurl.com/2eew96xv


# Esquema do Projeto no Eagle


# Video Explicativo do Projeto (Youtube)


# Agradecimentos
Prof Simões (vulgo Simas)




