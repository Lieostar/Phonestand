## Project Phone Stand

*A lightweight and functional phone stand designed in SolidWorks and optimized for 3D printing. Made in spite of me not having a good phone stand in the first place.*

---

## Overview

This repository contains the CAD files and documentation for a custom phone stand designed using SolidWorks (MMGS units). The stand features a pivoting back arm that allows multiple viewing angles and can be fabricated via 3D printing or CNC machining.

## Features

* **Two-Part Design**: Consists of a back and a front body.
* **Manufacturable Geometry**: All edges have fillets and chamfers to improve printability, comfort, and style.
* **Robust Construction**: Designed for PLA or ABS plastic with a thickness optimized for stability.

## Tools & Techniques Used

* **SolidWorks Features**: Extrude Boss/Base, Extruded Cut, Fillet, Chamfer, Circular Pattern
* **Assembly Mates**: Concentric Mate (pivot pin)
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
/PhoneStand
├── Phone Stand Assembly.SLDASM # Assembly file
├── STL/                       # Exported STL files for 3D printing
│   ├── Phone Stand Back.SLDPRT
│   └── Phone Stand Front.SLDPRT
├── Phone Stand Back.SLDPRT    # Pivoting arm part file
├── Phone Stand Front.SLDPRT   # Pivoting arm part file
├── README.md                  # Project overview and instructions
├── Stand Image 1.png          # Showcase image of assembly
└── Stand Image 2.png          # Showcase image of assembly
```

## Assembly Instructions

1. Open `Phone Stand Assembly.SLDASM` in SolidWorks.
2. Ensure `Phone Stand Front.SLDPRT` is fixed.
3. Mate `Phone Stand Back.SLDPRT` with the fixed point on the front stand.


## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
