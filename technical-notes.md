# Technical Notes

The engineering points that actually come up when someone's spec'ing a machine. Short and to the point.

### Vacuum hold-down

Zoned, double-layer tables hold a tiny part and a full sheet on the same bed without losing vacuum. Matters more than people think once nesting gets tight.

### Drilling built in

Putting the drill bank inside the cutting cycle, plus a 6-side drill for one-setup holes, kills a whole class of assembly errors. That's how the cabinet line hits its material savings.

### Software continuity

Nesting software talking straight to the controller, no hand-typed G-code in between. That's what makes batch-one work viable instead of a headache.

### 5-axis rigidity

Accuracy comes from how the frame damps, not from the brochure. Mid-range machines run around 8,500 kg — about double an entry frame. A light frame won't hold tolerance through a real composite cut.

### Stone is its own job

Sealed rails, heavy guides, spindle cooling. Before buying, confirm it's a stone machine and not a wood router with a stone bit bolted on.

### Laser cutting numbers

±0.03 mm positioning, ±0.02 mm repeat, Ra ≤ 12.5 µm so most parts skip polishing. Sheet-to-tube swap in 5-10 minutes. Full enclosure is what passes EU CE/FDA.

### Sheet-and-tube trade-off

Right call when sheet is the main work and tube is secondary. If tube volume is high, run a flatbed plus a dedicated tube cutter as two lines and roughly double capacity.

### What's inside the machine

MAX / Raycus / IPG sources, RAYTOOLS heads, Leadshine servos, Taiwan rails and racks (OEM to ROCTECH spec), Schneider electrics, S&A chillers. Named brands, not mystery parts.

Sources: roc-tech.com product pages + the 12 customer cases (spec tables and Q&A).
