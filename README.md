- [About](#org0de4295)
- [Images](#org4daaa50)
- [Schematic](#org8920924)
- [PCB](#orgf050ae3)
- [Bill of Materials](#orgf78294e)
- [Development](#org873bf2f)

    <!-- This file is generated automatically from metadata -->
    <!-- File edits may be overwritten! -->


<a id="org0de4295"></a>

# About

```markdown
- Project Name: trinamic_wiring
- Description: Wiring documentation for various Trinamic devices and ICs.
- Version: 0.3
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


<a id="org4daaa50"></a>

# Images


<a id="org8920924"></a>

# Schematic


<a id="orgf050ae3"></a>

# PCB


<a id="orgf78294e"></a>

# Bill of Materials


## Board

|    |
|--- |
|  |


## Supplemental

| Item | Description | Manufacturer Part Number | Manufacturer | Quantity |
|---- |----------- |------------------------ |------------ |-------- |


<a id="org873bf2f"></a>

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