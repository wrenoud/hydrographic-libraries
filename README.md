# FOSS for Hydrographic Programmers

### Hydrographic/Oceanographic Organizations on GitHub

* [HydrOffice][1]
* [ausseabed][2]
* [noaa-ocs-hydrography][3]
* [Rijkswaterstaat][4]
* [UK Hydrographic Office][5]
* [pyoceans][6]
* [OpenNavigationSurface][7]

### Data Readers

* [GDAL](https://pypi.org/project/GDAL/) (_python_) - this is the pypi library for [GDAL](https://github.com/OSGeo/gdal) (_C_/_C++_), a translator library for raster and vector geospatial data formats
* [PDAL](https://pypi.org/project/PDAL/) (_python_) - this is the pypi library for [PDAL](https://pdal.io/)  (_C_/_C++_), a library for translating and manipulating point cloud data. It is very much like the GDAL library which handles raster and vector data.
* [ausseabed/pyall](https://github.com/ausseabed/pyall) (_python_) - an [ausseabed][2] native python reader for Kongsberg ALL file format (note that this is a maintained fork of [pktrigg/pyall](https://github.com/pktrigg/pyall))
* [valschmidt/kmall](https://github.com/valschmidt/kmall) (_python_) - a native python reader for Kongsberg KMALL file format (note that there is also a fork [ausseabed/kmall](https://github.com/ausseabed/kmall) maintained by [ausseabed][2])
* [pyxtf](https://github.com/oysstu/pyxtf) (_python_) - A python library for reading and writing eXtended Triton Format (XTF) files
* [OpenNavigationSurface/BAG](https://github.com/OpenNavigationSurface/BAG) (_python_/_C_/_C++_) - the reference implementation for the BAG format maintained by [OpenNavigationSurface][7], GDAL includes this reference implementation.
* [hyo2_bag](https://github.com/hydroffice/hyo2_bag) (_python_) - a [HydrOffice][1] library for the BAG format
* [hyo2_soundspeed](https://github.com/hydroffice/hyo2_soundspeed) (_python_) - a [HydrOffice][1] library to read, write, and manage sound speed profiles from a diverse set of formats
* [gpsparser](https://github.com/valschmidt/gpsparser) (_python_) - a Python GPS NMEA string parsing module.
* [gsfpy](https://github.com/UKHO/gsfpy) (_python_) - Python wrapper for the C implementation of the Generic Sensor Format library.

### Data Analysis/Processing

* [pandas](https://pandas.pydata.org/) (_python_) - pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool for python
* [MB-System](https://github.com/dwcaress/MB-System) (_C_/_C++_) - an open source software package for the processing and display of bathymetry and backscatter imagery data derived from multibeam, interferometry, and sidescan sonars.
* [kluster](https://github.com/noaa-ocs-hydrography/kluster) (_python_) - a fully functional MBES processor for Kongsberg ALL and KMALL files from [noaa-ocs-hydrography][3].

### Aquisition Interfacing

* [hyo2_kng](https://github.com/hydroffice/hyo2_kng) (_python_) - a [HydrOffice][1] library and apps for Kongsberg Maritime's SIS data interaction
* [7k](https://github.com/Teledyne-Marine/7k) (_C/C++_) - Teledyne Marine 7k protocol for marine sensor interfacing (requires access aproval, see [Teledyne-Marine/access](https://github.com/Teledyne-Marine/access))

### Data Download

* [noaa_coops](https://github.com/GClunies/noaa_coops) (_python_) - Python wrapper for [NOAA CO-OPS Tides & Currents](https://tidesandcurrents.noaa.gov/) Data

### Specialized Tools

* [pyBathySfM](https://github.com/geojames/pyBathySfM) (_python_) - python tool for performing bathymetric refraction correction on Structure from Motion datasets.
* [pyproj](https://github.com/pyproj4/pyproj) (_python_) - Python interface to PROJ (cartographic projections and coordinate transformations library)
* [enc_dump](https://github.com/valschmidt/enc_dump) (_python_) - A python tool for extracting data from US Electronic Nautical Charts (based on GDAL)


[1]: https://github.com/hydroffice
[2]: https://github.com/ausseabed
[3]: https://github.com/noaa-ocs-hydrography
[4]: https://github.com/Rijkswaterstaat
[5]: https://github.com/UKHO
[6]: https://github.com/pyoceans
[7]: https://github.com/OpenNavigationSurface
