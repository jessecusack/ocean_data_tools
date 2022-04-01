# Ocean Data Tools

A list of software for reading, processing and analysing oceanographic data. The focus is on software that comes in the form of a package or module for a programming language, not GUIs or executables. The list is broken down in two main ways. First, all the software packages are listed. Second, the instruments are listed along with the relevant packages. Contributions in the form of emails, issues and pull requests are more than welcome!

### Contents
* [Software list](#software)
  * [For raw data processing](#software-for-reading-and-processing-raw-data)
  * [For analysing data](#software-for-analysing-processed-data)
  * [Other software e.g. colormaps](#other-software)
* [Instruments list](#instruments)
  * [Acoustic velocity instruments](#acoustic-velocity-instruments)
  * [CTDs](#ctds)
  * [Microstructure instruments](#microstructure-instruments)
  * [Echosounders and multibeams](#echosounders-and-multibeams)

# Software

## Software for reading and processing raw data

In no particular order!

| Package | Main devs | Language | Open-source | Actively developed? | Notes | 
|---------|-----------|----------|-------------|---------------------|-------|
| [oce](https://github.com/dankelley/oce) | Dan Kelly, Clark Richards | R        | yes         | yes                 | Can processes raw data from *many* different instruments and manufacturers |
| [dolfyn](https://github.com/lkilcher/dolfyn) | Levi Kilcher (and others?) | Python   | yes         | yes                 | For acoustic velocity data from ADCP and ADV |
| [RSKtools/pyRSKtools](https://bitbucket.org/rbr/) | RBR | MATLAB/Python | yes | yes | RBR's packages for reading data from their instruments |
| [ctdproc](https://github.com/gunnarvoet/ctdproc) | Gunnar Voet | Python | yes | yes | Reading/processing Seabird 9/11 CTD hex files typical to large ship CTDs |
| [pycurrents](https://currents.soest.hawaii.edu/ocn_data_analysis/installation.html) | Julia Hummon, Eric Firing | Python | yes | yes | Reading/processing/analysing data from a variety of instruments including ADCPs |
| [ocean-tools](https://github.com/dswinters/ocean-tools) | Dylan Winters | MATLAB | yes | maybe | Fast reading/processing of ADCP data from TRDI & Nortek |
| [sbemoored](https://github.com/gunnarvoet/sbemoored) | Gunnar Voet | Python | yes | yes | Reading/processing software for SBE56 and SBE37 instruments |
| [ODAS](https://rocklandscientific.com/wpdm-category/data-processing-software/) | Rockland | MATLAB | no | unknown | Processing software for Rockland Scientific vertical microstructure profilers (VMP) |
| [LADCP software](https://www.ldeo.columbia.edu/~ant/LADCP.html) | Andreas Thurnherr | Perl/MATLAB? | no | unknown | Proessing of lowered ADCP data |
| [RADCP](https://www.eoas.ubc.ca/~rich/#RDADCP) | Rich Pawlowicz  | MATLAB | no | unknown | Reading/processing ADCP data from TRDI instruments |
| [RDDTX](https://www.eoas.ubc.ca/~rich/#RDDTX) | Rich Pawlowicz  | MATLAB | no | unknown | Reading/processing single beam echosounder in .dt4 format |
| [CTD_RD](https://www.eoas.ubc.ca/~rich/#CTD) | Rich Pawlowicz  | MATLAB | no | unknown | Reading/processing Seabird CTD data in .cnv format |
| [EPSILOMETER](https://github.com/modscripps/EPSILOMETER) | Arnaud Le Boyer & Nicole Couto | MATLAB | yes | yes | Reading/processing epsilometer data |
| [mixingsoftware](https://github.com/OceanMixingGroup/mixingsoftware) | Ocean Mixing Group (OSU) | MATLAB | yes | some parts | A vast repository with code for reading and analysing a variety of instruments | 

## Software for analysing processed data

| Package | Main devs | Language | Open-source | Actively developed? | Notes | 
|---------|-----------|----------|-------------|---------------------|-------|
| [mixsea](https://github.com/modscripps/mixsea) | Gunnar Voet, Jesse Cusack | Python | yes | yes | Turbulence analysis of finescale observations |
| [python-oceans](https://github.com/pyoceans/python-oceans) | Filipe Fernandes | Python | yes | yes | Miscellaneous helper functions for ocean science |
| [5 beam ADCP turbulence](https://github.com/mguerrap/5Beam-Turbulence-Methods) | Maricarmen Guerra  | MATLAB | yes | no | Turbulence analysis of 5 beam Nortek Signature instruments |
| [T_Tide](https://www.eoas.ubc.ca/~rich/#T_Tide) | Rich Pawlowicz | MATLAB | no | unknown | Tidal harmonic analysis |
| [Standard Mixing Routines](https://github.com/OceanMixingCommunity/Standard-Mixing-Routines) | Many contributors | MATLAB | yes | no | Turbulence analysis of finescale observations | 
| [UTide](https://www.mathworks.com/matlabcentral/fileexchange/46523-utide-unified-tidal-analysis-and-prediction-functions) | Daniel Codiga | MATLAB | no | no | Tidal harmonic analysis |
| [UTide](https://github.com/wesleybowman/UTide) | Wesley Bowman  | Python | yes | yes | Tidal harmonic analysis |
| [gsw](https://www.teos-10.org/software.htm) | Trevor McDougall, Paul Barker | MATLAB, C, Fortran, Python, R, Julia, PHP, C++ | yes | yes | Seawater thermodynamics |
| [jLab](https://github.com/jonathanlilly/jLab/) | Jonathan Lilly | MATLAB | yes | yes | A vast toolbox for many types of analysis |
| [mixingsoftware](https://github.com/OceanMixingGroup/mixingsoftware) | Ocean Mixing Group (OSU) | MATLAB | yes | some parts | A vast repository with code for many types of analysis |
| [GarrettMunkMatlab](https://github.com/jklymak/GarrettMunkMatlab) | Jody Klymak | MATLAB | yes | no | Garrett-Munk spectra |
| [Taylor-Goldstein](https://blogs.oregonstate.edu/salty/matlab-tools-to-solve-the-viscous-taylor-goldstein-equation-for-both-instabilities-and-waves/) | Bill Smyth, Qiang Lian | MATLAB | no | no | Taylor-Goldstein equation solver (internal wave modes) |
| [pyTG](https://github.com/jessecusack/pytg) | Jesse Cusack | Python | yes | yes | Taylor-Goldstein equation solver (internal wave modes) copy of Bill Smyth's code |

## Other software

| Package | Main devs | Language | Open-source | Actively developed? | Notes | 
|---------|-----------|----------|-------------|---------------------|-------|
| [cbrewer](https://www.mathworks.com/matlabcentral/fileexchange/34087-cbrewer-colorbrewer-schemes-for-matlab) |  | MATLAB | no | no | Cynthia Brewer's colormaps |
| [cmocean](https://github.com/chadagreene/cmocean) | Chad Greene | MATLAB | yes | maybe | cmocean colormaps |
| [TMD](https://github.com/EarthAndSpaceResearch/TMD_Matlab_Toolbox_v2.5) | Susan Howard, Laurie Padman, Lana Erofeeva | MATLAB | yes | no | Barotropic tidal predictions |
| [pyTMD](https://github.com/tsutterley/pyTMD) | Tyler Sutterly | Python | yes | yes | Barotropic tidal predictions |

# Instruments

## Acoustic Velocity Instruments

| Instrument  | Software    | Notes  |
|-------------|-------------|--------|
| Teledyne RDI Workhorse | oce, ocean-tools, dolfyn | standard ship/lowered/mooring 4 beam ADCP 300/600/1200 kHz |
| Teledyne RDI Long Ranger | | standard deep mooring ADCP | 
| Teledyne RDI Sentinel V | oce | 5 beam ADCP | 
| Nortek Signature | oce?, ocean-tools? | |
| Nortek ADV | oce? dolfyn? | | 

## CTDs

| Instrument  | Software    | Notes  |
|-------------|-------------|--------|
| Seabird SBE 9/11 | oce, ctdproc, mixingsoftware | Typical UNOLS ship CTD system |
| Seabird SBE56 | oce, sbemoored | Common mooring/chain instrument measures T |
| Seabird SBE37 | oce, sbemoored | Common mooring instrument measures P, T, C |
| RBR solo | oce, RSKtools | Common mooring/chain instrument measures T |
| RBR duet | oce, RSKtools | Common small boat profiling/moored/chain instrument measures some combination of P, T, C |
| RBR concerto | oce, RSKtools | Common small boat profiling/moored/chain CTD measures P, T C and can support additional sensor modules such as dissolved oxygen |

## Microstructure Instruments

| Instrument  | Software    | Notes  |
|-------------|-------------|--------|
| Rockland VMP | ODAS |  |
| Epsilomiter | EPSILOMETER | Developed by the MOD group at Scripps and used in a variety of modes |
| Chipod | mixingsoftware | Developed by the OMG group at Oregon State and generally used on moorings |

## Echosounders and Multibeams
| Instrument  | Software    | Notes  |
|-------------|-------------|--------|
| BIOSONICS DTX digital echosounder  | RDDTX, mixingsoftware |  |
