# With Ichno (technical drawings)

Ichno 1.0.7 and later read what Fasteners placed:

- **Hole callouts** (ISO 129-1), grouped: `4 × Ø6.6 ⌴ Ø11 ↧ 6.4` (counterbore), `2 × Ø5.5 ⌵ Ø11.6 × 90°` (countersink), `M5 ↧ 8`
  (tapped, blind), `Ø5.6 ↧ 9.1 (M4)` (insert), `Ø5 H7` (pin), `Ø2.55 ↧ 9 (M3)` (self-tapping pilot). Every Fasteners hole of a view is
  called out, whatever their number.
- **Threads** (ISO 6410-1): seen end-on, a tapped hole gets the thin three-quarter circle at its nominal diameter; seen from the side,
  a screw gets the thin line at the root of its thread where it is visible, and a tapped hole drawn without its screw gets hidden thin
  lines at its nominal diameter.
- **Bill of materials** with full designations in the drawing's language: `Screw ISO 4762 M6 × 20 – 10.9`, `Nut ISO 4032 M6 – 10`,
  `Washer ISO 7089 6 – 300 HV`, `Threaded insert M4 × 8.1`, `Dowel pin ISO 8734 5 × 16`, `Threaded rod DIN 976 M8 × 60`.
- **Sections**: in front, side and top sections, screws, nuts, washers and pins crossed by the plane stay whole (ISO), drawn cleanly with
  the drive recess in thin lines, the hatching stopping at their outline; in isometric sections they are cut, never hatched.
- **Clean drawing**: in front, side and top views, Talos parts are drawn from their description (outlines, head, flats, drive recess,
  nuts, washers), each line seen or hidden — not from their mesh; in isometric views and sections, only their sharp edges.
- Screws, nuts and inserts are never taken for holes; cutters are never drawn.
