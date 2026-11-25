COILCRAFT 0805CS-080XJRC — ALTIUM REFERENCE PACK
=================================================

This pack contains reference artwork and dimensions to build an Altium Designer
SchLib component and PcbLib footprint. It does NOT contain native Altium .SchLib
or .PcbLib binary/library files.

PART
- Manufacturer: Coilcraft
- MPN: 0805CS-080XJRC
- Inductance: 8.2 nH
- Tolerance: ±5%
- Package: 0805 (2012 metric)
- Two terminals; non-polarized

PCB LAND PATTERN (Coilcraft 0805CS family drawing)
- Pad 1 size: 1.78 mm × 1.02 mm
- Pad 2 size: 1.78 mm × 1.02 mm
- Pad centre-to-centre pitch: 1.78 mm
- Inner edge-to-edge gap: 0.76 mm
- Suggested footprint name: L_0805CS_Coilcraft
- Suggested pad numbers: 1 and 2
- Suggested solder mask expansion: use your PCB fabrication house rules.
- Suggested paste: 1:1 pad opening initially; verify stencil/process requirements.
- The DXF contains the two pad rectangles and body outline as reference geometry.
  DXF geometry is NOT copper pad objects; convert/recreate as actual Altium pads.

SCHEMATIC
- Suggested component designator: L?
- Suggested comment/value: 8.2 nH
- Two passive pins, numbered 1 and 2.
- Pin electrical type: Passive.
- Symbol is non-polarized.

ALTIUM SETUP
1. Create a new Integrated Library project or separate SchLib and PcbLib.
2. In the SchLib, create a component named 0805CS-080XJRC.
3. Draw a standard inductor coil symbol and add two Passive pins numbered 1 and 2.
4. Set the component parameters: Manufacturer=Coilcraft, Manufacturer Part Number=0805CS-080XJRC,
   Inductance=8.2 nH, Package=0805 (2012 metric).
5. In the PcbLib, create footprint L_0805CS_Coilcraft.
6. Place two actual SMD pads, each 1.78 mm × 1.02 mm, centred at (0,+0.89 mm)
   and (0,-0.89 mm). Number them 1 and 2.
7. Add a Top Overlay body outline only if desired; do not let silkscreen overlap
   solderable pads. Add courtyard/assembly outlines per your library standard.
8. In the SchLib, use Models / Add Footprint to link L_0805CS_Coilcraft.
9. Compile the Integrated Library and inspect the footprint in 2D/3D before release.

IMPORTANT RF NOTE
The datasheet-recommended land pattern should be followed for soldering. For RF
layout, keep the connection path short and symmetric, and validate the final
layout against your board stackup and operating frequency. The footprint is a
land pattern, not an RF model.

OFFICIAL REFERENCES
- Coilcraft 0805CS series: https://www.coilcraft.com/en-us/products/rf/ceramic-core-chip-inductors/0805-%282012%29/0805cs/
- Coilcraft 0805CS datasheet / physical characteristics are available from the series page.
- Mouser product page advertises an ECAD Model for this MPN:
  https://www.mouser.com/ProductDetail/Coilcraft/0805CS-080XJRC
- DigiKey product page:
  https://www.digikey.com/en/products/detail/coilcraft/0805CS-080XJRC/21380988

Verify the manufacturer's latest drawing before fabrication.
