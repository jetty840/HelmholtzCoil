INSTRUCTIONS: https://hackaday.io/project/7409-highly-configurable-3d-printed-helmholtz-coil

SUMMARY:

Helmholtz coils contain a region of uniform magnetic field which is common used to measure the strength of magnets, measure electrical charges at the atomic level and nulling out earths magnetic field. The magnetic field calculation is done for you (no math).

This project uses OpenScad which is a 3D Solid modeler for 3D printing. OpenScad has the advantage that it's a programming language, which lends itself to heavy customization. You can custom everything, and if you don't like it or need something else, then change it.

Output in the OpenScad console details the coil configuration, wire length, field strength per Amp / mA and the maximum capacity of the coil:

Helmholtz Coil Configuration Statistics:
    AWG: 30
    Coil Diameter: 21cm
    Coil Turns: 3
        25649.22370 nT / 0.25649 Gauss per amp
        25.649224 nT per mA
        Wire length per coil: 1.98m
        Combined resistance of both coils: 0.001342Ohms
        Voltage required to drive coil: 0.00026979Volts @ 0.201Amps
        Maximum magnetic coil capacity: 5155.49396nT for
        the provded gauge
        Usable Volume (Cylinder): 105Length(mm) x 70Diameter(mm)
The inner cylinder of the coils (the space that is 1/3 the diameter of coil), denotes the area of uniform magnetic field.

The platform for magnetic experiments is replaceable, so you can have switchable platforms for applications.
