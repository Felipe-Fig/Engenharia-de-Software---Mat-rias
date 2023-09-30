# Fundamentos de Cálculo Aplicado
## Unopar - Anhanguera
### Engenharia de Software

# Questão
O lucro L(x) de uma indústria de peças para máquinas agrícolas é dado em função da quantidade x de unidades produzidas conforme a seguinte função:

L(x) = - x² + 990x - 89 000

A respeito desse contexto, julgue as seguintes afirmações, classificando-as como verdadeiras (V) ou falsas (F):

(  ) O lucro dessa indústria será sempre positivo, independentemente da quantidade de peças produzidas.

(  ) O lucro mínimo é atingido por essa indústria na produção de 495 peças.

(  ) O lucro máximo obtido por essa indústria é de R$ 156 025,00.

(  ) A produção de uma quantidade de peças inferior a 100 unidades gera prejuízo para a indústria.

Assinale a alternativa que indica a sequência correta:

**Gabarito: F, F, V, V**

### Explicação da questão
- Para a primeira assertiva precisaremos avaliar o gráfico da equação em questão. Para que o lucro L(x) seja sempre positivo, precisamos que o gráfico dessa equação fique sempre acima do eixo X. Para continuar a análise, precisamos calcular o delta (∆) da equação. Considerando que `∆ = b**2 - 4*a*c`, teremos que ∆ = 990**2 -4*(-1)*89000. 
A conta é grande e difícil de fazer sem calculadora, mas algo pode ser percebido: ∆ será positivo. Isso mostra que a função possui duas raízes reais. Se ela possui duas raízes reais, em 2 pontos do gráfico ela cortará o eixo X e para baixo. Como a < 0, a concavidade da equação é para baixo, de forma que existirá algum valor de X no qual Y será negativo. Como Y = L(x), pode-se dizer que nem sempre o lucro será positivo.

- A segunda assertiva também está incorreta pois não há lucro mínimo. Como o gráfico é côncavo para baixo, a curva se estende até o infinito, não podendo precisar esse valor. Mas podemos avaliar também da seguinte forma: resolvendo o cálculo apresentado na alternativa passada teremos que 
> ∆ = b**2 - 4*a*c\
∆ = 980.100 - 356.000\
∆ = 624.100

Com isso podemos calcular o vértice do gráfico.

> Xv = -b/2a\
Yv = -∆/4a\
Xv = 495\
Yv = 156.025

Ou seja, em 495 peças produzidas teremos o máximo de lucro possível, visto que é o topo, o vértice da função.

- Para a terceira assertiva: está correta, visto o Yv acima.

- Para a quarta assertiva precisamos avaliar quais são as raízes da equação. As raízes são os pontos onde o gráfico cortará o eixo X, significando que o lucro é 0. Qualquer ponto para trás da primeira raiz ou pra frente da segunda raiz será de lucro negativo, necessariamente.
> X1 = - b + sqrt(∆)/2a\
X2 = - b - sqrt(∆)/2a\
X1 = -990 + 790/ (-2) = 100\
X2 = -890

Com isso vemos que a última assertiva está correta, visto que qualquer valor de X acima de 100 (raiz), acarreterá valores de Y (lucro) menores que zero.

# Questão
Os lucros obtidos por uma empresa ao longo de certo período precisam ser distribuídos entre seus três sócios. Para isso, cada sócio receberá uma quantidade proporcional aos investimentos feitos por ele.

João receberá metade dos lucros, visto que ele fez o maior investimento para a abertura dessa empresa. Lucas receberá 1/5 dos lucros, sendo o restante direcionado à terceira sócia, Letícia.

Qual fração dos lucros dessa empresa será direcionada à Letícia?

**Gabarito: 3/10 ou 30%**

### Explicação da questão
- João receberá metade, ou seja, 50%.
- Lucas receberá 1/5, ou seja, 20%.
- Portanto Letícia necessariamente receberá o restante, 30%.

# Questão
A meia-vida é uma propriedade relacionada a substâncias químicas e que descreve o tempo necessário para que metade dos átomos (ou metade da massa) presentes em uma amostra seja desintegrada.

Considere que uma substância possua uma meia-vida de 8 horas. Se a amostra inicial apresenta massa de 500 mg, após quanto tempo a quantidade de substância será reduzida para apenas 62,5 mg?

**Gabarito: Após 24 horas**

### Explicação da questão
| Tempo | Massa |
| :---: | :---: |
| 0 horas| 500mg |
| 8 horas| 250mg |
| 16 horas | 125mg |
| 24 horas | 62,5mg |

# Questão
Para os clientes que utilizam telefones celulares apenas para atividades mais básicas e que buscam um plano mais barato, uma empresa de telefonia oferece aos seus clientes duas opções: um pré-pago e outro pré-fixado.

O plano pré-pago tem um custo de assinatura no valor de R$ 25,00 e o custo de ligação de R$ 0,05 por minuto de chamada, de acordo com o uso feito pelo cliente durante o mês.

Por outro lado, o plano pré-fixado tem uma mensalidade fixa de R$ 60,00, independentemente do tempo de ligação utilizado pelo cliente no mês.

Considerando o período de um mês, em qual situação o plano pré-fixado é mais barato do que o pré-pago?

**Gabarito: Quando o cliente faz ligações que totalizam mais do que 700 minutos por mês.**

### Explicação da questão
- 300 minutos x 0,05 = 15. Somados aos R$ 25 da mensalidade temos um total de R$ 40. Nesse caso o pré-pago é mais barato.
- 500 minutos x 0,05 = 25. Somados aos R$ 25 da mensalidade temos um total de R$ 50. Nesse caso o pré-pago é mais barato.
- 700 minutos x 0,05 = 35. Somados aos R$ 25 da mensalidade temos um total de R$ 60. Nesse caso o pré-pago é o mesmo preço do pré-fixado. Porém, o cliente faz MENOS que 700 minutos, não chegando a igualar o valor.
- Ou seja, se o gasto for MAIOR que 700 minutos, o plano pré-pago fica mais caro que o pré-fixado.

# Questão
Em um estudo, um biólogo percebeu que a quantidade de indivíduos de uma população de bactérias dobra a cada hora.

Ao observar as características dessa população, ele identificou que a quantidade de indivíduos q pode ser dada em função do tempo t, contado a partir do instante inicial t = 0, por meio de uma função na forma: `q(t) = a*b^t`

Após cinco horas do início do estudo, a quantidade de bactérias registrada foi de 16 000 indivíduos.

Com base nessa informação, assinale a alternativa que indica corretamente a função q(t) que modela esse problema:

**Gabarito: q(t) = 500 * 2ˆt**

### Explicação da questão
> q(5) = 16.000\
a*b^5 = 16.000\
16.000 = 2ˆ4 * 10ˆ3\
= 2ˆ4 * 2ˆ3 * 5ˆ3\
= 2ˆ4 * 2ˆ1 * 2ˆ2 * 5ˆ3\
= 2ˆ5 * (2ˆ2 * 5ˆ3)\
= 2ˆ5 * (4 * 125)\
= 2ˆ5 * 500

O objetivo de fazer uma base elevada à 5 potência é pelo fato da função fornecida pelo problema ser elevada à "t". Como o problema me dá o t = 5, simplifiquei de forma que tivesse uma potência de 5 para poder comparar. Chegando à equacão em questão. 