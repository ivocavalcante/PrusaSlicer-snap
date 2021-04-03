# PrusaSlicer-snap

Source for Snap package of PrusaSlicer **(unofficial)**.

Original project URL: [GitHub/PrusaSlicer](https://github.com/prusa3d/PrusaSlicer).

Snap package URL: [snapcraft.io/prusa-slicer](https://snapcraft.io/prusa-slicer)

# PrusaSlicer

PrusaSlicer converts 3D models into instructions for 3D printers.

PrusaSlicer takes 3D models (STL, OBJ, AMF) and converts them into G-code instructions
for FFF printers or PNG layers for mSLA 3D printers. It's compatible with any modern printer
based on the RepRap toolchain, including all those based on the Marlin, Prusa, Sprinter and
Repetier firmware. It also works with Mach3, LinuxCNC and Machinekit controllers.

PrusaSlicer is based on Slic3r by Alessandro Ranelucci and the RepRap community

Check upstream - https://github.com/prusa3d/PrusaSlicer - for more info about the project.

Connect following interfaces, in order to be able to save G-CODE directly to SD cards; unmounting cards through interface doesn't work though, and will crash GUI (I'm looking into it).

`sudo snap connect prusa-slicer:removable-media`

`sudo snap connect prusa-slicer:mount-observe`

**Disclaimer:**

This is an **unofficial package**, under development. Please report any issues to **package developer**, unless reproducible in upstream version - and, thus, not a packaging problem.

**snapcraft.yaml** file can be found here: https://github.com/ivocavalcante/PrusaSlicer-snap/blob/main/snap/snapcraft.yaml

All product and company names are trademarks™ or registered® trademarks of their respective holders. Use of them does not imply any affiliation with or endorsement by them.

