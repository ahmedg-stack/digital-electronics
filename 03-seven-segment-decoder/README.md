# Seven-Segment Decoder

**PLTW Digital Electronics, 2025–26** · Multisim + TinkerCAD

## Problem
Use logic gates to drive a **common-cathode seven-segment display** so it shows a fixed multi-digit sequence, one character per input state, from three inputs **X, Y, Z** (000 to 111).

**Constraints:** common-cathode display, 3-input gates only, simplified logic, current-limiting resistors, K-map simplification.

## Design
1. Wrote a truth table mapping each of the 8 input states to the 7 segment outputs (a–g).
2. Made a **separate K-map for each segment** and simplified each output.
3. Reused shared logic where the same character appeared more than once in the sequence.
4. Built the full AOI circuit in Multisim, then converted parts of it to **NAND-only** and **NOR-only** forms.
5. Built at least two segments on a breadboard in **TinkerCAD**, with current-limiting resistors.

*Schematics and truth tables for this project are intentionally not published.*

## What I learned / what I'd change
I came to really understand the difference between common-cathode and common-anode displays, and how to debug logic both in software and by drawing it out on paper. Next time I'd build the TinkerCAD circuit step by step instead of all at once, so I wouldn't get lost in my own logic.

If I rebuilt this on a PLD, I'd define X, Y, and Z as inputs and enter the truth table or Boolean equations directly, instead of wiring individual gates.
