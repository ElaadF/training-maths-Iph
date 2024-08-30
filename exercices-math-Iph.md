# Dévloppement et simplification de polynôme du second degré

Un polynôme du second degré est de la forme :

\begin{align}
f(x) = ax^2 + bx + c \\
\end{align}

Par convention, on réordonne toujours l'équation pour faire apparaître les x^2 avant, puis les x et enfin les tous nus.
En réordonnant une équation (dans notre cas la forme de l'équation s'appelle un polynôme du second degré) il est important de garder les signes à gauche et de garder les priorités des opérations lorsque l'on déplace les objets \
Par exemple :

\begin{align*}
f(x) &= (3 + 4x) - 5x^2 \\
&= -5x^2 + (3 + 4x) && \text{ici, on a : + (3 + 4x) car dans l'équation de base, il n'y a aucun signe à gauche donc, cela est équivalent à un +}\\
&= -5x^2 + 3 + 4x && \text{on peut enlever les parenthèses en conservant les mêmes signes puisqu'on ne multiplie pas ce groupe par un nombre négatif}\\
\end{align*}

Rappel : 
- les opérations se font dans un ordre de priorité : 
1. Les parenthèses
2. les multiplications/divisions : 3x = 3 * x
3. les aditions/soustractions : 2 - 3 = 2 + (-3)
- moins par moins ça fait plus : -2 * -1 = 2

## Exercices

### Exercice 1 - 28/08/2024
\begin{align*}
A(x) &= -3 - 2x^2 + 2x - 1x^2 \times 3 -4 \\
B(x) &= 2x - 8 + 2x^2 - (3x + 1) \\
\end{align*}

<details>
<summary>Correction exercice 1 A(x)</summary>
\begin{align*}    
A(x) &= -3 - 2x^2 + 2x - 1x^2 \times 3 -4 \\
&= -3 - 2x^2 + 2x - 3x^2 - 4  && \text{je regarde les opérations prioritaires, ici, c'est une multiplication, donc je la traite en premier comme si elle était entre parenthèses :  $1x^2 \times 3 = 1 \times x^2 \times 3 = 1 \times 3 \times x^2  = 3 \times x^2$} \\
&= -2x^2 - 3x^2 + 2x - 4 - 3 && \text{il ne reste plus d'opération prioritaire, je peux commencer à simplifier l'équation en regroupant les objets de mêmes natures $x^2$ ensemble, $x$ et les tous nus tout en conservant les signes à gauche des objets} \\
&= -5x^2 + 2x - 7 && \text{je ne peux plus simplifier mon equation, elle est sous la forme $ax^2 + bx + c$ j'ai donc terminé} \\
\end{align*}
</details>


<details>
<summary>Correction exercice 1 B(x)</summary>
\begin{align*} 
B(x) &= 2x - 8 + 2x^2 - (3x + 1) \\
&= 2x - 8 + 2x^2 - 1 \times (3x + 1) && \text{je vois qu'il y a une opération prioritaire entre parenthèse, je ne peux pas la simplifier, mais je peux enlever les parenthèses afin de pouvoir simplifier avec le reste de l'opération, je regarde le signe du chiffre devant la parenthèse, c'est un $-1$ donc pour ouvrir la parenthèse, j'inverse les signes dedans (en gros, je multiplie par $-1$ : $3x$ et $1$}\\
&= 2x - 8 + 2x^2 - 3x -1 \\
&= 2x^2 + 2x - 3x - 8 - 1 && \text{je peux simplifier en regroupant les objets de même type en conservant les signes à gauche des objets} \\
&= 2x^2 - x - 9 \\
\end{align*}
</details>


### Exercice 2 - 29/08/2024
\begin{align*}
A(x) &= -x + (2 - 3x^2 +1) -3(x + 1) \\
B(x) &= -2x^2 - (2x + 3 + 8x^2) + 1 \\
\end{align*}

Bonus : \
\begin{align*}
f(x) = -3 - 2[ (2x + 1) - (x^2 - 1) ]
\end{align*}

<details>
<summary>Correction exercice 2 A(x)</summary>
\begin{align*}    
A(x) &= -x + (2 - 3x^2 +1) -3(x + 1) \\
&= -x + 2 - 3x^2 +1 -3(x + 1) && \text{je vois 2 opérations prioritaires, je peux commencer par celle que je veux, mais je préfère la faire dans l'ordre, donc j'enlève les parenthèses de $(2 - 3x^2 +1)$, je conserve les signes puisque qu'on ne multiplie pas par un nombre négatif (ici il n'y a rien devant donc c'est comme si c'était $1 \times (2 - 3x^2 +1)$ } \\
&= -x + 2 - 3x^2 +1 -3x - 3 && \text{deuxième opération prioritaire $-3 \times (x + 1)$, c'est une multiplication par un nombre négatif donc on inverse les signes en multipliant par 3} \\
&= -3x^2 -x - 3x +2 + 1 - 3 && \text{plus d'opération prioritaire, donc je commence à regrouper les objets entre eux pour simplifier}\\
&= -3x^2 -4x + 0 && \text{j'ai rajouté + 0 à la fin pour ne pas te perdre, mais on ne le garde pas pour simplifier au max}\\
&= -3x^2 -4x\\
\end{align*}
</details>


<details>
<summary>Correction exercice 2 B(x)</summary>
\begin{align*}    
B(x) &= -2x^2 - (2x + 3 + 8x^2) + 1 \\
&= -2x^2 - 2x -3 -8x^2 + 1 && \text{Je ne peux rien simplifier dans la parenthèse, donc je l'enlève afin de pouvoir regrouper avec le reste, je fais attention au signe devant} \\
&= -2x^2 -8x^2 -2x -3 + 1 && \text{je regroupe les objets entre eux, en conservant le signe} \\
&= -10x^2 -2x -2
\end{align*}
</details>


<details>
Pour l'exercice Bonus, il y a 2 solutions possibles, libre à toi de choisir la solution que tu préfère (je pense que la solution 1 t'embrouillera moins)
<summary>Correction du bonus de l'exercice 2 f(x) solution 1</summary>
\begin{align*}    
f(x) &= -3 - 2[ (2x + 1) - (x^2 - 1) ]\\
&= -3 - 2[2x + 1 -x^2 + 1] && \text{première parenthèse, pas besoin d'inverser les signe, car devant, c'est positif, la seconde, j'inverse les signes} \\
&= -3 - 2[ -x^2 + 2x + 1 + 1] && \text{je regroupe dans les crochets} \\
&= -3 - 2[ -x^2 + 2x + 2] &&  \text{je simplifie dans les crochets} \\
&= -3 + 2x^2 - 4x - 4 &&  \text{je multitplie $-2$ au contenu des crochets, c'est un chiffre négatif, je fais bien attention d'inverser les signes} \\
&= 2x^2 - 4x - 4 -3 && \text{je regroup} \\
&= 2x^2 -4x - 7 && \text{je simplifie} \\
\end{align*}
</details>


<details>
<summary>Correction du bonus de l'exercice 2 f(x) solution 2</summary>
\begin{align*}    
f(x) &= -3 - 2[ (2x + 1) - (x^2 - 1) ]\\
&= -3 - 2(2x + 1) + 2(x^2 - 1) && \text{je décide d'ouvrir les crochets, mais dans ce cas, il faut multiplier $-2$ aux 2 blocs $(2x+1)$ et $-(x^2 -1)$ je fais attention aux signes} \\
&= -3 - 4x -2 + 2(x^2 - 1) && \text{je développe en suivant les opérations prioritaires, pour ouvrir les parenthèses, je dois multiplier les éléments à l'intérieur par le chiffre devant, car il est négatif} \\
&= -3 - 4x -2 + 2x^2 - 2 && \text{je développe en suivant les opérations prioritaires, pour ouvrir les parenthèses, je dois multiplier les éléments à l'intérieur par le chiffre devant qui est positif, donc on conserve les signes} \\
&= -2x^2 - 4x -2 -3 -2 && \text{je regroupe} \\
&= 2x^2 - 4x -7 && \text{je simplifie} \\
\end{align*}
</details>


### Exercice 3 - 30/08/2024
\begin{align*}
A(x) &= -3x(x + 2) - 2(x+2)\\
B(x) &= -x[2x + 2 - (3x-4)] \\
\end{align*}

Bonus : \
\begin{align*}
f(x) = (2x+1)^2
\end{align*}
