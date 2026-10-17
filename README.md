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
`#vorort` bzw. `#vorortstahl` (Knoten G/12 in 1:1 zum Ausrichten am Bauwerk),
`#praesentation` oder `#3d`.

Lagen mit dem Vermerk „Lage geschätzt“ sind im Modell plausibel angeordnet,
aber nicht aus dem Plan bestimmt. Das Modell dient der Anschauung in der Lehre
und ersetzt keine Ausführungsunterlage.
