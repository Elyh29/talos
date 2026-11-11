# Placing screws

## Place by Clicking
1. In the **Talos** panel, choose the screw (type, size, length or *Auto Length*), its drive, head and joint — every choice is a sketch.
2. Press **Place by Clicking**. A ghost of the real screw follows the mouse on the parts, with its holes and a label
   (designation, holes, distance to the nearest edge, warnings).
3. **Click** to pin the preview. Change the screw from the panel or with the keys below: the preview follows.
4. **Enter** places it. **Esc** unpins; **Esc** or **right-click** again ends the tool.

**Shift+click** places at once, without pinning. **Ctrl** snaps to vertices, edge middles and face centres.

| Key | While the preview is pinned |
|---|---|
| ↑ ↓ | size |
| ← → | length (turns Auto Length off) |
| J | next joint |
| M | magnet on / off (hold Alt to ignore it) |

## Magnet and grid
The magnet draws the screw to the rows and columns of the screws already on the face, to the middle between two of them and to the
face centre, with pink guides like Photoshop's smart guides. *Grid* snaps to a grid of that step from the corner of the face.

## Other ways
- **Add at 3D Cursor**: the preview opens pinned at the cursor, on the nearest face of the active object.
- In Edit Mode, **Add on Selected Faces** places a screw at the centre of each selected face (or one per selected vertex).
- **Section Card** shows a section through the screw axis in the preview: parts hatched, hole, thread.

## Where things go in the Outliner

Talos keeps the scene tidy in one **Talos** collection:

- **Fasteners** ‣ one collection per standard and size (*ISO 4762 M3*, *ISO 4017 M6*…), each screw with its nut, washers and insert under it;
- **Holes** ‣ *Holes · Part*, the hidden cutters of each drilled part (not rendered).

Your parts stay where they are. Move a screw into a collection of your own and Talos leaves it there, even when you edit it.
Screws placed somewhere else (in a scene made by hand, or moved around)? **Tidy Collections** puts them all back.
