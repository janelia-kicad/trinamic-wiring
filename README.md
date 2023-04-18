- [About](#org45adf98)
- [Images](#orga192416)
- [Schematic](#org2daba21)
- [PCB](#orgef8a1f1)
- [Bill of Materials](#org65267f4)
- [Development](#orgb60563d)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="org45adf98"></a>

# About

```markdown
- Project Name: trinamic_wiring
- Description: Wiring documentation for various Trinamic devices and ICs.
- Version: 0.3.0
- Kicad Version: 7.0.1
- Release Date: 2023-04-18
- Creation Date: 2022-11-02
- License: BSD-3-Clause
- URL: https://github.com/janelia-kicad/trinamic_wiring
- Author: Peter Polidoro
- Email: peter@polidoro.io
- Copyright: 2023 Howard Hughes Medical Institute
- References:
  - https://www.kicad.org/
  - https://www.trinamic.com/products/integrated-circuits/details/tmc2209-la/
```


<a id="orga192416"></a>

# Images


<a id="org2daba21"></a>

# Schematic


<a id="orgef8a1f1"></a>

# PCB


<a id="org65267f4"></a>

# Bill of Materials


## Board

|    |
|--- |
|  |


## Supplemental

| Item | Description | Manufacturer Part Number | Manufacturer | Quantity |
|---- |----------- |------------------------ |------------ |-------- |


<a id="orgb60563d"></a>

# Development


## Install Guix

[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)


## Edit metadata.org

    make -f .metadata/Makefile metadata-edits


## Tangle metadata.org

    make -f .metadata/Makefile metadata


## Edit project

    make -f .metadata/Makefile project-edits
    exit