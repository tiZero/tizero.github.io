---
title:  Terza verifica di Matematica
author: Versione A
date:   Gennaio 2021
---
## Testo

### Esercizio 1

Considerati i punti $$A=(3,0)$$ e $$B=(0,2)$$ nel piano cartesiano, determinare la posizione reciproca della retta $$AB$$ e della circonferenza di equazione $$x^2 + y^2 + 2(x + y) = 7$$.

[Soluzione](#esercizio-1-1)

### Esercizio 2

Scrivere l'equazione delle rette tangenti alla circonferenza di equazione $$x^2 + y^2 + 4x + 8y + 16 = 0$$ e passanti per il punto $$P=(-4,0)$$.

[Soluzione](#esercizio-2-1)

### Esercizio 3

Scrivere l'equazione della circonferenza di centro $$C=(-1,0)$$ e tangente alla retta di equazione $$x - y= 3$$.

[Soluzione](#esercizio-3-1)

## Svolgimento

### Esercizio 1

Determiniamo l'equazione della retta $$AB$$: essendo una retta non verticale, la sua equazione è del tipo $$y = mx + q$$. Facilmente deduciamo che $$q = 2$$ (infatti la retta passa per il punto $$B=(0,2)$$) e che

$$
    m = \frac{y_A - y_B}{x_A - x_B} = - \frac23
$$

Dunque la retta $$AB$$ ha equazione $$y = -\frac23 x + 2$$.

A questo punto possiamo considerare il sistema costituito dalle due equazioni della retta e della circonferenza:

$$
    \left\{\begin{array}{l}
    x^2 + y^2 + 2x + 2y - 7 = 0\\
    \\
    y = -\frac23 x + 2
    \end{array}\right.
$$

Sostituendo la variabile $$y$$ nella prima equazione, otteniamo l'equazione risolvente

$$
    x^2 + \left( -\frac23 x + 2\right)^2 + 2x + 2\left( -\frac23 x + 2\right) - 7 = 0
$$

che in forma normale diventa $$13 x^2 - 18x + 9 = 0$$. Poiché $$\Delta < 0$$,[^1] concludiamo che il sistema non ha soluzioni: di conseguenza, **la retta è esterna rispetto alla circonferenza** (cioè non c'è alcun punto di intersezione tra le due curve).

[Top](#testo)

### Esercizio 2

Con il metodo di completamento dei quadrati possiamo trasformare l'equazione della circonferenza in

$$
    (x + 2)^2 + (y + 4)^2 = 4
$$

Da qui ricaviamo immediatamente che il centro della circonferenza è il punto $$C = (-2,-4)$$ e il raggio è $$r = 2$$. Calcolando la distanza del punto $$P$$ dal centro $$C$$ troviamo che

$$
    \overline{CP} = \sqrt{(x_C - x_P)^2 + (y_C - y_P)^2} = \sqrt{2^2 + 4^2} = \sqrt{20} = 2 \sqrt{5} > r
$${:.scroll-wrapper}

Concludiamo che il punto $$P$$ è esterno alla circonferenza e, di conseguenza, che le rette tangenti passanti per $$P$$ sono due.

La generica retta passante per $$P = (-4,0)$$ ha equazione $$y = m(x + 4)$$, che in forma normale diventa

$$
    mx - y + 4m = 0
$$

A questo punto basta calcolare la distanza $$d$$ della retta dal centro $$C$$ e trovare per quali valori di $$m$$ si ha $$d = r$$.

$$
    d = \frac{\vert m \cdot (-2) - (-4) + 4m \vert}{\sqrt{m^2 + 1}} = \frac{\vert 2m + 4 \vert}{\sqrt{m^2 + 1}}
$$

Risolviamo dunque l'equazione

$$
    \frac{\vert 2m + 4 \vert}{\sqrt{m^2 + 1}} = 2
$$

Elevando al quadrato ed eliminando i denominatori, otteniamo l'equazione $$(2m + 4)^2 = 4(m^2 + 1)$$, che in forma normale diventa

$$
    4m + 3 = 0
$$

Essendo un'equazione di primo grado, abbiamo come unica soluzione $$m = -\frac34$$ a cui corrisponde la retta tangente

$$
    y = -\frac34(x + 4) \longrightarrow y = -\frac34 x - 3
$$

Tuttavia, poiché le rette tangenti devono necessariamente essere due, l'altra retta non può che essere la **retta verticale** passante per $$P$$,[^2] cioè la retta di equazione

$$
    x = x_P \longrightarrow x = -4
$$

[Top](#testo)

### Esercizio 3

La generica circonferenza di centro $$C =(-1,0)$$ ha equazione

$$
    (x + 1) + y^2 = r^2
$$

dove $$r$$ è il raggio (incognito) della circonferenza.

Affinché la retta $$x - y - 3 = 0$$ sia tangente alla circonferenza è necessario che il raggio $$r$$ sia uguale alla distanza $$d$$ della retta dal centro.

$$
    d = \frac{\vert (-1) - 0 - 3 \vert}{\sqrt{1^2 + 1^2}} = \frac{4}{\sqrt{2}} = 2\sqrt{2}
$$

Concludiamo che il raggio della circonferenza è $$r=2\sqrt{2}$$ e, di conseguenza, che l'equazione della circonferenza è

$$
    (x+1)^2 + y^2 = 8
$$

[Top](#testo)

[^1]: Qui conviene calcolare $$\Delta/4 = 9^2 - 13 \cdot 9 = -36$$
[^2]: Da un buon disegno si può dedurre immediatamente che una delle due rette tangenti è necessariamente verticale
