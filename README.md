# 🌌 SpaceTimeGlobe

A buildable **3D spacetime globe** model for 3D printing and laser cutting.
Assemble a sleek, transparent globe that illustrates spacetime geometry using simple bolts, rods, and laser-cut plates.

---

## 🧩 What’s Included

From the `repository_root/` you’ll find:

* **Corner and edge 3D‑printable frames**

  * `corner_piece_*` (x 4)
  * `edge_piece_*` (x 4)
* **Laser‑cut plates**

  * `hyperbola_plate.svg/.dxf` (4 mm low‑friction material, e.g., plexiglass)
  * `top_plate.svg/.dxf` (4 mm transparent plexiglass)
* **Lattice blocks** (designed for 3D printing)
* **Assembly.FCStd** – example with 4 lattice blocks
* Full FreeCAD source files

  * `Dimensions.FCStd` – size‐reference file
  * Other FCStd models update automatically when reopened & recomputed
* Step files for export: print-ready
* Reference images: `006.png`, `008.png`, and others

---

## 🛠️ Hardware & Materials Needed

* **M3 × 10 mm countersunk bolts and nuts**

  * \~12 for frame assembly, plus \~8 for plates
* **Laser-cut plates:**

  * Hyperbola plate: 4 mm low‑friction material (plexiglass suggested)
  * Top plate: 4 mm transparent plexiglass
* **Aluminium rods:** 6 mm diameter × 25 mm long (quantity depends on lattice blocks)
* Optional: lattice-block pins (not every block requires one)

---

## 🧭 Assembly Instructions

### 1. Frame Assembly

1. Print 4 corner pieces and 4 edge pieces.
2. Align and bolt into a cube-style frame using M3 × 10 mm countersunk bolts from the top, nuts secured underneath.
3. Ensure all nuts are seated flush in the bottom holes.

### 2. Hyperbola Plate

1. Laser-cut plate
2. Carefully countersink the four pre-lasered bolt holes.
3. Bolt the plate onto the assembled frame using M3 × 10 bolts and nuts.

### 3. Lattice Blocks & Rods

1. 3D print the default 16 lattice blocks (as in design).
2. Refer to `006.png` to insert the 6 mm × 25 mm aluminium rods through the blocks.
3. Only some blocks require pins—these are optional and not shown; customize per your design.

### 4. Top Plate

1. Laser-cut with the provided design (again, adjust if globally resized).
2. Bolt into position over the lattice‑rod assembly using M3 × 10 bolts and nuts.

### 5. Final Check

See `Assembly.FCStd` and `008.png` for a visual example with four blocks. Ensure bolts are snug and rods slide freely.

---

## 🛠️ Customizing Sizes

* Modify **only** `Dimensions.FCStd` (your master parameter file).
* Re-open every other `.FCStd` file afterward and click “Recompute” so they reflect the new size.
* Re-export STEP files and laser files as needed for printing or cutting.

---

## 🧠 Tips & Notes

* Always countersink bolt holes in laser-cut parts for flush mounting.
* For altered dimensions, change the Dimenions.FCStd file and recompute all other files
* Lattice-block pin placement is a bit of a mess atm but I do not have the diagram ready yet. Not all blocks should have a pin.

---

## 🎯 Quick Start Checklist

* [ ] Print 4 corner + 4 edge pieces
* [ ] Laser-cut hyperbola + top plates
* [ ] Assemble frame with M3 bolts & nuts
* [ ] Attach hyperbola plate
* [ ] Print lattice blocks and insert rods
* [ ] Bolt on top plate
* [ ] Enjoy your SpaceTimeGlobe!

---

Feel free to tweak as needed—and congratulations on this beautiful functional design!
