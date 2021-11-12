---
layout: post
title: "Partnerinterview Drehmoment"
---

Ablauf
---
*   Partnerarbeit
    *   Studieren Sie die Lösungen:
        *   Mensch A: Studiert die Lösung von Aufgabe 1.
        *   Mensch B: Studiert die Lösung von Aufgabe 2.
    *   Ziel: Sie werden eine Expertin dieser Aufgabe! 
    *   Im Anschluss stellen Sie Ihre Aufgabe ihrem Partner.
    *   Das Ziel ist, das dieser zur algebraischen Lösung kommt (**ohne** die Lösung zu studieren, **nur** durch Anleitung der Expertin).
    *   Unterstützen Sie sich dabei gegenseitig.
    *   Schauen Sie, dass Sie mindestens jeweils die erste Teilaufgabe gelöst bekommen.
*   Falls Sie Druckfehler finden wäre ich für eine Meldung dankbar!

Aufgabe 1: Hebel
-----

Stellen Sie Sich vor, Sie sind auf einer Wanderung.
Der Weg wird aber von einem grossen Felsbrocken der Masse $m_1 = 100~kg$ versperrt.
Sie müssen den Stein anheben, um ihn aus dem Weg zu räumen, damit Sie ihre Wanderung fortsetzen können.
Glücklicherweise haben Sie einen stabilen Wanderstock der Länge $l = 2~m$ dabei und können Physik!
Sie nehmen Ihren Wanderstock, legen sich einen Drehpunkt mit Abstand $r_1 = 10~cm$ vom Felsbrocken.
1.  Wie viel Kraft müssen Sie ausüben, um den Stein anzuheben (bzw. zu balancieren)?
2.  Stellen Sie sich vor, Sie müssten mit dieser Kraft eine Masse aufheben. Wie gross wäre diese?
3.  Was ist die Bedingung, damit sich dieses Unterfangen lohnt, d.h. wie gross/klein muss $r_1$ gewählt werden?  

<img src="/assets/hebel-wanderer-edited.png" style="width: 80%;">

> Situation in Aufgabe 1: Steine aus dem Weg räumen. Quelle: Giancoli, Physics.

1.   Gegeben sind $m_1 = 100~kg$, $r_1 = 0.10~m$ und $l = 2~m$.
Gesucht ist die Kraft für das Anheben $F_2$ in $N$.
Der zweite **Hebelarm** ist $r_2 = l - r_1 = 1.9~m$.
Für das balancieren brauchen wir $\sum M = M_1 + M_2 = 0$
Dabei ist $M_1 = r_1 F_1$ (Drehung gegen den Uhrzeigersinn) mit $F_1 = m_1 g$
und $M_2 = -r_2 F_2$ (Drehung im Uhrzeigersinn).
In dem wir $\sum M = 0$ nach $F_2$ auflösen, erhalten wir die Lösung
$$
    F_2 = \frac{r_1 m g}{r_2} = \frac{r_1 m g}{l - r_1} \approx \frac{0.1~m * 100~kg * 10~m/s^2}{1.9~m} \approx 50~N.
$$

2.   Gegeben sind $F_2 = 50 N$.
Gesucht ist eine Masse $m_2$ in $kg$.
Die Gewichtskraft ist $F = m g$, darum ist die Lösung
$$
    m_2 = \frac{F_2}{g} = \frac{r_1 m }{l - r_1} \approx 5~kg.
$$

3.  Das lohnt sich falls $\eta = \frac{F_2}{F_1} < 1$. Wir suchen also $r_1$ in $m$.
Gemäss obiger Formel für $F_2$ ist das Resultat also
$$
    \eta = \frac{r_1}{r_2} = \frac{r_1}{l-r_1} < 1.
$$
Dies gilt, wenn $r_1 < l - r_1$ also wenn $0~m < r_1 < 1~m$. &nbsp; :white_check_mark: 

Aufgabe 2: Wippe
----
Versetzen Sie Sich in Ihre Kindheit zurück. 
Beim Spielen auf der Wippe sind die Kinder in der Regel nicht gleich schwer.
Nehmen wir an, dass Alice $m_A = 30~kg$ und Bob $m_B = 25~kg$ miteinander auf der Wippe sind.
Die Wippe ist für unsere Zwecke immer ausreichend Lang und Alice sitzt so, dass ihr Hebelarm $r_A = 2.5~m$ ist.
1.  Wo muss sich Bob hinsetzen, damit das balancieren funktioniert? In anderen Worten: Was ist Bobs Hebelarm?
2.  Angenommen Bobs Hebelarm ist auch $2.5~m$. Wo müsste sich Charlie $m_C = 15~kg$ hinsetzen, 
damit die Wippe stabil bleibt?
3.  Wie schwer müsste Charlie sein, damit er sich in $r_C = 1~km$ dazusetzen kann. Existiert so ein Charlie?

<img src="/assets/wippe-think-pair-edited.png" style="width: 80%;">

> Situation in Aufgabe 2: Mit Alice und Bob auf dem Spielplatz. Quelle Giancoli, Physics.

1.  Gegeben sind $m_A = 30~kg$, $m_B = 25~kg$ und $r_A = 2.5~m$.
Gesucht ist $r_B$ in $m$.
Die Bedingung $\sum M = M_A + M_B = 0$ ist nötig, damit es nicht beginnt zu drehen.
Da Alice links sitzt ist $M_A = + r_A m_A g$. 
Für Bob haben wir dafür $M_B = - r_B m_B g$.
Wir finden die Lösung
$$
    r_B = \frac{r_A m_A}{m_B} \approx 3~m.
$$

2. Zusätzlich gegeben ist $m_C = 15~kg$ und $r_B = 2.5~m$ und gesucht ist $r_C$.
Die Bedingung für kein Schaukelbeginn ist $\sum M = M_A + M_B + M_C = 0$.
Da der Betrag von $M_B$ kleiner wird, sind die ersten zwei Drehmomente zusammen immer noch positiv und somit muss $M_C = -r_C m g$ negativ sein.
Die Lösung ist durch Auflösen nach $r_C$ gegeben durch
$$
    r_C =  \frac{m_A r_A - m_B r_B}{m_C} \approx  0.8~m.
$$

3. Hier ist $r_C = 10~km = 10^3~m$ gegeben und $m_C$ gesucht in $kg$.
Für die Lösung stellen wir die Formel aus 2. nach $m_C$ um und erhalten
$$
    m_C =  \frac{m_A r_A - m_B r_B}{r_C} \approx 1.25 * 10^{-2}~kg.
$$
Diese Masse ist zu klein für einen Charlie! &nbsp; :disappointed:
