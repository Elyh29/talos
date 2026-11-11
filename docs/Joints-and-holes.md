# Joints and holes

The screw's axis is followed through every part it crosses (one ray per part, so parts that touch are all found).
Each part gets its own hidden cutter in a « Holes · part » collection, cut by one Boolean modifier « Fastener Holes ».

| Joint | Holes |
|---|---|
| **Into the Part Below** | clearance in the first part; tapped hole in the part below (clearance only if there is none) |
| **Through Bolt** | clearance through every part, washer and nut at the exit |
| **Single Part** | clearance in the first part only (through, or as deep as the screw) |
| **Tapped in the Part** | screwed into the clicked part itself |

A part farther than 2 d (at least 5 mm) beyond an empty gap is not part of the joint (the far wall of a tube, for instance).

## Holes
- **Clearance**: ISO 273, fine / medium / coarse series.
- **Counterbore** (cap screws sunk in): DIN 974-1. **Countersink**: 90°.
- **Tapped**: ISO 2306 tap drill, thread 1.5 d in the part (Auto Length).
- **Pins**: reamed hole Ø d H7 in each part. **Shoulder screws**: bore Ø d H8 in the first part, tapped below.

## Auto Length
The shortest standard length that gives 1.5 d of thread in a tapped part, or leaves 2 threads beyond a nut.

## Solver
*Auto* uses **Manifold** on closed parts (Blender 4.5 and later: fast and exact), **Exact** otherwise, and **Fast** on heavy parts of
older Blenders.
