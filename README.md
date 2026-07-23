# Project Hub

Welcome!

This repository serves as an index to most **RADI0SUS** open-source projects.

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
### Tables, reports, ORTEP plots
- [`ciflordg-web`](https://github.com/radi0sus/ciflordg-web/) *CIF reporting, average calculations, geometry-parameter analysis, interatomic distance analysis, disorder-model summarisation, and ORTEP-style SVG structure plotting.* `JavaScript` `HTML`
  - [Try it here.](https://radi0sus.github.io/ciflordg-web/)
- [`cifpal`](https://github.com/radi0sus/cifpal/) *Tables with selected bond lengths and angles from CIF (Crystallographic Information File).* `Python`
- [`tablemaster-web`](https://github.com/radi0sus/tablemaster-web/) *Crystal data and structure refinement details from up to five CIFs.* `JavaScript` `HTML`
  - [Try it here.](https://radi0sus.github.io/tablemaster-web/)
### Geometry parameters
- [`cshm-cc`](https://github.com/radi0sus/cshm-cc/) *Computes CShM (shape measures) and other geometric indices from crystallographic information files (CIFs).* `Python` 
- [`advanced_cshm-cc`](https://github.com/radi0sus/advanced_cshm-cc/) *Browser-based CShM analyzer for coordination compounds.* `JavaScript` `HTML`
  - [Try it here.](https://radi0sus.github.io/advanced_cshm-cc/)
- [`tau-calc`](https://github.com/radi0sus/tau-calc/) *Python 3 script that calculates τ₄, τ₅, O, and CShM from CIF.* `Python`
----
- **Note 1:** `ciflordg-web`, `tablemaster-web`, and `advanced_cshm-cc` include almost all functionality of the remaining tools.
- **Note 2:** There are some older tools like [`Ciflord2`](https://github.com/radi0sus/Ciflord2) or [`TablemasterG2`](https://github.com/radi0sus/TablemasterG2).
  
## Spectroscopy
### Raman spectroscopy
- [`raman_tl`](https://github.com/radi0sus/raman_tl/) *Baseline correction, smoothing, processing and plotting of Raman spectra.* `Python`  
- [`advanced_raman_tl`](https://github.com/radi0sus/advanced_raman_tl/) *Web app for baseline correction, smoothing, processing and plotting of Raman spectra.* `Python` `Streamlit App`
  - [Try it here.](https://advancedramantl-nfvgsz7dquxrmtk6xvc9hq.streamlit.app/)
### Mößbauer spectroscopy
- [`fit-mb`](https://github.com/radi0sus/fit-mb/) *Python 3 script for (hassle-free) fitting of Mößbauer (MB) spectra.* `Python`
- [`cal-mb`](https://github.com/radi0sus/cal-mb/) *Easily calibrate Mößbauer (MB) spectra.* `Python`

## Retro computing
- [`hexviz`](https://github.com/radi0sus/hexviz/) *HEX BIN DEC visualizer for C64 & C128 VDC.* `6502 Assembly` 
  - [Try it here.](https://radi0sus.github.io/hexviz/) `JavaScript` `HTML`
- [`memory128`](https://github.com/radi0sus/memory128/) *A Memory Game for the C128 (VDC)* `6502 Assembly`
  - [Try it here.](https://radi0sus.github.io/memory128/) `JavaScript` `HTML`
- [`robots-mapedit`](https://github.com/radi0sus/robots-mapedit/) *Modern Robots Map Editor.* `Python`

##  Miscellaneous
- [`odl-germany`](https://github.com/radi0sus/odl-germany/) *Interactive overview of ODL stations in Germany.* `Python` `Streamlit App`
  - [Try it here.](https://odl-germany.streamlit.app)
- [`Alfred_Workflows`](https://github.com/radi0sus/Alfred_Workflows/) *A collection of Alfred (MacOS) workflows.* `Shell` `Python`
