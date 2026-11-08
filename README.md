# 3D-Printed-Gearbox
A compact gearbox designed in SolidWorks and 3D printed.

## Specs
- Gear ratio: 20.4:1
- Material: PLA
- Printer changes : The initial solid aluminium axles from early design concepts to 3D printable DfAM (Design for Additive Manufacturing) PLA axles. Utilising the 30% gyroid infill setting, the axles underwent a 54% mass reduction (65.9g to 30.3g) while also improving the torque transmission capacity.
- Slicer settings (Ulti-maker Creality Slicer): 30% Gyroid infill for axles, 0.17m layer height, 0.28mm initial layer height, no supports needed.

## Folder contents
- `solidworks/` - original part and SLDPRT and SLDASM files
- `stl/` - print-ready STL files
- `step/` - assembly in STEP format

## Notes
- Axles were printed in halves to allow enacting forces on the beam to be perpendicular to layer direction as each half axle was printed horizontally on the print bed.
- 0.4mm z-offset for axle 1, and a 0.9mm z-offset for axles 2 and 3, Axle 1 used the same keyed joint CAD design as Axle 2 and 3, scaled down 33%.
- The 16-tooth gear with a 20˚ Pressure Angle (PA) was selected to ensure geometric compatibility with standard SolidWorks toolbox spur gears.  While using the 12-tooth gear increased the gear reduction ratio, it also increased the risk of nonconjugate action and accelerated wear due to a mismatched PA.
