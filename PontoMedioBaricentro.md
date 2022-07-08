# Ponto Médio

O segmento de reta possui inúmeros pontos alinhados, mas somentos **um** deles divide o segmento em duas partes exatamentes iguais.

A identificação e a determinação desse, é chamada de **ponto médio**, por exemplo:

<p align="center">
    <img src="https://s2.static.brasilescola.uol.com.br/img/2017/03/segmento-de-reta-com-ponto-medio.jpg"/>
</p>

O segmento de reta AB possui um ponto médio (M), que tem as coordenadas (Xm, Ym). Observe que é formado triângulos (AMN) e (ABP) são semelhantes e possuem três ângulos iguais.

Assim podemos aplicar a relação entre os segmentos:

$\frac{AM}{AB} = \frac{AN}{AP}$

Podemos concluir que AB = 2 $\cdot$ AM, já que o M é o ponto médio do segmento AB.

Então podemos substituir:

$\frac{AM}{2 \cdot AM} = \frac{AN}{AP}$

$\frac{AN}{AP} = \frac{1}{2}$

$AP = 2 \cdot AN$ 

Outras conclusões que podemos tirar:

$
x_p - x_a = 2 \cdot (x_m - x_a)\\
x_b - x_a = 2 \cdot (x_m - x_a)\\
x_b - x_a = 2 \cdot x_m - 2 \cdot x_a\\
2 \cdot x_m = x_b - x_a + 2 \cdot x_a\\
2 \cdot x_m = x_a + x_b\\
x_m = (x_a + x_b)/2\\
$

Repetindo a ideia, chegaremos que $y_m = (y_a + y_b)/2$

Assim, considerando M como o ponto médio de AB, temos a seguinte expressão para determinar as coordenadas do ponto médio de qualquer segmento no plano cartesiano:

$
x_m = (\frac{x_a+x_b}{2},\frac{y_a+y_b}{2})
$

## Exemplos:

1) Dadas as coordenadas dos pontos A(4, 6) e B(8, 10) pertencentes ao segmento AB, determine as coordenadas do ponto médio desse segmento.

Resolução:

$
x_a = 4, y_a = 6\\ 
x_b = 8, y_b = 10\\
X_m = (x_a + x_b) / 2\\
x_m = (4 + 8)/2\\
x_m = 12/2\\
x_m = 6
y_m = (y_a + y_b)/2\\
y_m = (6 + 10) / 2\\
y_m = 16/2\\
y_m = 8\\
$

As coordenadas do ponto médio do segmento AB são (6, 8).

2) Dado os pontos P(5, 1) e Q(-2, -9), determine as coordenadas do ponto médio do segmento PQ.

$
x_m = [5+(-2)]/2\\
x_m = (5-2)/2\\
x_m = 3/2\\
y_m = [1 + (-9)]/2\\
y_m = (1-9)/2\\
y_m = -8/2\\
y_m = -4\\
$

Portanto, o ponto médio de PQ é ($\frac{3}{2}, -4$)

# Baricentro

Baricentro é um dos pontos notáveis do triângulo. Podemos falar também que o baricentro é o "Centro de gravidade do triângulo". 

Para encontrar  baricentro, devemos encontrar suas três medianas (É um segmento que divide as bases do triangulo em duas partes iguais) e o ponto de encontro entre elas. 

Quando representamos no plano cartesiano, podemos encontrar o baricentro calculando a média aritmética entre os valores de x e de y, assim encontrando o par ordenado do baricentro.

As três medianas do triangulo:

<p align="center">
    <img src="https://s5.static.brasilescola.uol.com.br/be/2021/03/1-1-medianas.jpg"/>
</p>

Se traçarmos as três ao mesmo tempo, temos:

<p align="center">
    <img src="https://s4.static.brasilescola.uol.com.br/be/2021/03/2-baricentro.jpg"/>
</p>

E encontramos o baricentro.

Propriedades do Baricentro:
- É sempre um ponto interno do triângulo.
- Divide a mediana em duas partes cuja razão é 1:2

No triangulo representado anteriormente, temos então:

$\frac{GM_a}{MA} = \frac{GM_b}{MB} = \frac{GM_c}{MC} = \frac{1}{2}$

Para calcular o baricentro:

Primeiro representamos ele no plano cartesiano, assim:

<p align="center">
    <img src="https://s4.static.brasilescola.uol.com.br/be/2021/03/triangulo-no-plano-cartesiano.jpg"/>
</p>

Vemos que os vértices são $A(x_a, y_a), B(x_b, y_b) e C(x_c, y_c)$, então para encontrar as coordenadas do baricentro G, utilizamos a fórmula:

$
G(x_g, y_g)\\
x_g = \frac{x_a+x_b+x_c}{3}\\
y_g = \frac{y_a+y_b+y_c}{3}\\
$

## Exemplos:

1) Podemos afirmar que o baricentro do triângulo cujos vértices são os pontos A(2, 1), B(-3, 5) e C(4, 3) é o ponto:

a) G(1, 3)

b) G(3, 1)

c) G(3, 3)

d) G(-2, -1)

e) G(-1, 3)

Resolução:

Basta jogar na fórmula:
$
x_g = \frac{2+(-3)+4}{3} = \frac{2-3+4}{3} = \frac{3}{3} = 1\\
y_g = \frac{1+5+3}{3} = \frac{9}{3} = 3
$

Logo, G(1, 3), então resposta A.

