# Troubleshooting

| Message | What to do |
|---|---|
| *X is not a closed mesh* | Holes may be missing or wrong. Mesh ‣ Clean Up ‣ Merge by Distance, fill the holes of the mesh, or Solidify a surface. |
| *the hole was not cut in X* | The Boolean failed: usually an open mesh. Try another *Solver* (Exact). |
| *X: N faces, holes are slow to cut* | Use the Manifold solver (Blender 4.5+). |
| *too short / does not reach / only N mm of thread* | Turn *Auto Length* on, or pick a longer screw. |
| *X touches Y* | Two screws (heads, nuts or shanks) overlap. |
| *no room for the wrench beside Y* | A hexagon head or nut needs about 1.9 × its width across flats around it for a socket. |
| *No thin nut in M2: ISO 4032 instead* | That nut or washer is not made in this size; the plain one is used. |
| *Y is right under X: choose « Into the Part Below »* | You picked *Tapped in the Part* on a part lying on another one. |
| *a pin holds two parts* | A dowel pin should cross into a second part (1.5 d). |
| *already registered as a subclass* when enabling Talos | Restart Blender once, then enable Talos again. |

Holes are cut in the part's **evaluated** mesh: modifiers above « Fastener Holes » (Bevel, Mirror…) are drilled too.
