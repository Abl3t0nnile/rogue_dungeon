# Bewegung kinematischer Körper im 2-dimensionalen Raum

Die Bewegung kinematischer Körper im 2-dimensionalen Raum basiert auf den physikalischen Grundsätzen der *Kinetik*. Durch die Bewegungsrichtung und die Geschwindigkeit im Bezug zur Zeit ...

## Koordinatensystem

Die Darstellung von Objekten auf dem Bildschirm findet immer in Bezug zur Basis $O = (0, 0)$, als obersten, linken Pixel statt. Dadurch werden Bewegungen nach links oder rechts, als negative oder positive Werteveränderungen eines Punktes aus der $x$ Achse und Bewegungen nach oben oder unten, als negative oder Positive Wertveränderungen auf der $y$ Achse definiert. Die Skala wird mit 1 als Breite eines Pixels definiert. Da jeder Punkt in der Ebene einen einzelnen Pixel auf dem Bildschirm repräsentiert, sind negative Koordinaten nicht darstellbar und können somit ignoriert werden.

## Konstante, Variablen und Formeldefinition

Die kleinsten Einheiten für **Entfernung** und **Zeit** werden als $px$ für einen Pixel und $\delta$ für die vergangene Zeit seit dem letzten gerenderten Bild definiert. $\delta$ wird im Kontext dieser Berechnungen als Konstante aufgefasst, obwohl sich der Wert durch starke Rechenlast verändern kann. Läuft die Simulation mit einer konstanten Bildrate von 60 Frames pro Sekunde ist $\delta$ konstant $\frac{1}{60}$. Fällt die Bildrate unter diesen Wert, steigt der Wert von $\delta$, was für eine flüssigere Bewegung sorgt und Ruckeln verhindert.

Der **Reibungskoeffizient** $\mu$ als Kraft die einer Bewegung entgegenwirkt. In der Realität ist der Reibungskoeffizient keine Konstante und wird von vielen Faktoren beeinflusst. Im Rahmen dieser einfachen Implementation von Bewegung wird $\mu$ allerdings als konstante Größe innerhalb einer Simulation definiert und kann beliebig angepasst werden, um das Bewegungsgefühl zu beeinflussen.

Der **Basisvektor** $\vec{v_0} = \begin{bmatrix} 0 \cr -1 \end{bmatrix}$ steht für die Ausrichtung eines 

Der **Drehwinkel** $\phi$ in Grad der Abweichung vom Basisvektor $\vec{v_0}$

### Acceleration / Beschleunigung

$$
\vec{a} = {\Delta \vec{v} \over \Delta t}
$$


### Velocity / Geschwindigkeit

$$
\vec{v} = {\vec{s} \over \Delta t}
$$

### Displacement / Positionsveränderung

$$
\vec{s} = v\vec{d}
$$

### Speed / Tempo

$$
v = {|\vec{s}| \over \Delta t}
$$

### Direction / Richtung

...

## Direkte Bewegung in 4 oder 8 Richtungen

Fußgänger, Lebewesen ...

Basisvektor $\vec{v_0} = \begin{bmatrix} 0 \cr 0 \end{bmatrix}$

## Fortbewegung auf Rädern

Autos ...

## Fortbewegung im Vakuum

Raumschiffe ...
