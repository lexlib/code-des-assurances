# Article Annexe A331-2

Le tableau suivant est utilisé pour justifier le calcul des taux par échéance mentionnés au b du 1° de l'article A. 331-2 :

<pre>
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┯━━━━━━━━━━━━━━━┯━━━━━━━━━┯━━━━━━━━━━━━━┯━━━━━━━━━━━━━━━━━━━━━━━━━┯━━━━━━━━━━━━━━━━━━━━━━━━━┓
┃                               │               │ EXER-   │ N +1        │ k = N + i pour i = 2,   │ k = N + i pour i > 5    ┃
┃                               │               │ CICE N  │             │ 3, 4 et 5               │                         ┃
┠┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┨
┃ Obligations                   │ (A)           │ A(N)    │ A(N + 1)    │ A(k)                    │ A(k)                    ┃
┠┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┨
┃ Obligations arrivées à terme  │ (B)           │         │ A(N) - A(N  │ B(k) = A(k - 1) - A(k)  │ B(k) = A(k - 1) - A(k)  ┃
┃ dans l'année                  │               │         │ + 1)        │                         │                         ┃
┠┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┨
┃ Coupons de l'année            │ (C) = TME *   │         │ A(N + 1) *  │ C(k) = A(k) * TME       │ C(k) = A(k) * TME       ┃
┃                               │ (A)           │         │ TME         │                         │                         ┃
┠┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┨
┃ Coupons et réinvestissements  │ (D)           │         │ B(N + 1)*(1 │ D(k) = [B(k) + C(k - 1) │ D(k) = [B(k) + C(k - 1) ┃
┃ d'obligations capitalisés     │               │         │ + 75 %*TME) │ + D(k - 1)] * (1+75     │ + D(k - 1)] * (1 + 60   ┃
┃                               │               │         │             │ %*TME)                  │ %*TME)                  ┃
┠┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┨
┃ Autres actifs                 │ (E)           │ E(N)    │ E(N) * (1 + │ E(k) = E(k - 1) * (1 +  │ E(k) = E(k - 1) * (1 +  ┃
┃                               │               │         │ 75% * TME)  │ 75% * TME)              │ 60 % * TME)             ┃
┠┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┨
┃ TOTAL ACTIF                   │ (F) = (A) +   │ F(N)    │ F(k) F(N)   │ F(N + 1)                │ F(k)                    ┃
┃                               │ (C) + (D) +   │         │             │                         │                         ┃
┃                               │ (E)           │         │             │                         │                         ┃
┠┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┼┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┨
┃ TAUX DE RENDEMENT             │ (G)           │         │ F(N + 1)/   │ F(k)/F(k - 1) - 1       │ F(k)/F(k - 1) - 1       ┃
┃                               │               │         │ F(N) - 1    │                         │                         ┃
┠┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┴┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┴┈┈┈┈┈┈┈┈┈┴┈┈┈┈┈┈┈┈┈┈┈┈┈┴┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┴┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┈┨
┃ (A) Montant des obligations et titres assimilés non échus, net des provisions pour dépréciation durable à                 ┃
┃ la date d'inventaire, sans prise en compte des surcotes et décotes. (B) Obligations et titres assimilés                   ┃
┃ arrivés à terme dans l'année considérée. (C) Coupons de l'année considérée, déterminés sur la base du taux                ┃
┃ moyen des emprunts d'Etat calculé sur base semestrielle appliqué au montant des obligations. (D) Coupons                  ┃
┃ versés au cours des exercices précédents et obligations échues réinvestis, capitalisés à un taux égal à 75                ┃
┃ % du taux moyen des emprunts de l'Etat français calculé sur base semestrielle si la date d'échéance de                    ┃
┃ paiement considérée est inférieure à 5 ans, 60 % de ce même taux moyen sinon. (E) Pour les autres actifs,                 ┃
┃ le montant retenu est celui des placements mentionnés dans les tableaux a, b, et d à h de l'état détaillé                 ┃
┃ figurant au point 3.II.1.4.A1 de l'annexe à l'article A. 344-3, autres que ceux mentionnés aux 1°, 2°, 2°                 ┃
┃ bis et 2° ter de l'article R. 332-2, capitalisé à un taux égal à 75 % du taux moyen des emprunts de l'Etat                ┃
┃ français calculé sur base semestrielle si la date d'échéance de paiement considérée est inférieure à 5                    ┃
┃ ans, 60 % de ce même taux moyen sinon.                                                                                    ┃
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
</pre>


Les entreprises devront également préciser l'unité des montants renseignés dans le tableau, qui pourront être exprimés en
euros, en milliers d'euros, ou en millions d'euros.

**Liens relatifs à cet article**

_Créé par_:

  - Arrêté du 23 décembre 2008 - art. 2
