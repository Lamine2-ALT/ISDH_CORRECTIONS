# Corrigé: Manipulations de racines et rationalisation de dénominateurs : un parcours complet.

---

## 1°) Simplification de t

Soit $t=\sqrt{45}+\sqrt{196}-\sqrt{180}-\sqrt{245}$

On simplifie chaque terme :
$$t = \sqrt{9 \times 5}+\sqrt{196}-\sqrt{36 \times 5}-\sqrt{49 \times 5}$$
$$t = 3\sqrt{5} + 14 - 6\sqrt{5} - 7\sqrt{5}$$
$$t = 3\sqrt{5} - 6\sqrt{5} - 7\sqrt{5} + 14$$
$$t = (3 - 6 - 7)\sqrt{5} + 14$$
$$t = -10\sqrt{5} + 14$$

**Réponse :** $a = -10$, $b = 5$ et $c = 14$

---

## 2°) Étude des réels x et y

### a) Rationalisation du dénominateur

Soit $x=\frac{4}{7+3\sqrt{5}}$. On multiplie par le conjugué :
$$x = \frac{4}{7+3\sqrt{5}} \times \frac{7-3\sqrt{5}}{7-3\sqrt{5}} = \frac{4(7-3\sqrt{5})}{(7+3\sqrt{5})(7-3\sqrt{5})}$$

En utilisant l'identité remarquable $(a+b)(a-b) = a^2 - b^2$ avec $a = 7$ et $b = 3\sqrt{5}$ :
$$x = \frac{4(7-3\sqrt{5})}{7^2 - (3\sqrt{5})^2} = \frac{4(7-3\sqrt{5})}{49 - 45} = \frac{4(7-3\sqrt{5})}{4} = 7-3\sqrt{5}$$

**Réponse :** $x = 7-3\sqrt{5}$

### b) Signe de y

Soit $y=3\sqrt{5}-7$. Pour comparer $3\sqrt{5}$ et $7$, on compare leurs carrés :
$$(3\sqrt{5})^2 = 9 \times 5 = 45 \quad \text{et} \quad 7^2 = 49$$

Puisque $45 < 49$, on a $(3\sqrt{5})^2 < 7^2$. Comme deux nombres positifs sont rangés dans le même ordre que leurs carrés, on obtient $3\sqrt{5} < 7$, donc $y = 3\sqrt{5} - 7 < 0$.

**Réponse :** $y$ est négatif.

### c) Relation entre x et y

Calculons $-y$ :
$$-y = -(3\sqrt{5}-7) = -3\sqrt{5}+7 = 7-3\sqrt{5}$$

Or d'après a), $x = 7-3\sqrt{5}$. Donc $x = -y$.

### d) Encadrement de x

On sait que $2,236< \sqrt{5}< 2,237$. En multipliant par 3 :
$$6,708 < 3\sqrt{5} < 6,711$$

En multipliant par $-1$ (l'ordre change) :
$$-6,711 < -3\sqrt{5} < -6,708$$

En ajoutant 7 :
$$0,289 < 7-3\sqrt{5} < 0,292$$

**Réponse :** À $10^{-2}$ près, $0,28 < x < 0,30$

---

## 3°) Calcul de $\sqrt{z}$

Soit $z=(x-y)^{2}$. D'après 2°c), on sait que $x = -y$, donc :
$$z = (-y - y)^{2} = (-2y)^{2} = 4y^{2}$$

Par conséquent :
$$\sqrt{z} = \sqrt{4y^{2}} = 2\sqrt{y^{2}} = 2|y|$$

Or d'après 2°b), $y < 0$, donc $|y| = -y$. Ainsi :
$$\sqrt{z} = 2(-y) = -2y$$

**Conclusion :** $\sqrt{z}=-2y$