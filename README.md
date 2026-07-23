# Project Hub

Welcome!

This repository serves as an index to all **RADI0SUS** open-source projects.

Most of these projects started as Python applications. 
Since installing Python still seems to be a challenge for some of us, 
I decided to make them even more accessible by adopting a browser-based approach.  

I have always been inspired by the *zero dependency philosophy* of SHELX, 
and I hope some of these projects follow the same idea. 
The only requirement is a modern web browser with JavaScript enabled.  

I should also admit that much of the JavaScript code was written with the assistance of AI.

## Computational Chemistry (mostly ORCA related)
### Spectroscopy
#### UV/Vis spectroscopy
- [`orca_uv`](https://github.com/radi0sus/orca_uv/) *Plots absorption spectra from from ORCA output files.* `Python`  
- [`advanced_orca_uv`](https://github.com/radi0sus/advanced_orca_uv/) *Interactive browser-based UV-Vis spectrum analysis and export from ORCA output files.* `JavaScript` `HTML`
  - [Try it here.](https://radi0sus.github.io/advanced_orca_uv/) 
- [`orca_st`](https://github.com/radi0sus/orca_st/) *Easily transfer selected states from ORCA output files into tables.* `Python`  
- [`orca_st-go`](https://github.com/radi0sus/orca_st-go/) *Easily transfer selected states from ORCA output files into tables.* `Go`
  - **Note:** `advanced_orca_uv` includes almost all functionality of `orca_st` and `orca_st-go`.

#### Infrared spectroscopy
- [`orca_ir`](https://github.com/radi0sus/orca_ir/) *Plots IR spectra from from ORCA output files.* `Python`  
- [`advanced_orca_ir`](https://github.com/radi0sus/advanced_orca_ir/) *Interactive web app for plotting IR spectra from ORCA & GAUSSIAN output files.* `JavaScript` `HTML`
  - [Try it here.](https://radi0sus.github.io/advanced_orca_ir/)   
- [`modeviz`](https://github.com/radi0sus/modeviz/) *Visualization of calculated IR Modes from ORCA or GAUSSIAN.* `JavaScript` `HTML`
  - [Try it here.](https://radi0sus.github.io/modeviz/)

#### Mößbauer spectroscopy
- [`plot-mb`](https://github.com/radi0sus/plot-mb/) *Plots Mößbauer spectra from parameter files or ORCA output files.* `Python` 
- [`advanced_plot_mb`](https://github.com/radi0sus/advanced_plot_mb/) *Plots Mößbauer spectra from parameter files or ORCA output files.* `JavaScript` `HTML`
  - [Try it here.](https://radi0sus.github.io/advanced_plot_mb/)
- **Note:** It can also simulate Mößbauer spectra from specified isomer shifts and quadrupole splittings.

### Orbital analysis
- [`orca_orb`](https://github.com/radi0sus/orca_orb/) *Analyzes the section 'LOEWDIN REDUCED ORBITAL POPULATIONS PER MO' in ORCA output files.* `Python` 
- [`advanced-orca-orb`](https://github.com/radi0sus/advanced-orca-orb/) *Analyzes the section 'LOEWDIN REDUCED ORBITAL POPULATIONS PER MO' in ORCA output files.* `JavaScript` `HTML`
  - [Try it here.](https://radi0sus.github.io/advanced-orca-orb/)
- [`mo-viewer`](https://github.com/radi0sus/mo-viewer/) *Display and export Gaussian CUBE files.* `JavaScript` `HTML`
  - [Try it here.](https://radi0sus.github.io/mo-viewer/)    

### Structure (xyz) analysis and manipulation
- [`xyz2tab`](https://github.com/radi0sus/xyz2tab/) *Convert XYZ data to bond lengths & angles, calculate contacts, planes and dihedral angles and print tables.* `Python` 
- [`advanced_xyz2tab`](https://github.com/radi0sus/advanced_xyz2tab/) *Convert XYZ data to bond lengths & angles, calculate contacts, planes and dihedral angles and print tables.* `JavaScript` `HTML`
  - [Try it here.](https://radi0sus.github.io/advanced_xyz2tab/)
- [`xyzalign`](https://github.com/radi0sus/xyzalign/)*Align atomic coordinates in xyz files.* `Python`
- [`xyzoverlay`](https://github.com/radi0sus/xyzoverlay/) *Python 3 script for overlaying or superimposing two or more molecules.* `Python`

## Crystallography
- [`ciflordg-web`](https://github.com/radi0sus/ciflordg-web/) *CIF reporting, average calculations, geometry-parameter analysis, interatomic distance analysis, disorder-model summarisation, and ORTEP-style SVG structure plotting.* `JavaScript` `HTML`
  - [Try it here.](https://radi0sus.github.io/ciflordg-web/) 

## Spectroscopy
