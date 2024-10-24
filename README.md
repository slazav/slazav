### Selected projects

#### Low-temperature physics

At the moment all these projects are almost abandoned because
unfortunately I do not have any position in helium-3 science anymore. If
you have any suggestions, any spare wet cryostat which I can rebuild and
use, please let me know!

* Measurement system (was used in superfluid Helium-3 experiments in
Helsinki and Lancaster)

  * [device2](https://github.com/slazav/device2) -- Server for accessing devices and programs in experimental setup. This is the central part of the measurement system which allows to send commands to local and remote devices and programs without any knowledge about connection details
  * [graphene](https://github.com/slazav/graphene) -- A simple time series database based on BerkleyDB
  * [pico_osc](https://github.com/slazav/pico_osc) -- SPP interface for Picoscope 4000 oscilloscope (can be connected to device2). Programs for manipulating recorded signals (probably, should be moved to a separate package)
  * [spp-picoadc](https://github.com/slazav/spp-picoadc) -- SPP interface for Pico ADC devices
  * [spp-nidaq](https://github.com/slazav/spp-nidaq) -- SPP interface to NI DAQ devices (via NIDAQmx library)
  * [spp-ads1115](https://github.com/slazav/spp-ads1115) -- SPP interface to ADS1113/1114/1115 ADC converter
  * [tcl-device_role](https://github.com/slazav/tcl-device_role) -- DeviceRole library, standard drivers for devices
  * [tcl-exp](https://github.com/slazav/tcl-exp) -- TCL/TK based GUI for experiments
  * [tcl-xblt](https://github.com/slazav/tcl-xblt) -- tcl-xblt library from ROTA group
  * [tcl-gpib](https://github.com/slazav/tcl-gpib) -- tcl-gpib library from ROTA group (I'm not using it because Device2 server directly works with libgpib)
  * [tcl-bf2gr](https://github.com/slazav/tcl-bf2gr) -- parse Bluefors/CryoMech/Magnicon logfiles, put data into graphene database
  * [alt2deb](https://github.com/slazav/alt2deb) -- Scripts for building deb packages - this was used for deploying the measurement system on Debian/Ubuntu

* Data processing

  * [py_fit_res](https://github.com/slazav/py_fit_res) -- python library for fitting linear and non-linear resonances
  * [fit_res](https://github.com/slazav/fit_res) -- Fast command-line tool for fitting linear resonances
  * [data_filter](https://github.com/slazav/data_filter) -- A smart filter for telemetry data

* Numerical simulation

  * [he3lib](https://github.com/slazav/he3lib) -- He3 calculator, C/F/matlab/octave/cmdline interfaces
  * [he3vmcw](https://github.com/slazav/he3vmcw) -- 1D Legget-Takagi equation solver (based on V.Dmitriev's code)
  * [he3text1r](https://github.com/slazav/he3text1r) -- He3-B 1D radial texture calculation. F/C/matlab/octave interfaces
  * [he3cad](https://github.com/slazav/he3cad) -- Cadabra scripts - energies in He3-B
  * [he3en](https://github.com/slazav/he3en) -- Collection of matlab/octave scripts for testing various 3He-B energies
  * [cryoblocks](https://github.com/slazav/cryoblocks) -- Thermal flow calculator for cryogenic (and any other) systems
  * [magneetti](https://github.com/slazav/magneetti) -- Old (not my) program for magnetic field profile calculation
  * [dealii_progs](https://github.com/slazav/dealii_progs) -- Simulation: Spin waves between half-quantum vortices in polar phase of 3He
  * [LIM](https://github.com/slazav/LIM) -- Larkin-Imry-Ma state toy simulations

#### Maps

I'm making hiking maps more then 20 years. Two main projects are maps of
Moscow region (related to MMB orienteering event) and maps of mountain
regions. Nowdays I'm not very active with Moscow maps (but MMB team
still is). Mountain maps are updated quite regularly.

Maps can be viewed online [here](https://nakarte.me/#m=3/45.33670/73.47656&l=E/Q/Z).
More information and other formats (Garmin, Osmand, etc.) [here](https://slazav.xyz/maps/index.htm).

* [mapsoft2](https://github.com/slazav/mapsoft2) -- Mapsoft project
* [mapsoft2-libs](https://github.com/slazav/mapsoft2-libs) -- libraries for mapsoft2 and other projects
* [map_hr](https://github.com/slazav/map_hr) -- Sources for mountain maps
* [map_podm](https://github.com/slazav/map_podm) -- Sources for Moscow maps
* [alos_overlay](https://github.com/slazav/alos_overlay) -- fixing ALOS DEM data

#### Misc

* [addphoto](https://github.com/slazav/addphoto) -- Script for making html texts with photos (for slazav.xyz site)
* [bresenham](https://github.com/slazav/bresenham) -- description of Bresenham algorithm (line, circle), comments in Russian
* [akk](https://github.com/slazav/akk) -- An old program for visualizing guitar chords

All Github projects: https://github.com/slazav?tab=repositories

Most of my code is under GPL v3.0 License. Most packages contain spec
file for Altlinux (it's my main packaging system), some have files for
building packages for Gentoo (thanks to @suntar) and Ubuntu.

My website (mostly travel reports and photos): https://slazav.xyz/

My profile in [scholar.google.com](https://scholar.google.com/citations?user=t2gXN8sAAAAJ&hl=en)

<!--

ph_scan -- Scripts and programs for film scanners
ph_scripts -- simple scripts for making html photoalbums
weather -- построение графиков количества снега и температуры по данным rp5
my_qucs -- my .qucs folder full of random qucs files
ptlogger -- Pressure + temperature logger based on Adafruit feather
mmb -- old MMB scripts and data
ves -- списки снаряжения к разным походам и т.п.
sti - сервер для игры в стихи

exp_py -- my python libraries
exp_scripts -- Useful scripts for my experimental setup and data processing
tcl-device -- Device library - replaced with https://github.com/slazav/device2
tcl-grview -- GrapheneViewer library, a viewer for Graphene databases
tcl-grmon -- GrapheneMonitor library, monotor frame and modules
he3waves -- matlab scripts for various numerical calculations: magnon condensate, spin waves in HQV, vortex fermion states...
he3misc -- Various things about He3 calculations
fig2xfig -- save matlab figures in xfig format

my_papers -- 
my_talks -- slides for presentations (latex+xfig - based)
he3notes -- one more attempt to organize notes and reports
diss -- My PhD thesis: Superfluid 3He in aerogel, HPD oscillations. Text, numerical exp, presentations

f5_cryo_data -- f5 general information
cryo_data -- Cryostat parameters and important data
data_f4 -- Lancaster f4 data processing
data_f4_wire_b -- 
data_f2_nafenPython -- 
data_dd_hpd
geokhi -- work for GEOKHI institute

slazav_xyz_cat -- slazav.xyz: catalog (+gps data)
xyz_site -- for slazav.xyz site
eventdb -- Simple BerkleyDB-based WEB-interface

map_hr_c -- хребтовки А.Чупикина и О.Власенко
map_podm_tiles -- Карты Подмосковья в виде гуглолиток. В качестве исходника используется map_podm
map_podm_1km -- Labels for 1km maps.
clusters -- some temporary map project
* [nakarte](https://github.com/slazav/nakarte) -- modify nakarte.me for vector map editing (not finished)

-->
