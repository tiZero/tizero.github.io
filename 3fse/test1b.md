---
title:  Terza verifica di Fisica
author: Versione B
date:   9 febbraio 2021
---
## Testo

### Esercizio 1

Un treno viaggia a velocità costante. Dall’ultima carrozza un oggetto viene lanciato verso l’esterno a una velocità di 52 m/s in direzione opposta a quella di marcia. Tuttavia, un osservatore a terra vede l’oggetto lanciato proseguire nella stessa direzione del treno a 10 m/s.

* Qual è la velocità del treno B rispetto ai binari?
* Il treno costituisce un riferimento inerziale? Perché?
* Supponiamo di essere sul treno, in un vagone isolato senza finestrini. È possibile effettuare un esperimento per determinare a quale velocità stiamo viaggiando?

[Soluzione](#esercizio-1-1)

### Esercizio 2

Dopo essere stata lanciata orizzontalmente a una velocità di 24 m/s, una palla da baseball (140 g) viene rispedita indietro dal battitore a 35 m/s, in direzione perfettamente orizzontale.

* Determinare la variazione di quantità di moto della palla
* Sapendo che la palla è rimasta a contatto con la mazza per $$0,\!001$$ s, calcolare la forza media esercitata dal battitore sulla palla.

[Soluzione](#esercizio-2-1)

### Esercizio 3

Un blocco di massa $$m = 2,\!4$$ kg si trova su un piano perfettamente liscio e inclinato di un angolo $$\theta = 40^\circ$$ rispetto alla direzione orizzontale. Il blocco è tenuto fermo con una fune come in figura. Determinare il valore della tensione nella fune.

![test1b](img/test1b.svg)

[Soluzione](#esercizio-3-1)

## Svolgimento

### Esercizio 1

Indicando con $$S$$ e $$S'$$ i due sistemi di riferimento rispettivamente del suolo e del treno, rappresentiamo la situazione con un disegno:

![test1a-1](img/test1b-1.svg)

Rispetto ad un asse $$x$$  diretto come in figura, i dati a nostra disposizione sono $$v' = -52$$ m/s (velocità dell'oggetto lanciato rispetto al treno) e $$v = 10$$ m/s (velocità dell'oggetto lanciato rispetto al suolo).

* Il testo chiede di calcolare il valore di $$V$$, cioè la velocità del treno ($$S'$$) rispetto a $$S$$, che possiamo dedurre dalla **trasformazione di Galileo** delle velocità:

  $$
      v' = v - V \, \longrightarrow V = v - v' = 10 - (-52) = 62 \text{ m/s}
  $${:.scroll-wrapper}

* Il treno è un sistema di riferimento inerziale poiché viaggia a velocità costante.

* Il **principio di relatività** di Galileo afferma che la legge fondamentale della dinamica $$\vec{F} = m\vec{a}$$ è valida in *qualsiasi* sistema di riferimento inerziale: in particolare, qualsiasi esperimento di dinamica darà lo stesso esito indipendentemente dalla velocità del treno.

[Top](#esercizio-1)

### Esercizio 2

Rispetto all'asse $$x$$ fissato orizzontalmente come in figura, le due velocità (iniziale e finale) della pallina sono rispettivamente

$$v_i = 24 \,\mathrm{m/s} \quad\text{e}\quad v_f = -35 \,\mathrm{m/s}$$

![test1a-2](img/test1b-2.svg)

* Dalla definizione di quantità di moto $$p = mv$$, possiamo facilmente calcolare la variazione $$\Delta p$$ come segue:

   $$
   \Delta p = p_f - p_i = mv_f - mv_i = m(v_f - v_i)= 0,\!140 \cdot \left(- 35 - 24\right) = - 8,\!26 \,\mathrm{kg \cdot m/s}
   $${:.scroll-wrapper}

* Il **teorema dell'impulso** afferma che $$F \cdot \Delta t = \Delta p$$, dove $$F$$ è la forza (media) esercitata dalla mazza del battitore sulla pallina e $$\Delta t = 0,\!001$$ s è il tempo di contatto. Con una semplice formula inversa ricaviamo

   $$
   F = \frac{\Delta p}{\Delta t} = \frac{-8,\!26}{0,\!001} = -8\,260 \,\mathrm{N}
   $$

[Top](#esercizio-2)

### Esercizio 3

Nello schema di corpo libero rappresentiamo tutte le forze agenti sul blocco, scegliendo un asse $$x$$ di riferimento con direzione parallela a quella del piano inclinato:

![test1a-3](img/test1b-3.svg)

Le tre forze sul blocco sono

* il peso $$\vec{P}$$ del corpo diretto verso il basso
* la reazione vincolare $$\vec{R}$$ del piano d'appoggio
* la **tensione** $$\vec{T}$$ esercitata dalla corda

Poiché il blocco è fermo, la risultante delle forze agenti su di esso è nulla (**principio d'inerzia**):

$$
    \vec{P} + \vec{R} + \vec{T} = 0
$$

Considerando le componenti lungo l'asse $$x$$ dei vettori coinvolti in questa equazione, troviamo la relazione scalare

$$
\begin{aligned}
    P_x + R_x + T_x &= 0\\
    -mg \sin \theta + 0 + T &= 0
\end{aligned}
$$

da cui possiamo facilmente ricavare il valore $$T$$ della tensione presente nella fune:

$$
    T = mg \sin \theta = 2,\!4 \cdot 9,\!81 \cdot \sin 40^\circ = 15,\!13 \, \mathrm{N}
$${:.scroll-wrapper}
[Top](#esercizio-3)
