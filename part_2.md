**Zusammenfassung des zweiten Crashkurs-Tages (VWL 1)**

Nachfolgend findest du eine komprimierte Übersicht über die im Transkript behandelten Themen. Dabei geht es v. a. um mikroökonomische Grundlagen rund um Konsumentenentscheidungen, Produktion und Kosten. 

---

## 1. Wiederholung: Wichtige Rechenschritte (aus Tag 1)

- **Marktgleichgewicht**  
  $`
    D(p) = S(p).
  `$
  Man setzt Nachfrage und Angebot gleich, um den Gleichgewichtspreis $`p^*`$ und die -menge $`q^*`$ zu erhalten.

- **Elastizitäten (Wiederholung)**  
  - Preiselastizität, Einkommenselastizität (Formeln vom Vortag).  
  - Einsetzen und Ableiten wie zuvor besprochen.

- **Spieltheorie – gemischte Strategien**  
  (nur kurze Wiederholung, u. a. Gefangenen-/Dilemma-Situation und Nash-Gleichgewichte.)

---

## 2. Präferenzen und Nutzenfunktionen (Fortsetzung)

### 2.1 Indifferenzkurven
- **Definition**: Eine Indifferenzkurve enthält alle Güterbündel, die für einen Konsumenten (bzw. Haushalt) _gleich gut_ sind (gleicher Nutzen).
- **Arten**:
  1. **Perfekte Substitute**: Indifferenzkurven verlaufen linear. Nutzenfunktion typischerweise $`u(x_1, x_2)=a\,x_1 + b\,x_2`$.  
  2. **Perfekte Komplemente**: „Leontief“-Form $`\min(a\,x_1,\;b\,x_2)`$. Indifferenzkurven im rechten Winkel („L“-Form).  
  3. **Quasilinear**: Eine Variable tritt (z. B.) in einer Wurzelfunktion/Log-Funktion auf + lineare Summation bei der anderen. Form: $`u(x_1,x_2)=f(x_1)+x_2`$.  
  4. Weitere Sonderfälle wie neutrale Güter, Bad-Güter, Sättigungspunkt etc.

### 2.2 Positive monotone Transformationen
- Nur **die Rangordnung** der Güterbündel ist relevant (d. h. ordinales Konzept).  
- Man darf Nutzenfunktionen additiv verschieben, positiv skalieren, potenzieren oder logarithmieren, solange das Vorzeichen oder die Ordnung nicht verändert wird.  

### 2.3 Grenzrate der Substitution (MRS)
- **MRS** = Steigung der Indifferenzkurve = $`-\,\tfrac{\partial u/\partial x_1}{\partial u/\partial x_2}`$.  
- Sie zeigt, in welchem Verhältnis der Haushalt bereit ist, Gut 2 gegen Gut 1 einzutauschen (an einem bestimmten Punkt der Indifferenzkurve).  

### 2.4 Optimale Entscheidung (Haushalt)
- Haushalt wählt das Güterbündel, das **maximalen Nutzen** bringt und dennoch in sein Budget passt:  
  1. **Budgetgerade**: $`p_1\,x_1 + p_2\,x_2 = m`$.  
  2. **Optimale Bedingung** (bei strengen Präferenzen):  
     $`
       \text{MRS} = \frac{p_1}{p_2}
       \quad\text{(Betrag der Steigungen: Indifferenzkurve = Budgetgerade)}.
     `$
- Sonderfälle: perfekte Substitute (Richtung „alles oder Mischung“), perfekte Komplemente (Mengenverhältnis fest), quasilinear (kritischer Wert bei einem Gut, dann Umstieg auf das andere).

---

## 3. Slutsky-Zerlegung (Substitutions- & Einkommenseffekt)

Wenn sich der **Preis** eines Gutes ändert, verändert sich auch dessen Nachfrage. Dieser Gesamteffekt lässt sich in **zwei Teile** aufspalten:

1. **Substitutionseffekt**:  
   - Man substituiert (tauscht) relativ zum neuen Preis.  
   - Formal wird ein fiktives Einkommen $`m'`$ verwendet, damit der Haushalt auf denselben Nutzenniveau bleibt wie zuvor, aber zum neuen Preis kalkuliert.  
   - Nachfrageänderung zwischen $`(p_1, p_2, m)`$ und $`(p_1', p_2, m')`$.

2. **Einkommenseffekt**:  
   - Zusätzlich verbleibt (bei Preissenkung) oder fehlt (bei Preissteigerung) dem Konsumenten Einkommen („Kaufkraft“).  
   - Nachfrageänderung zwischen $`(p_1', p_2, m')`$ und $`(p_1', p_2, m)`$.

Vorgehen beim Berechnen (Schema):
1. **Altes Optimum**: $`x_1^*(p_1,p_2,m)`$.  
2. **Neues Optimum**: $`x_1^*(p_1',p_2,m)`$.  
3. **Fiktives Einkommen** $`m' = m + (p_1' - p_1)\cdot x_1^*`$.  
4. **Substitutionsoptimum**: $`x_1^{SE} = x_1^*(p_1', p_2, m')`$.  
5. **Substitutionseffekt**: $`\Delta x_1^{SE} = x_1^{SE} - x_1^*(p_1,p_2,m)`$.  
6. **Einkommenseffekt**: $`\Delta x_1^{IE} = x_1^*(p_1',p_2,m) - x_1^{SE}`$.  

