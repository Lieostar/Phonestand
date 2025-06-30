## Project Phone Stand

*A lightweight and functional phone stand designed in SolidWorks and optimized for 3D printing. Made in spite of not having a good phone stand in the first place.*

---

## Overview

This repository contains the CAD files, STL exports, and rendered images for a custom-designed phone stand created in SolidWorks using MMGS units. The project showcases key design techniques, including extrusion, filleting, and chamfering.

## Features

* **Two-Part Design**: Consists of a support piece and a front body.
* **3D Printer Ready: Clean, manifold STL files included for rapid prototyping.
* **Ergonomic Design: Filleted and chamfered edges for comfort and aesthetics.

## Tools & Techniques Used

* **SolidWorks Features**: Extrude Boss/Base, Extruded Cut, Fillet, Chamfer
* **Assembly Mates**: Angle Mate
* **Units**: Millimeters, Grams, Seconds (MMGS)

## Technical Specifications

| Component             | Dimension / Parameter     |
| --------------------- | ------------------------- |
| Base Length           |                  100  mm  |
| Base Width            |                   80  mm  |
| Base Thickness        |                   10  mm  |
| Front Length          |                  160  mm  |
| Front Width           |                   80  mm  |
| Front Thickness       |                   10  mm  |
| Angle Positions       |               70 degrees  |


## File Structure
```
Phone-Stand-Project/
├── Phone-Stand-Assembly.SLDASM     # Full assembly file
├── Phone-Stand-Front.SLDPRT        # Base/front component
├── Phone-Stand-Front.STL           # STL file for base
├── Phone-Stand-Support.SLDPRT      # Adjustable support arm
├── Phone-Stand-Support.STL         # STL file for arm
├── README.md                       # Project description and instructions
├── Stand-Image-1.png               # Render/image of final assembly
└── Stand-Image-2.png               # Additional view/render
```

## Assembly Instructions

1. Open `Phone-Stand-Assembly.SLDASM` in SolidWorks.
2. Insert `Phone-Stand-Front.SLDPRT` and `Phone-Stand-Support.SLDPRT` into the assembly.
3. Ensure `Phone-Stand-Front.SLDPRT` is fixed.
4. Mate `Phone-Stand-Support.SLDPRT` with the fixed point on the front stand.

## Future Improvements

* Make the design have adjustable angles to view a phone at
* Modify for tablet-sized devices with longer width
* Look into adding wireless changing integrated into the design

