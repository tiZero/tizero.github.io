---
title: Successione di Fibonacci
author: Formula chiusa per il termine generale della successione
date: Maggio 2021
---

La _successione di Fibonacci_ $$F_n$$ è la successione numerica definita per $$n \geq 0$$ dalle seguenti proprietà:

$$
  \begin{aligned}
    F_0 &= 0\\
    F_1 &= 1\\
    F_{n+2} &= F_{n+1} + F_n
  \end{aligned}
$$

I primi termini della successione di Fibonacci sono

$$0 \quad 1 \quad 1 \quad 2 \quad 3 \quad 5 \quad 8 \quad 13 \quad 21 \quad \cdots$$

---

Osserviamo che l'equazione di secondo grado $$x^2 = x + 1$$ ha due soluzioni di segno opposto:

$$\phi = \frac{1 + \sqrt5}{2} \quad \text{e} \quad \psi = \frac{1 - \sqrt5}{2}$$

La soluzione positiva $$\phi$$ (tradizionalmente chiamata [_sezione aurea_](https://it.wikipedia.org/wiki/Sezione_aurea)) presenta numerose particolarità matematiche, tra cui uno stretto legame con la successione di Fibonacci.

### Esercizio

Dimostrare che il termine generale $$F_n$$ della successione di Fibonacci è dato dalla formula seguente:

$$F_n = \frac{\phi^n - \psi^n}{\phi - \psi} \qquad \text{per ogni } n \geq 0$$

###### Risoluzione guidata

Verificare che la formula

- è valida per $$n = 0$$ e per $$n = 1$$.
- soddisfa la relazione ricorsiva $$F_{n+2} = F_{n+1} + F_n$$.

---

### Svolgimento (Flora)

Verifichiamo la relazione $$F_{n-2} + F_{n-1} = F_n$$ sostituendo a $$F_n$$ l'espressione la sua espressione secondo il termine generale.

<div class="scroll-wrapper">
$$
  \frac{\phi^{n-2} - \psi^{n-2}}{\phi - \psi} + \frac{\phi^{n-1} - \psi^{n-1}}{\phi - \psi} = \frac{\phi^n - \psi^n}{\phi - \psi}
$$
</div>

Essendo $$\phi - \psi = \sqrt5$$ possiamo togliere i denominatori:

<div class="scroll-wrapper">
$$
  \phi^{n-2} - \psi^{n-2} + \phi^{n-1} - \psi^{n-1} = \phi^n - \psi^n
$$
</div>

Ricordiamo però dalle proprietà delle potenze che $$a^m \cdot a^n = a^{m+n}$$ e dunque possiamo riscrivere l'uguaglianza come

<div class="scroll-wrapper">
$$
  \phi^n \cdot \phi^{-2} - \psi^n \cdot \psi^{-2} + \phi^n \cdot \phi^{-1} - \psi^n \cdot \psi^{-1} = \phi^n - \psi^n 
$$
</div>

Tale espressione è però semplificabile come segue raccogliendo $$\phi^n$$ e $$\psi^n$$:

$$
  \phi^n(\phi^{-2}+\phi^{-1} - 1) - \psi^n(\psi^{-2}+\psi^{-1} - 1) = 0
$$

Sostituendo i valori noti otteniamo

<div class="scroll-wrapper">
$$
  \phi^n \cdot \left(\frac{2}{3 + \sqrt5} + \frac{2}{1 + \sqrt5} - 1 \right) - \psi^n \cdot \left(\frac{2}{3 - \sqrt5} + \frac{2}{1 - \sqrt5} - 1 \right) = 0
$$
</div>

Risolvendo però le espressioni numeriche evinciamo ciò:

$$
  \phi^n \cdot 0 - \psi^n \cdot 0 = 0
$$

Essendo dunque $$0 = 0$$ riteniamo dimostrata la validità del termine generale.
