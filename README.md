# Bewehrungsmodell Unterzug Pos. 441 – AR-Ansicht

Web-Anwendung zum Betrachten eines Bewehrungsmodells im Browser und in
Augmented Reality (Android: Scene Viewer/WebXR, iPhone/iPad: Quick Look).

- `index.html` – AR-Ansicht mit Varianten (1:50, 1:25, Ausschnitt 1:1, 1:10, 1:5, 1:1),
  Präsentationsfahrt, Stereo-3D (Rot/Cyan, Side-by-Side), Maßen und Farblegende nach Ø
- `modell/unterzug-441-modell.html` – interaktives Modell mit Stahlliste
- `models/` – Modelle als GLB und USDZ

Positionen lassen sich nach Gruppen einblenden und antippen (Browser und
VR-/MR-Brillen). Auf Android-Handys startet AR im Scene Viewer (stabil, ohne
Marken), auf iPhone/iPad in Quick Look.

Direkt starten per Link-Anker, z. B. `#m10` (Maßstab 1:10 für den Boden), `#m5` (1:5), `#ganz` (1:1),
`#praesentation` oder `#3d`.

**Fertigteilträger:** Schalter „Fertigteilträger“ (Link-Anker `#ft`, z. B. `#m10-ft`) blendet die Querträger
ein, Lage aus der Ansicht geschätzt (Raster 1,20 m, Trapezquerschnitt). Gilt auch in AR.

**Vor Ort (Testzweig):** `vorort.html` legt das 1:1-Modell in WebXR (Chrome auf Android) auf eine
echte Stütze (17, 15, 13, G/12). Man tippt die linke und rechte untere Ecke einer Stützenseite an;
das Modell wird daraus ausgerichtet, im Raum verankert und lässt sich in 1-cm- und 0,5°-Schritten
nachstellen.

Lagen mit dem Vermerk „Lage geschätzt“ sind im Modell plausibel angeordnet,
aber nicht aus dem Plan bestimmt. Das Modell dient der Anschauung in der Lehre
und ersetzt keine Ausführungsunterlage.
