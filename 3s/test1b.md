---
title:  Terza verifica di Matematica
author: Versione B
date:	Febbraio 2021
---

## Testo

### Esercizio 1

Determinare la lunghezza della corda staccata dalla retta di equazione $$y=4$$ sulla circonferenza di centro $$C=(-2,3)$$ e raggio $$r=\sqrt{10}$$.

[Soluzione](#esercizio-1-1)

### Esercizio 2

Consideriamo la circonferenza di equazione $$x^2 + y^2 + 4y - 9 = 0$$ e il punto $$P=(-3,0)$$.

* Quante sono le rette tangenti alla circonferenza passanti per $$P$$?
* Scrivere l'equazione delle rette tangenti alla circonferenza passanti per $$P$$.

[Soluzione](#esercizio-2-1)

### Esercizio 3

Scrivere l'equazione delle rette tangenti alla circonferenza di equazione $$x^2 + y^2 - 6x + 2y + 5 = 0$$ e parallele alla retta di equazione $$x - 2y = 5$$.

[Soluzione](#esercizio-3-1)

## Svolgimento

### Esercizio 1

Conoscendo centro e raggio, possiamo subito scrivere l'equazione della circonferenza:

$$(x + 2)^2 + (y - 3)^2 = 10$$

Troviamo i due punti di intersezione $$A$$ e $$B$$ della corda con la circonferenza risolvendo il sistema

$$
    \left\{\begin{array}{l}
        (x + 2)^2 + (y - 3)^2 = 10\\
        \\
        y = 4
    \end{array}\right.
$$

Sostituendo il valore $$y = 4$$ nella prima equazione otteniamo un'equazione di secondo grado nella sola variabile $$x$$, che possiamo facilmente risolvere:

$$(x + 2)^2 = 9 \, \longrightarrow \, x + 2 = \pm 3 \, \longrightarrow \, x = -2 \pm 3$$

Per cui $$A = (-5, 4)$$ e $$B = (1, 4)$$. Infine, poiché gli estremi della corda $$A$$ e $$B$$ si trovano alla stessa altezza $$y$$, la lunghezza della corda $$AB$$ è semplicemente

$$\overline{AB} = x_B - x_A = 6$$

[Top](#testo)

### Esercizio 2

È facile verificare che il punto $$P$$ appartiene alla circonferenza: infatti, sostituendo le sue coordinate ($$x = -3$$ e $$y = 0$$) nell'equazione della circonferenza si ottiene un'uguaglianza vera. Di conseguenza, c'è **un'unica retta tangente** alla circonferenza e passante per $$P$$, di equazione

$$y - y_P = m (x - x_P) \longrightarrow y = m (x + 3)$$

Il centro della circonferenza è il punto $$C = (0, -2)$$ e il coefficiente angolare della retta $$CP$$ risulta

$$m_{CP} = \frac{y_C - y_P}{x_C - x_P} = - \frac23$$

Essendo perpendicolare alla retta $$CP$$, la retta tangente passante per $$P$$ ha coefficiente angolare

$$m = -\frac{1}{m_{CP}} = \frac32$$

In conclusione, l'equazione cercata è

$$y = \frac32 (x + 3) \longrightarrow y = \frac32 x + \frac92$$

[Top](#testo)

### Esercizio 3

Portando l'equazione in forma normale, vediamo che la retta $$x - 2y = 5$$ ha coefficiente angolare $$m = 1/2$$, infatti

$$x - 2y = 5 \longrightarrow y = \frac12 x - \frac52$$

Di conseguenza, poiché rette parallele hanno lo stesso coefficiente angolare, le rette tangenti che stiamo cercando hanno equazione del tipo

$$y = \frac12 x + q \longrightarrow x - 2y + 2q = 0$$

Con il metodo del completamento dei quadrati possiamo trasformare l'equazione della circonferenza in

$$(x - 3)^2 + (y + 1)^2 = 5$$

da cui si vede immediatamente che il centro della circonferenza è il punto $$C = (3, -1)$$ e il suo raggio è $$r = \sqrt{5}$$. A questo punto basta calcolare la distanza $$d$$ della retta $$x - 2y + 2q = 0$$ dal centro $$C$$ e trovare per quali valori di $$q$$ risulta $$d = r$$.

$$
    d = \frac{\vert 3 - 2 \cdot (-1) + 2q \vert}{\sqrt{1^2 + 2^2}} = \frac{\vert 2q + 5 \vert}{\sqrt{5}}
$$

Risolviamo dunque l'equazione

$$
    \frac{\vert 2q + 5 \vert}{\sqrt{5}} = \sqrt{5} \,\longrightarrow\, \vert 2q + 5 \vert = 5 \,\longrightarrow\, 2q + 5 = 5 \vee 2q + 5 = -5 \,\longrightarrow\, q = 0 \vee q = -5
$${:.scroll-wrapper}

Concludiamo che le due rette che verificano le condizioni richieste hanno equazione

$$x - 2y = 0 \quad \text{e} \quad x - 2y - 10 = 0$$

[Top](#testo)