---

## 4. Produktionstheorie

### 4.1 Produktionsfunktion
- **Inputs**: $`x_1,x_2,\dots`$ (z. B. Arbeit, Maschinen, Material)  
- **Output**: $`y`$ = hergestellte Menge.  
- **Produktionsfunktion** $`f(x_1,x_2)`$: maximaler Output bei gegebenen Inputs.  

### 4.2 Grenz- und Durchschnittsprodukt
- **Grenzprodukt** (MP): partielle Ableitung der Produktionsfunktion, analog zum Grenznutzen.  
  $`
    MP_1 = \frac{\partial f}{\partial x_1},\quad
    MP_2 = \frac{\partial f}{\partial x_2}.
  `$
- **Durchschnittsprodukt** (AP): Output $`y`$ pro Einheit eines bestimmten Inputs (z. B. $`x_1`$).  
  $`
    AP_1 = \frac{f(x_1,x_2)}{x_1}.
  `$

### 4.3 Skalenerträge
- **Konstante** Skalenerträge: Vervielfachen der Inputs um $`a`$ ⇒ Output erhöht sich *exakt* um $`a`$.  
- **Steigende** Skalenerträge: Output steigt *überproportional* zur Erhöhung der Inputs.  
- **Sinkende** Skalenerträge: Output steigt *unterproportional*.  

### 4.4 Grenzrate der technischen Substitution (TRS)
- Entspricht formal der MRS bei Konsum:
  $`
    TRS = -\,\frac{MP_1}{MP_2}.
  `$
- Steigung der Isoquante (Linie aller Inputkombinationen, die denselben Output $`y`$ erzeugen).

---

## 5. Kosten und Gewinn

### 5.1 Kostenfunktion
- **Gesamtkosten** = variable Kosten + ggf. Fixkosten.  
  $`
    C(x_1,x_2) = w_1\,x_1 + w_2\,x_2 \;(+\;\text{Fixkosten } F).
  `$
  - $`w_i`$ = Preis pro Einheit des Inputfaktors $`x_i`$.

### 5.2 Kostenminimierung und Faktorwahl
- Unternehmen will z. B. ein bestimmtes $`y`$ *kostenminimal* herstellen ⇒ gesucht ist eine kostengünstige Kombination $`(x_1^*,x_2^*)`$.  
- **Bedingung** (analog zu MRS = Preisverhältnis):  
  $`
    TRS = \frac{w_1}{w_2}
    \quad\text{(mit part. Ableitungen als MP)}.
  `$
- Einsetzen in die Produktionsfunktion $`f(x_1,x_2)=y`$ ⇒ Bestimmung der „bedingten Faktornachfrage“ nach $`x_1`$ bzw. $`x_2`$ in Abhängigkeit von $`y`$.

### 5.3 Lang- und kurzfristige Betrachtung, Fixkosten
- Kurzfristig fallen Fixkosten (z. B. Miete) oft unvermeidbar an; langfristig können alle Kosten variabel werden.  

### 5.4 Durchschnitts- und Grenzkosten
- **Durchschnittskosten** (AC): $`\tfrac{C(y)}{y}`$.  
- **Durchschnittlich variable Kosten** (AVC): $`\tfrac{C(y)-F}{y}`$ (ohne Fixkosten).  
- **Grenzkosten** (MC): $`\tfrac{dC(y)}{dy}`$.

### 5.5 „Shutdown“-Bedingung (kurzfristig)
- Wenn der Marktpreis $`p`$ < AVC, wird kurzfristig die Produktion eingestellt (jede zusätzliche Einheit würde Verlust vergrößern).  
- Liegt $`p`$ dagegen zwar unter AC, aber über AVC, kann das Unternehmen kurzfristig weiterproduzieren, um zumindest einen Teil der Fixkosten zu decken.

---

## 6. Tipps zum Lernen / Klausur

1. **Formeln** verstehen, nicht nur auswendig lernen. Viele Rechenschritte (z. B. Slutsky, Budgetgleichungen, partielle Ableitung) sind ähnlich.  
2. **Standard-Schemata** üben (MRS=Preisverhältnis, TRS=Inputpreisverhältnis, Gewinnmaximierung über Ableitungen).  
3. **Tutorien- und Übungsaufgaben** intensiv trainieren: Dort finden sich fast alle „typischen“ Rechenarten.  
4. **Zeitmanagement**: In der Klausur ist pro Aufgabe nur wenige Minuten Zeit → schnelles, fehlerfreies Vorgehen.

---

**Fazit**  
Der zweite Kurstag vertieft die Konsumentenentscheidungen (Slutsky-Zerlegung, weitere Präferenztypen) und überträgt das Gesehene auf den Produktionsbereich (Produktionsfunktion, Kostenminimierung, Gewinnmaximierung). Die zentralen „Bausteine“ – partielle Ableitungen, Budget-/Kosten-Gleichungen, MRS/TRS-Bedingungen – wiederholen sich ständig. Wer die Rechenwege und Grundprinzipien sicher beherrscht, hat gute Chancen, in der VWL-Klausur erfolgreich zu sein.
