# Awesome Geospatial   [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Long list of geospatial analysis tools. Geospatial analysis, or just spatial analysis, is an approach to applying statistical analysis and other analytic techniques to data which has a geographical or spatial aspect.

![427672_2794027726746_176065793_n](https://user-images.githubusercontent.com/7756611/48104109-2f465b80-e219-11e8-81bb-f6066e6a1be8.jpg)

- [Awesome Geospatial](#awesome-geospatial)
    - [Database](#database)
    - [Image Classification & DIP Software](#image-classification--dip-software)
    - [Geographic Information System](#geographic-information-system)
    - [Web Map Development](#web-map-development)
    - [Web Map Server](#web-map-server)
    - [Radar](#radar)
    - [Lidar](#lidar)
    - [3D Application](#3d-application)
    - [Geographic Data Mining](#geographic-data-mining)
    - [Atmospheric Correction](#atmospheric-correction)
    - [Agent-based Modeling](#agent-based-modeling)
    - [Libraries](#libraries)
    - [PaaS - Platform as a Service](#paas---platform-as-a-service)
    - [SaaS - Software as a Service](#saas---software-as-a-service)
    - [DaaS - Data as a Service](#daas---data-as-a-service)
    - [Deep Learning](#deep-learning)
    - [Python](#python)
    - [Perl](#perl)
    - [Java](#java)
    - [Kotlin](#kotlin)
    - [Clojure](#clojure)
    - [Crystal](#crystal)
    - [C Sharp](#c-sharp)
    - [C++](#c)
    - [C](#c-1)
    - [Fortran](#fortran)
    - [Go](#go)
    - [Rust](#rust)
    - [Ruby](#ruby)
    - [PHP](#php)
    - [Lua](#lua)
    - [Lisp](#lisp)
    - [Haskell](#haskell)
    - [Elixir](#elixir)
    - [Swift](#swift)
    - [Scala](#scala)
    - [Groovy](#groovy)
    - [Delphi](#delphi)
    - [CSS](#css)
    - [IDL](#idl)
    - [Julia](#julia)
    - [JavaScript](#javascript)
    - [R](#r)
    - [Mobile Development](#mobile-development)
    - [Geospatial Big Data](#geospatial-big-data)
    - [Visualization](#visualization)
    - [Tools](#tools)
    - [Cheat sheets](#cheat-sheets)
    - [Data Sources](#data-sources)
    - [Resources](#resources)
    - [Podcasts](#podcasts)
    - [Conferences](#conferences)
    - [References](#references-and-other-awesome-lists)

- - -

## Database

* [PostGIS](http://postgis.net/) :star2: - PostgreSql spatial extension.
* [PostGIS Vector Tile Utils](https://github.com/mapbox/postgis-vt-util) - A set of PostgreSQL functions that are useful when creating vector tile sources.
* [PgRouting](https://pgrouting.org/) - pgRouting extends the PostGIS / PostgreSQL geospatial database to provide geospatial routing functionality.
* [Spatialite](http://www.gaia-gis.it/gaia-sins/) - SQLite spatial extension.
* [Geopackage](https://www.geopackage.org/) - SQLite spatial extension. More powerfull than its older brother Spatialite.
* [Microsoft SQL Server](https://docs.microsoft.com/en-us/sql/relational-databases/spatial/spatial-data-sql-server) - Microsoft SQL/SQL Azure spatial features. All the spatial functionality is also available as a .NET library (can be downloaded using nuget)
* [Neo4j Spatial](https://github.com/neo4j-contrib/spatial) - Library of spatial utilities for Neo4j.
* [Oracle Spatial](http://www.oracle.com/us/products/database/options/spatial/overview/index.html) - Oracle database spatial extension.
* [MySql Spatial](http://dev.mysql.com/doc/refman/5.7/en/spatial-extensions.html) - MySql spatial extension.
* [GeoCouch](https://github.com/couchbase/geocouch) - GeoCouch is a spatial extension for Couchbase and Apache CouchDB.
* [Cloudant](https://cloudant.com/) - IBM noSQL database that supports spatial data (GeoJSON).
* [MongoDB](https://www.mongodb.com/) - Also supports GeoJSON and spatial indexes.
* [DB2 Spatial Extender](http://www-03.ibm.com/software/products/en/db2spaext) - Spatial Extender allows you to store, manage, and analyze spatial data in DB2.
* [Informix Spatial](http://www-01.ibm.com/software/data/informix/spatial/) - Informix spatial extension.
* [Teradata Geospatial Feature](http://br.teradata.com/Resources/Demos/Teradata-Geospatial-Features-Overview/?LangType=1046&LangSelect=true) - Teradata spatial extension for DW and BI.
* [Rasdaman](http://www.rasdaman.org/) - Array database that allows storing and querying massive multi-dimensional arrays, such as sensor, image, simulation, and statistics data appearing in domains like earth, space, and life science.
* [SciDB](http://www.paradigm4.com/) - Array database designed for multidimensional data management and analytics common to scientific, geospatial, financial, and industrial applications.
* [3D CityDB](http://www.3dcitydb.org/) - A free 3D geo database to store, represent, and manage virtual 3D city models on top of a standard spatial relational database. The database model contains semantically rich, hierarchically structured, multi-scale urban objects facilitating complex GIS modeling and analysis tasks, far beyond visualization.
* [Tile38](https://github.com/tidwall/tile38) - Tile38 is a geospatial database, spatial index, and realtime geofence.
* [OrientDB](https://github.com/orientechnologies/orientdb) - OrientDB is an Open Source Multi-Model NoSQL DBMS with the support of Native Graphs, Documents Full-Text, Reactivity, Geo-Spatial and Object Oriented concepts.
* [H2GIS](https://github.com/orbisgis/h2gis) - A spatial extension of the H2 database.
* [MobilityDB](https://github.com/ULB-CoDE-WIT/MobilityDB) - An extension to the Postgres database which adds support for temporal and spatio-temporal objects

## Image Classification & DIP Software

* [eCognition](http://www.ecognition.com/suite/ecognition-developer) - GEOBIA software.
* [Interimage](http://www.lvc.ele.puc-rio.br/projects/interimage/) - Open Source GEOBIA software.
* [ENVI](http://www.harrisgeospatial.com/ProductsandSolutions/GeospatialProducts/ENVI.aspx) - Geospatial image processing and classification software.
* [ERDAS](http://www.hexagongeospatial.com/products/producer-suite/erdas-imagine) - Geospatial image processing and classification software.
* [PCI Geomatica](http://www.pcigeomatics.com/software/geomatica/professional) - Remote sensing software package for image processing
* [Global Mapper](http://www.bluemarblegeo.com/products/global-mapper.php) - Geospatial and remote sensing data analysis.
* [Spring](http://www.dpi.inpe.br/spring/english/index.html) - GIS and remote sensing image processing system with an object-oriented data model.
* [TerrSet](https://clarklabs.org/terrset/) - TerrSet (formerly IDRISI) is an integrated geographic information system (GIS) and remote sensing software
* [OSSIM](http://trac.osgeo.org/ossim/) - Suite of geospatial libraries and applications used to process imagery, maps, terrain, and vector data.
* [e-Foto](http://www.efoto.eng.uerj.br/en) - Free and open source digital photogrammetric workstation.
* [Guidos Toolbox](http://forest.jrc.ec.europa.eu/download/software/guidos/) - Some GDAL functionalities and includes MSPA (Morphological Spatial Pattern Analysis) for connectivity maps.
* [Matlab](http://www.mathworks.com/products/matlab/) - Multi-paradigm numerical computing environment and fourth-generation programming language.
* [IDL](http://www.harrisgeospatial.com/ProductsandSolutions/GeospatialProducts/IDL.aspx) - IDL is a programming language used for data analysis and image processing programming.
* [ArcMap Raster Edit Suite](https://github.com/haoliangyu/ares) - An ArcMap Addin that enables manual editing of single pixels on raster layer.
* [The Sentinel Toolbox](https://sentinel.esa.int/web/sentinel/toolboxes) - The Sentinel Toolboxes consists of a collection of processing tools, data product readers and writers and a display and analysis application to process Sentinel data.
* [Dinamica EGO](http://csr.ufmg.br/dinamica/) - Dinamica EGO consists of a sophisticated platform for environmental modeling.
* [TIMESAT](http://web.nateko.lu.se/timesat/timesat.asp?cat=0) - TIMESAT is a software package for analysing time-series of satellite sensor data.
* [gdal2tilesp](https://github.com/pramsey/gdal2tilesp) - This enhancement to the gdal2tiles.py script includes additional features.


## Geographic Information System

* [ArcGIS](https://www.arcgis.com/features/) :star2: - GIS for working with maps and geographic information.
* [ArcGIS Pro](https://pro.arcgis.com/en/pro-app/) - Fully 64-bit version of ArcGIS with new GUI and 2D/3D integration.
* [LuciadFusion](http://www.luciad.com/solutions/luciadfusion) - An all-in-one server solution for your data publication workflow and geospatial data management
* [QGIS](http://www.qgis.org/en/site/) :star2: - Cross-platform free and open-source desktop geographic information system.
* [GeoDa](http://geodacenter.github.io/) - Spatial data analysis software.
* [Terraview](http://www.dpi.inpe.br/terraview_eng/index.php) - GIS application built using the TerraLib  GIS library.
* [gvSIG](http://www.gvsig.com/en) - Free and open source GIS.
* [GRASS GIS](https://grass.osgeo.org/) - GRASS (Geographic Resources Analysis Support System) is a free and open source GIS.
* [ILWIS](http://52north.org/communities/ilwis/ilwis-open) - Integrated Land and Water Information System (ILWIS) is a remote sensing and GIS software.
* [MapWindow GIS](http://www.mapwindow.org/) - Free and open source desktop geographic information system.
* [MapInfo](http://www.pitneybowes.com/us/location-intelligence/geographic-information-systems/mapinfo-pro.html) - Commercial GIS.
* [MicroImages TNTgis](https://www.microimages.com/) - Commercial GIS.
* [Geomedia](http://www.hexagongeospatial.com/products/producer-suite/geomedia) - Commercial GIS.
* [uDig](http://udig.refractions.net/) - A GIS Framework for Eclipse (Java) and also a GIS software.
* [SAGA](http://www.saga-gis.org/en/index.html) - SAGA is the abbreviation for System for Automated Geoscientific Analyses.
* [Manifold System](http://www.manifold.net/) - Commercial GIS.
* [AutoCAD Map 3D](http://www.autodesk.com.br/products/autocad-map-3d/overview) - GIS AutoCAD integration.
* [Smallworld](https://www.gegridsolutions.com/geospatial/catalog/smallworld_core.htm) - Commercial GIS.
* [OpenJUMP](http://openjump.org/) - Open source Java GIS.
* [Mapbox Studio](https://github.com/mapbox/mapbox-studio-classic) - Desktop application for vector tile driven map design.
* [FME Desktop](https://www.safe.com/fme/fme-desktop/) - FME is an integrated collection of Spatial ETL tools for data transformation and data translation.
* [GC2](http://www.mapcentia.com/en/product/) - GC2 is a enterprise platform GIS (open source)


## Web Map Development

* [OpenLayers](http://openlayers.org/) :star2: - High-performance, feature-packed library for creating interactive maps on the web.
* [Ol-ext](https://viglino.github.io/ol-ext/) :star2: - Cool extensions for Openlayers (ol) - animated clusters, CSS popup, Font Awesome symbol renderer, charts for statistical map (pie/bar), layer switcher, wikipedia layer, animations, canvas filters.
* [Leaflet](http://leafletjs.com/) :star2: - Open-Source JavaScript Library for Mobile-Friendly Interactive Maps.
* [Geomanjas](http://www.geomajas.org/) - Open source development software for web-based and cloud based GIS applications.
* [CesiumJS](https://cesiumjs.org/) - An open-source JavaScript library for world-class 3D globes and maps.
* [L7](https://github.com/antvis/L7) - Large-scale WebGL-powered Geospatial Data Visualization By Ant Financial
* [LuciadRIA](http://www.luciad.com/solutions/luciadria) - A JavaScript library for 3D globes and maps, with support for military symbology and desktop-like performance
* [geojson-vt](https://github.com/mapbox/geojson-vt) - A highly efficient JavaScript library for slicing GeoJSON data into vector tiles on the fly.
* [ArcGIS JS App Generator](https://github.com/odoe/generator-arcgis-js-app) - This is a yeoman generator for ArcGIS API for JavaScript applications.
* [CMV - The Configurable Map Viewer](https://github.com/cmv/cmv-app) - CMV is a community-supported open source mapping framework. CMV works with the Esri JavaScript API, ArcGIS Server, ArcGIS Online and more.
* [Leaflet.MapboxVectorTile](https://github.com/SpatialServer/Leaflet.MapboxVectorTile) - A Leaflet Plugin that renders Mapbox Vector Tiles on HTML5 Canvas.
* [Flare Cluster Layer](https://github.com/nickcam/FlareClusterLayer) - ArcGIS javascript custom graphics layer. Creates clusters and creates flares for clusters.
* [Google Maps API Polyline String Decoder](https://github.com/mgd722/decode-google-maps-polyline) - Function that will convert encoded polyline strings (as returned by the Google Maps API) into a list of lat/lon pairs.
* [Mapzen Tangram](https://github.com/tangrams/tangram) - JavaScript library for rendering 2D & 3D maps live in a web browser with WebGL, supports MVT, GeoJSON, TopoJSON.
* [GeoNode](http://geonode.org/) - A web-based application and platform for developing geospatial information systems (GIS) and for deploying spatial data infrastructures (SDI).


## Web Map Server

* [Geoserver](http://geoserver.org/) :star2: - WMS written in Java and relies on GeoTools. Allows users to share and edit geospatial data.
* [MapProxy](http://mapproxy.org/) - An open source tile server proxy for geospatial data (WMS-C, TMS, WMTS, KML SuperOverlays). It caches, accelerates and transforms data from existing map services and serves any desktop or web GIS client. 
* [Mapserver](http://mapserver.org/) :star2: - WMS written in C.
* [MapGuide](https://mapguide.osgeo.org/) - Runs on Linux or Windows, supports Apache and IIS web servers, and has APIs (PHP, .NET, Java, and JavaScript) for application development.
* [PGRestAPI](https://github.com/spatialdev/PGRestAPI) - Node.js REST API for PostGres Spatial Entities. AKA: SpatialServer.
* [utilery](https://github.com/tilery/utilery) - Micro vector tile manufacturing from PostGIS.
* [Deegree](http://www.deegree.org/) - Open source software for spatial data infrastructures and the geospatial web. Deegree offers components for geospatial data management, including data access, visualization, discovery and security. Open standards are at the heart of Deegree. It supports WMS, WFS for Catalogue Service, WCS, WPS, WMTS.
* [52North WPS](http://52north.org/communities/geoprocessing/wps/index.html) - The 52°North Web Processing Service (WPS) enables the deployment of geo-processes on the web in a standardized way. It features a pluggable architecture for processes and data encodings. The implementation is based on the current OpenGIS specification: 05-007r7. Its focus was the creation of an extensible framework to provide algorithms for generalization on the web.
* [Zoo Project WPS](http://www.zoo-project.org/) - A WPS (Web Processing Service) implementation written in C, Python and JavaScript. It is an open source platform which implements the WPS 1.0.0 and WPS 2.0.0 standards edited by the Open Geospatial Consortium (OGC). It provides a developer-friendly framework for creating and chaining WPS compliant Web Services.
* [Nanocubes](https://github.com/laurolins/nanocube) - An in-memory data structure for spatiotemporal data cubes.
* [Baremaps](https://www.baremaps.com/) - An open source pipeline for producing Mapbox vector tiles from OpenStreetMap with Postgis and Java.

## Radar

* [PolSARpro](https://earth.esa.int/web/polsarpro) :star2: - Open source radar image data processing software.
* [Sarmap](http://www.sarmap.ch/page.php?page=sarscape) - Synthetic Aperture Radar processing software.
* [GAMMA](http://www.gamma-rs.ch/no_cache/software.html) - Allows processing of SAR, interferometric SAR (InSAR) and differential interferometric SAR (DInSAR).
* [Sentinel Toolboxes](https://sentinel.esa.int/web/sentinel/toolboxes) - Free open source toolboxes for the scientific exploitation of the Sentinel missions.
* [NANSAT](https://github.com/nansencenter/nansat) - Nansat is a scientist friendly Python toolbox for processing 2D satellite earth observation data.
* [PySAR](https://github.com/insarlab/PySAR) - InSAR time series analysis in Python.
* [SARbian](https://eo-college.org/sarbian/) - Free and open SAR operating system (based on Debian Linux).
* [GMT5SAR](https://topex.ucsd.edu/gmtsar/) - InSAR processing system based on GMT.
* [PyRate](https://github.com/GeoscienceAustralia/PyRate) - A Python tool for estimating velocity and time-series from Interferometric Synthetic Aperture Radar (InSAR) data.
* [SARPROZ](https://www.sarproz.com/) - Implements a wide range of Synthetic Aperture Radar (SAR), Interferometric SAR (InSAR) and Multi-Temporal InSAR processing techniques.
* [GIAnT](http://earthdef.caltech.edu/projects/giant/wiki) - Python libraries and scripts that implement various published time-series InSAR algorithms in a common framework.


## Lidar

* [LAStools](http://www.cs.unc.edu/~isenburg/lastools/) :star2: - A collection of highly-efficient, scriptable tools with multi-core batching that process LAS, compressed LAZ, Terrasolid BIN, .shp, and ASCII.
* [FullAnalyze](https://code.google.com/archive/p/fullanalyze/) - Handling, visualizing and processing lidar data (3D point clouds and waveforms).
* [DielmoOpenLidar](http://www.dielmo.com/eng/ficha-tecnologia-software.php?prod=21) - Open source software based in gvSIG for the management of LiDAR data.
* [Global Mapper Lidar Module](https://www.bluemarblegeo.com/products/global-mapper-lidar.php) - Lidar module for Global Mapper.
* [Fusion](http://forsys.cfr.washington.edu/fusion/fusionlatest.html) :star2: - CLI/GUI Lidar software.
* [libLAS](https://liblas.org/) - libLAS is a C/C++ library for reading and writing the very common LAS LiDAR format. 
* [LASzip](https://www.laszip.org/) - Quickly turns bulky LAS files into compact LAZ files without information loss.
* [PyLAS](https://pypi.python.org/pypi/PyLAS) - A python library for reading and writing LAS files.
* [Laspy](http://laspy.readthedocs.io/en/latest/) - Laspy is a python library for reading, modifying, and creating .LAS LIDAR files.
* [PDAL](http://www.pdal.io/) - PDAL is a C++ BSD library for translating and manipulating point cloud data.
* [displaz](https://github.com/c42f/displaz) - A hackable lidar viewer.
* [lidario](https://github.com/jblindsay/lidario) - A small Go library for reading and writing LiDAR (LAS) files.
* [lidar](https://github.com/jblindsay/lidar) - A Crystal language library for reading and writing LiDAR data in LAS format.
* [MCC-LIDAR](https://sourceforge.net/projects/mcclidar/) - Multiscale Curvature Classification for LIDAR Data.
* [lidR](https://github.com/Jean-Romain/lidR) - R package for airborne LiDAR data manipulation and visualisation for forestry application.
* [Entwine](https://github.com/connormanning/entwine) - Point cloud indexing for massive datasets.
* [Quick Terrain Modeler](http://appliedimagery.com/) - Proprietary LiDAR exploitation software by Applied Imagery.
* [TopoDOT](https://new.certainty3d.com/) - Proprietary software for extracting topography, 3D models, GIS Assets, and more from point cloud data.
* [rGEDI](https://github.com/carlos-alberto-silva/rGEDI) - An R Package for NASA's Global Ecosystem Dynamics Investigation (GEDI) Data Visualization and Processing.


## 3D Application

- [Skyline](http://www.skylineglobe.com/SkylineGlobe/corporate/Default.aspx?) - A glimpse into Skyline's cutting-edge 3D geospatial visualization products, and their potential to transform the way your organization makes decisions, shares information and manages its assets
- [CityEngine](http://www.esri.com/software/cityengine/) - Transform 2D GIS Data into Smart 3D City Models
- [ArcGIS Earth](http://www.esri.com/software/arcgis-earth) - Display data, sketch placemarks, measure distances and areas, and add annotations at any part of the world
- [World Wind](http://worldwind.arc.nasa.gov/java/) -  Providing features for displaying with geographic data
- [Google Earth](http://earth.google.com/) - Bringing a earth view for global mapping

## Geographic Data Mining

* [Weka](http://www.cs.waikato.ac.nz/ml/weka/) - Weka is a collection of machine learning algorithms for data mining tasks written in Java.
* [GeoDMA](https://sourceforge.net/projects/geodma/) - GeoDMA is a plugin for TerraView software, used for geographical data mining.


## Atmospheric Correction

* [ARCSI](https://www.arcsi.remotesensing.info/) - The Atmospheric and Radiometric Correction of Satellite Imagery (ARCSI) software provides a command line tool for the generation of Analysis Ready Data (ARD) optical data including atmospheric correction, cloud masking, topographic correction etc.
* [radiometric_normalization](https://github.com/planetlabs/radiometric_normalization) - Implementation of radiometric normalization workflows.
* [ATCOR](http://www.atcor.de/) - ERDAS Imagine module.
* [6S](http://6s.ltdri.org/) - Second Simulation of the Satellite Signal in the Solar Spectrum (6S) open source algorithm.
* [Py6S](https://py6s.readthedocs.io/en/latest/) - Py6S is a interface to the Second Simulation of the Satellite Signal in the Solar Spectrum (6S) atmospheric Radiative Transfer Model through the Python programming language.
* [i.atcorr](https://grass.osgeo.org/grass70/manuals/i.atcorr.html) - GRASS GIS module that performs atmospheric correction using the 6S algorithm.
* [sen2cor](http://step.esa.int/main/third-party-plugins-2/sen2cor/) - is a processor for Sentinel-2 Level 2A product generation and formatting; it performs the atmospheric-, terrain and cirrus correction of Top-Of- Atmosphere Level 1C input data.

## Agent-based Modeling
* [Mesa](https://github.com/projectmesa/mesa) - Mesa is an Apache2 licensed agent-based modeling (or ABM) framework in Python.
* [NetLogo](https://ccl.northwestern.edu/netlogo/) - NetLogo is a multi-agent programmable modeling environment.
* [Repast](https://repast.github.io/) - The Repast Suite is a family of advanced, free, and open source agent-based modeling and simulation platforms.
* [MASON](https://cs.gmu.edu/~eclab/projects/mason/) - MASON is a fast discrete-event multiagent simulation library core in Java, designed to be the foundation for large custom-purpose Java simulations, and also to provide more than enough functionality for many lightweight simulation needs. MASON contains both a model library and an optional suite of visualization tools in 2D and 3D.
* [DMASON](https://github.com/isislab-unisa/dmason) - DMASON is a parallel version of the MASON library for writing and running simulations of Agent based simulation models.
* [nlrx](https://github.com/ropensci/nlrx) - Provides tools to setup and execute NetLogo simulations from R.


## Libraries

* [GDAL](http://www.gdal.org/) :star2: - Geospatial Data Abstraction Library (GDAL) is a translator library for raster and vector geospatial data formats.
* [Mapnik](http://mapnik.org/) - C++/Python/Node.js library for map rendering.
* [Terralib](http://www.terralib.org/) - TerraLib is a GIS classes and functions open source library.
* [GeographicLib](http://geographiclib.sourceforge.net/) - For solving geodesic problems. Implemented in C, C++, Java, Javascript, Fortran, Python and Matlab. 
* [Geolib](http://www.geolib.co.uk/) - GeoLib is a fast, efficient, computational geometry library available in C++, C# and Java.
* [pgRouting](http://pgrouting.org/) - Extends the PostGIS / PostgreSQL geospatial database to provide geospatial routing functionality.
* [PointCloud](https://github.com/pgpointcloud/pointcloud) - A PostgreSQL extension for storing point cloud (LIDAR) data.
* [TerraMA2](https://github.com/TerraMA2/terrama2) - A free and open source computational platform for early warning systems.


## PaaS - Platform as a Service

* [Google Maps API](https://developers.google.com/maps/) - Google's PaaS (Platform as a Service) for Geocoding or analysis/processing services.
* [Microsoft Bing API](https://www.microsoft.com/en-us/maps) - Microsoft Bing Maps API.
* [OpenStreetMap API](http://wiki.openstreetmap.org/wiki/API_v0.6) - OpenStreetMap API.
* [Mapbox.js](https://www.mapbox.com/mapbox.js/api/v2.4.0/) - MapBox Javascript API.
* [Mapbox GL JS](https://www.mapbox.com/mapbox-gl-js/api/) - MapBox WebGL Javascript API.


## SaaS - Software as a Service

* [ArcGIS Online](https://www.arcgis.com/home/) - ArcGIS Online GIS platform for mapping and spatial analysis.
* [Carto](https://carto.com/) -  Cloud computing platform that provides GIS and web mapping tools for display in a web browser.
* [Fulcrum](http://www.fulcrumapp.com/) - A mobile data collection platform that allows you to build, deploy, & collect field data with your own customizable data collection apps.
* [GIS Cloud](https://www.giscloud.com/) - Real-time mapping platform for the entire workflow of your organization.
* [Linq](https://www.linq.it/) - Business process mapping.
* [Mapbox](https://www.mapbox.com/) - Plataform for web map design and manipulation.
* [NextGIS](http://nextgis.com/) - A cloud geospatial service that allows you to create web GIS right in the browser.
* [OpenCage Geocoding API](https://geocoder.opencagedata.com/) - An API aggregating multiple open geo datasources (OpenStreetMap and others).
* [OpenMapTiles](https://openmaptiles.com/) - Vector tiles and map services as service, self-hosted or off-line.

## DaaS - Data as a Service

* [Apple Maps](https://mapsconnect.apple.com/) - Apple map service.
* [Google Maps](https://www.google.com.br/maps) - Google map service.
* [Microsoft Bing Maps](http://www.bing.com/mapspreview) - Microsoft map service.
* [OpenStreetMap](http://www.openstreetmap.org/) - OpenStreeMap map service.


## Deep Learning

* [Darknet](https://github.com/pjreddie/darknet) - Darknet is an open source neural network framework written in C and CUDA.
* [Raster Vision](https://github.com/azavea/raster-vision) - An open source framework for deep learning on satellite and aerial imagery.
* [AirNet](https://github.com/mathildor/TF-SegNet) - SegNet-like network implemented in TensorFlow to use for segmenting aerial images.
* [TernausNetV2](https://github.com/ternaus/TernausNetV2) - TernausNetV2: Fully Convolutional Network for Instance Segmentation.
* [YOLT](https://github.com/avanetten/yolt) - You Only Look Twice: Rapid Multi-Scale Object Detection In Satellite Imagery.
* [SIMRDWN](https://github.com/avanetten/simrdwn) - The Satellite Imagery Multiscale Rapid Detection with Windowed Networks (SIMRDWN) codebase combines some of the leading object detection algorithms into a unified framework designed to detect objects both large and small in overhead imagery.
* [Pixel Decoder](https://github.com/Geoyi/pixel-decoder) - A machine learning python package to run deep learning with satellite imagery.
* [LightNet](https://github.com/ansleliu/LightNet) - LightNet: Light-weight Networks for Semantic Image Segmentation (Cityscapes and Mapillary Vistas Dataset)
* [eo-learn](https://github.com/sentinel-hub/eo-learn) - Earth observation processing framework for machine learning in Python.
* [libtorch-yolov3](https://github.com/walktree/libtorch-yolov3) - A Libtorch implementation of the YOLO v3 object detection algorithm.
* [ShelfNet](https://github.com/juntang-zhuang/ShelfNet) - Implementation of a CNN model for real-time semantic segmentation.
* [Hyperspectral](https://github.com/KGPML/Hyperspectral) - Deep Learning for Land-cover Classification in Hyperspectral Images.
* [SNIPER](https://github.com/mahyarnajibi/SNIPER) - SNIPER is an efficient multi-scale object detection algorithm.
* [Label Maker](https://github.com/developmentseed/label-maker) - Data Preparation for Satellite Machine Learning.
* [TorchSat](https://github.com/sshuair/torchsat) - TorchSat is an open-source PyTorch framework for satellite imagery analysis.
* [Temporal Convolutional Neural Network](https://github.com/charlotte-pel/temporalCNN) - Temporal Convolutional Neural Network for the Classification of Satellite Image Time Series.
* [neat-EO](https://neat-EO.pink) - Efficient AI4EO OpenSource framework


## Python

* [GeoDjango](https://docs.djangoproject.com/en/2.2/ref/contrib/gis/) - Django geographic web framework.
* [Landsat-util](https://github.com/developmentseed/landsat-util) - Landsat-util is a command line utility that makes it easy to search, download, and process Landsat imagery.
* [Rasterio](https://github.com/mapbox/rasterio) :star2: - Rasterio employs GDAL under the hood for file I/O and raster formatting.
* [Rasterstats](https://github.com/perrygeo/python-rasterstats/) - Python module for summarizing geospatial raster datasets based on vector geometries.
* [ArcGIS Python API](https://developers.arcgis.com/python/) - ArcGIS API for Python is a Python library for working with maps and geospatial data, powered by web GIS.
* [PyQGIS](http://docs.qgis.org/testing/en/docs/pyqgis_developer_cookbook/) - Python for QGIS.
* [Pandas](http://pandas.pydata.org/) - Open source library providing high-performance, easy-to-use data structures and data analysis tools for the Python.
* [pandana](https://github.com/UDST/pandana) - Pandas Network Analysis - dataframes of network queries, quickly.
* [xarray ](http://xarray.pydata.org/en/stable/) - xarray (formerly xray) is an open source project and Python package that aims to bring the labeled data power of pandas to the physical sciences, by providing N-dimensional variants of the core pandas data structures.
* [GeoPandas](https://github.com/geopandas/geopandas) - Python tools for geographic data.
* [MovingPandas](https://github.com/anitagraser/movingpandas) - MovingPandas implements a Trajectory class and corresponding methods based on GeoPandas.
* [Shapely](https://pypi.python.org/pypi/Shapely) :star2: - Manipulation and analysis of geometric objects in the Cartesian plane.
* [mapboxgl-jupyter](https://github.com/mapbox/mapboxgl-jupyter) - Use Mapbox GL JS to visualize data in a Python Jupyter notebook.
* [Cartopy](http://scitools.org.uk/cartopy/) - A library providing cartographic tools for python for plotting spatial data.
* [Rtree](http://toblerity.org/rtree/) - For efficiently querying spatial data.
* [geoalchemy](https://github.com/geoalchemy/geoalchemy) - Using SQLAlchemy with spatial databases.
* [NodeBox-opengl](http://www.cityinabottle.org/nodebox/) - For playing around with animations.
* [Statsmodels](http://statsmodels.sourceforge.net/) - Python module that allows users to explore data, estimate statistical models, and perform statistical tests.
* [NumPy](http://www.numpy.org/) - NumPy is the fundamental package for scientific computing with Python.
* [geopy](https://github.com/geopy/geopy) - geopy is a Python 2 and 3 client for several popular geocoding web services.
* [FreeType](https://code.google.com/archive/p/freetype-py/) - For converting font glyphs to polygons.
* [Fiona](https://fiona.readthedocs.io/en/latest/) :star2: - For making it easy to read/write geospatial data formats.
* [matplotlib](http://matplotlib.org/) - Python 2D plotting library.
* [networkx](http://networkx.github.io/) - To work with networks.
* [PySAL](http://pysal.readthedocs.io/en/latest/) - For all your spatial econometrics needs.
* [Descartes](https://pypi.python.org/pypi/descartes) - Plot geometries in matplotlib.
* [PyShp](https://code.google.com/archive/p/pyshp/) - For reading and writing shapefiles.
* [PyProj](https://github.com/jswhit/pyproj) - For conversions between projections.
* [Pyncf](https://github.com/karimbahgat/pyncf) - Pure Python NetCDF file reading and writing.
* [chupaESRI](https://github.com/johnjreiser/chupaESRI) - ChupaESRI is a Python module/command line tool to extract features from ArcGIS Server map services.
* [geojsonio.py](https://github.com/jwass/geojsonio.py) - Open GeoJSON data on geojson.io from Python. geojsonio.py also contains a command line utility that is a Python port of geojsonio-cli.
* [Ogcserver](https://github.com/mapnik/OGCServer) - Python WMS implementation using Mapnik.
* [RSGISLib](http://www.rsgislib.org/) :star2: - The Remote Sensing and GIS software library (RSGISLib) is a collection of tools for processing remote sensing and GIS datasets. The tools are accessed using Python bindings or an XML interface.
* [Scikit-image](http://scikit-image.org/) - Scikit-image is a collection of algorithms for image processing.
* [pyWPS](http://pywps.org/) - An implementation of the Web Processing Service standard from the Open Geospatial Consortium. PyWPS is written in Python. It enables integration, publishing and execution of Python processes via the WPS standard.
* [pyCSW](http://pycsw.org/) - Fully implements the OpenGIS Catalogue Service Implementation Specification (Catalogue Service for the Web). Initial development started in 2010 (more formally announced in 2011). The project is certified OGC Compliant, and is an OGC Reference Implementation.
* [urbansim](https://github.com/UDST/urbansim) - New version of UrbanSim, a platform for modeling metropolitan real estate markets.
* [OSMnet](https://github.com/UDST/osmnet) - Tools for the extraction of OpenStreetMap street network data.
* [rio-hist](https://github.com/mapbox/rio-hist) - Histogram matching plugin for rasterio.
* [rio-color](https://github.com/mapbox/rio-color) - Color correction plugin for rasterio.
* [geojson-area](https://github.com/scisco/area) - Calculate the area inside of any GeoJSON geometry. This is a port of Mapbox's geojson-area for Python.
* [Peartree](https://github.com/kuanb/peartree) - Peartree: A library for converting transit data into a directed graph for network analysis.
* [GeoDaSpace](https://github.com/GeoDaCenter/GeoDaSpace) - Software for Advanced Spatial Econometrics.
* [Mahotas](https://github.com/luispedro/mahotas) - Mahotas is a library of fast computer vision algorithms (all implemented in C++ for speed) operating over numpy arrays.
* [Mahotas-imread](https://github.com/luispedro/imread) - Read images to numpy arrays.
* [dask-rasterio](https://github.com/dymaxionlabs/dask-rasterio) - Read and write rasters in parallel using Rasterio and Dask.
* [geeup](https://github.com/samapriya/geeup) - Simple CLI for Earth Engine Uploads.
* [Verde](https://github.com/fatiando/verde) - Verde is a Python library for processing spatial data (bathymetry, geophysics surveys, etc) and interpolating it on regular grids (i.e., gridding).
* [gpdvega](https://github.com/iliatimofeev/gpdvega) - gpdvega is a bridge between GeoPandas and Altair that allows to seamlessly chart geospatial data.
* [LANDSAT-Download](https://github.com/olivierhagolle/LANDSAT-Download) - Automated download of LANDSAT data from USGS website.
* [USGS API](https://github.com/kapadia/usgs) - USGS is a python module for interfacing with the US Geological Survey's API.
* [som-tsp](https://github.com/DiegoVicen/som-tsp) - Solving the Traveling Salesman Problem using Self-Organizing Maps.
* [Centroids](https://github.com/lyzidiamond/centroids) - This application reads a valid geojson FeatureCollection and returns a valid geojson FeatureColleciton of centroids.
* [sentinelsat](https://github.com/sentinelsat/sentinelsat) - Search and download Copernicus Sentinel satellite images.
* [PyPostal](https://github.com/openvenues/pypostal) - Python bindings to libpostal for fast international address parsing/normalization.
* [python-opencage-geocoder](https://github.com/OpenCageData/python-opencage-geocoder) - A Python module that uses the OpenCage Geocoding API.
* [rio-tiler](https://github.com/mapbox/rio-tiler) - Get mercator tile from landsat, sentinel or other AWS hosted raster.
* [rio-cogeo](https://github.com/mapbox/rio-cogeo) - CloudOptimized GeoTIFF creation plugin for rasterio.   
* [GIPPY](https://github.com/gipit/gippy) - Geospatial Image Processing for Python.
* [ts-raster](https://github.com/adbeda/ts-raster) - ts-raster is a python package for analyzing time-series characteristics from raster data. It allows feature extraction, dimension reduction and applications of machine learning techniques for geospatial data.
* [LT-ChangeDB](https://github.com/eMapR/LT-ChangeDB) - Scripts to extract spectral change information from LandTrendr data to a geodatabase.
* [pymap3d](https://github.com/scivision/pymap3d) - Python 3D coordinate conversions for geospace ecef enu eci.
* [YATSM](https://github.com/ceholden/yatsm) - Yet Another Timeseries Model (YATSM) is a Python package for utilizing a collection of timeseries algorithms and methods designed to monitor the land surface using remotely sensed imagery.
* [untiler](https://github.com/mapbox/untiler) - Stitch image tiles into larger composite TIFs.
* [pyroSAR](https://github.com/johntruckenbrodt/pyroSAR) - A Python Framework for Large-Scale SAR Satellite Data Processing.
* [RIOS](https://bitbucket.org/chchrsc/rios/overview) - Raster I/O Simplification. A set of python modules which makes it easy to write raster processing code in Python.
* [thunder](https://github.com/thunder-project/thunder) - Thunder is an ecosystem of tools for the analysis of image and time series data in Python.
* [eo-box](https://github.com/benmack/eo-box) - Earth observation processing framework for machine learning in Python.
* [lidar](https://github.com/giswqs/lidar) - Terrain and hydrological analysis using digital elevation models (DEMs).
* [whitebox](https://github.com/giswqs/whitebox) - Python frontend for [WhiteboxTools](https://github.com/jblindsay/whitebox-tools). 
* [WhiteboxTools-ArcGIS](https://github.com/giswqs/WhiteboxTools-ArcGIS) - ArcGIS Python Toolbox for [WhiteboxTools](https://github.com/jblindsay/whitebox-tools). 
* [landsat-extract-gee](https://github.com/loicdtx/landsat-extract-gee) - Get Landsat surface reflectance time-series from google earth engine.
* [satpy](https://satpy.readthedocs.io/en/latest/) - Satpy is a python library for reading, manipulating, and writing data from remote-sensing earth-observing meteorological satellite instruments.
* [CuPy](https://github.com/cupy/cupy) - NumPy-like API accelerated with CUDA.
* [Python Geocoder](https://github.com/DenisCarriere/geocoder) - Simple and consistent geocoding library written in Python.
* [EarthPy](https://github.com/earthlab/earthpy) - A package built to support working with spatial data using open source python.
* [scikit-mobility](https://github.com/scikit-mobility/scikit-mobility) - Mobility analysis in Python.
* [MovingPandas](https://github.com/anitagraser/movingpandas) - Implementation of Trajectory classes and functions built on top of GeoPandas.
* [geojson-area](https://github.com/scisco/area) - Calculate the area inside of any GeoJSON geometry.
* [osm2geojson](https://github.com/aspectumapp/osm2geojson) - Parse OpenStreetMap (OSM) XML and Overpass JSON/XML.
* [pyGEOS](https://github.com/pygeos/pygeos) - Exposes geospatial operations from GEOS into Python.
* [mapclassify](https://github.com/pysal/mapclassify) - Classification schemes for choropleth mapping.
* [Tobler](https://github.com/pysal/tobler) - Tobler is a python package for areal interpolation, dasymetric mapping, and change of support.


## Perl
* [address formatting](https://github.com/OpenCageData/address-formatting) - Templates to format geographic addresses.
* [Geo::GDAL](https://metacpan.org/pod/Geo::GDAL) - Perl extension for the GDAL library for geospatial data.


## Java

* [Geotools](http://www.geotools.org/) :star2: - GeoTools is an open source Java library that provides tools for geospatial data.
* [GeoServer](http://geoserver.org/) - GeoServer is open source server for sharing geospatial data.
* [GeoWebCache](http://www.geowebcache.org/) - a Java web application used to cache map tiles coming from a variety of sources such as OGC Web Map Service (WMS). It implements various service interfaces (such as WMS-C, WMTS, TMS, Google Maps KML, Virtual Earth) in order to accelerate and optimize map image delivery. It can also recombine tiles to work with regular WMS clients.
* [Geonetwork](http://geonetwork-opensource.org/) - GeoNetwork is a catalog application to manage spatially referenced resources.
* [JTS Topology Suite](http://www.vividsolutions.com/jts/jtshome.htm) :star2: - JTS Topology Suite is an API of 2D spatial predicates and functions.
* [GeOxygene](https://sourceforge.net/projects/oxygene-project/) - Provide an open framework which implements OGC/ISO specifications for the development and deployment of GIS applications.
* [Gisgraphy](http://www.gisgraphy.com/) - Open source framework that offers the ability to do geolocalisation and geocoding via Java APIs or REST webservices.
* [JGeocoder](http://jgeocoder.sourceforge.net/) - Free Java Geocoder.
* [Spatial4j](https://github.com/locationtech/spatial4j) - Spatial4j is a general purpose geospatial ASL licensed open-source Java library.
* [Geoapi](http://www.geoapi.org/) - GeoAPI provides a set of Java language programming interfaces for geospatial applications.
* [Openmap](https://github.com/openmap-java/openmap) - Open Source JavaBeans-based programmer's toolkit.
* [Apache SIS](http://sis.apache.org/) - Apache Spatial Information System (SIS) is a free software, Java language library for developing geospatial applications.
* [World Wind Java SDK](http://worldwind.arc.nasa.gov/java/) - Nasa cross-platform Java SDK.
* [MapFish Print](http://mapfish.github.io/) - The purpose of Mapfish Print is to create reports that contain maps (and map related components) within them. The project is a Java based servlet/library/application based on the mature Jasper Reports Library.
* [asgbook](https://github.com/lakshmanok/asgbook) - Implementation of GIS/RS features in Java. Its also the code accompanying the book "Automating the Analysis of Spatial Grids" by Valliappa Lakshmanan.
* [whitebox-geospatial-analysis-tools](https://github.com/jblindsay/whitebox-geospatial-analysis-tools) - An open-source GIS and remote sensing package.
* [LuciadLightspeed](http://www.luciad.com/solutions/luciadlightspeed) - A Java library that provides the foundations for advanced geospatial analytics applications
* [jpostal](https://github.com/openvenues/jpostal) - Java/JNI bindings to libpostal for fast international street address parsing/normalization.
* [Photon](https://github.com/komoot/photon) - Photon is an open source geocoder built for OpenStreetMap data. It is based on elasticsearch.
* [GraphHopper Routing Engine](https://github.com/graphhopper/graphhopper) - GraphHopper is a fast and memory efficient Java routing engine, released under Apache License 2.0. By default it uses OpenStreetMap and GTFS data, but it can import other data sources.


## Kotlin

* [geospatial-messenger](https://github.com/sdeleuze/geospatial-messenger) - Geospatial messenger application written with Spring Boot + Kotlin + PostgreSQL.


## Clojure

* [geo](https://github.com/Factual/geo) - Clojure library for working with geohashes, polygons, and other world geometry.


## Crystal

* [lidar](https://github.com/jblindsay/lidar) - A Crystal language library for reading and writing LiDAR data in LAS format.


## C Sharp
* [Windows UWP map control](https://msdn.microsoft.com/en-us/library/windows/apps/xaml/dn642089.aspx) - The Bing Maps control built into the Windows UWP platform.
* [Bing Maps WPF SDK ](https://msdn.microsoft.com/en-us/library/hh750210.aspx) - The Bing Maps WPF API.
* [Bing Maps REST Toolkit](https://github.com/Microsoft/BingMapsRESTToolkit) - This is a portable class library which makes it easy to access the Bing Maps REST services from .NET.
* [Bing Maps Spatial Data Services Toolkit](https://github.com/Microsoft/BingMapsSDSToolkit) - This toolkit makes it easy to use the Bing Maps Spatial Data Services (SDS) in .NET.
* [BotBuild-Location](https://github.com/Microsoft/BotBuilder-Location) - An open-source location picker control for Microsoft Bot Framework powered by Bing Maps REST services.
* [SharpMap](http://sharpmap.codeplex.com/) - SharpMap is an easy-to-use mapping library for use in web and desktop applications.
* [DotSpatial](https://dotspatial.codeplex.com/) - DotSpatial is a geographic information system library written for .NET 4.
* [NTS Net Topology Suite](https://github.com/NetTopologySuite/NetTopologySuite) - A .NET GIS solution that is fast and reliable for the .NET platform.
* [GDAL/OGR CSharp](https://trac.osgeo.org/gdal/wiki/GdalOgrInCsharp) - C# bindings for GDAL and OGR.
* [MaxRev.Gdal.Core](https://github.com/MaxRev-Dev/gdal.netcore) - Bindings for GDAL and OGR (both win-x64 and linux-x64). 
* [Geo](https://github.com/sibartlett/Geo) - A geospatial library for .NET
* [SharpKml](https://sharpkml.codeplex.com/) - Is able to read/write both KML files and KMZ files.
* [Mapbox Maps SDK for Unity](https://www.mapbox.com/unity-sdk/) - The Maps SDK for Unity is a collection of tools for building Unity applications from real map data.
* [osmsharp](http://www.osmsharp.com/) - OsmSharp is a C# library to work with OpenStreetMap (OSM) data.
* [GeoJSON4EntityFramework](https://github.com/alatas/GeoJSON4EntityFramework) - Create GeoJSON from Entity Framework Spatial Data or WKT.
* [GeoJSON.Net](https://github.com/GeoJSON-Net/GeoJSON.Net) - .Net library for GeoJSON types & corresponding Json.Net (de)serializers.
* [Earth-Lens](https://github.com/Microsoft/Earth-Lens) - Earth Lens, a Microsoft Garage project is an iOS iPad application that helps people and organizations quickly identify and classify objects in aerial imagery through the power of machine learning.
* [ArcBruTile](https://github.com/ArcBruTile/ArcBruTile) - ArcBruTile displays a collection of maps in ArcGIS Pro 2.0 and ArcMap 10.0 - 10.6.
* [BruTile](https://github.com/BruTile/BruTile) - BruTile is a .NET library to access tile services like those of OpenStreetMap, MapBox or GeodanMaps.
* [DEM Net Elevation API](https://github.com/dem-net/DEM.Net) - 3D terrain generation library, provides access to global DEM datasets (OpenTopography, Nasa ASTER) and tiled imagery services. GlTF and STL export formats supported. [Live demo](https://elevationapi.com)


## C++

* [GEOS](https://trac.osgeo.org/geos/) :star2: - GEOS (Geometry Engine - Open Source) is a C++ port of the Java Topology Suite (JTS).
* [GDAL](http://www.gdal.org/) :star2: - Geospatial Data Abstraction Library (GDAL) is a computer library that serve as a translator library for raster and vector geospatial data formats.
* [Mapnik](http://mapnik.org/) - C++ library for map rendering.
* [Terralib](http://www.dpi.inpe.br/terralib5/wiki/doku.php?id=start) - TerraLib is a GIS classes and functions open source library.
* [Boost Geometry](http://www.boost.org/doc/libs/1_61_0/libs/geometry/doc/html/index.html) :star2: - Part of collection of the Boost C++ Libraries, defines concepts, primitives and algorithms for solving geometry problems.
* [Capaware](https://en.wikipedia.org/wiki/Capaware) - 3D terrain representation with multilayer representation.
* [libspatialindex](https://github.com/libspatialindex/libspatialindex) - C++ implementation of R*-tree, an MVR-tree and a TPR-tree with C API.
* [Spatial](https://sourceforge.net/projects/spatial/) - Spatial is a generic header-only C++ library providing multi-dimensional in-memory containers, iterators and functionals.
* [geojson-vt-cpp](https://github.com/mapbox/geojson-vt-cpp) - Port to C++ of JS GeoJSON-VT for slicing GeoJSON into vector tiles on the fly.
* [Supercluster](https://github.com/mapbox/supercluster.hpp) - A C++14 port of supercluster, a fast 2D point clustering library for use in interactive maps.
* [Mapbox GL Native](https://github.com/mapbox/mapbox-gl-native) - Render Mapbox styles in mobile, desktop, and node applications using C++ and OpenGL.
* [Mapbox Maps SDK for Qt](https://www.mapbox.com/qt/) - Qt Automotive Map Suite. 
* [Mapzen Tangram-ES](https://github.com/tangrams/tangram-es) - C++ library for rendering 2D and 3D maps using OpenGL ES 2 with custom styling and interactions
* [Mapnik Vector Tile](https://github.com/mapbox/mapnik-vector-tile) - Mapnik C++ implemention of Mapbox Vector Tile specification.
* [Vector Tiles Producer](https://github.com/vross/vector-tiles-producer) - Command line tool in C++ to creates vector tiles for a given area at chosen zoom levels using a Mapnik XML.
* [libGeoTiff](https://trac.osgeo.org/geotiff/) - Manipulate TIFF based interchange format for georeferenced raster imagery.
* [Orfeo ToolBox](https://www.orfeo-toolbox.org/) - Orfeo TooLBox (OTB) is an open-source C++ library for remote sensing images processing, distributed under the CeCILL-v2 licence.
* [ITK](https://itk.org/) - ITK is an open-source, cross-platform system that provides developers with an extensive suite of software tools for image analysis.
* [RSGISLib](https://bitbucket.org/petebunting/rsgislib/src/bf7933996822?at=default) - The Remote Sensing and GIS software library (RSGISLib) is a collection of tools for processing remote sensing and GIS datasets. The tools are accessed using Python bindings or an XML interface.
* [OSRM (Open Source Routing Machine)](http://project-osrm.org/) - High performance routing engine written in C++, designed to run on OpenStreetMap data. Services available: Nearest, Route, Table, Match, Trip, Tile.
* [OpenOrienteering Mapper](https://github.com/OpenOrienteering/mapper) - OpenOrienteering Mapper is a software for creating maps for the orienteering sport.
* [TauDEM](https://github.com/dtarb/TauDEM) - Terrain Analysis Using Digital Elevation Models (TauDEM) software for hydrologic terrain analysis and channel network extraction. 
* [osgearth](https://github.com/gwaldron/osgearth) - A free open source C++ geospatial toolkit.
* [dreich_algorithm](https://github.com/csdms-contrib/dreich_algorithm) - Algorithm for extracting channel networks from high resolution topographic data.
* [gSLICr](https://github.com/carlren/gSLICr) - Real-time super-pixel segmentation.
* [LASzip](https://github.com/LASzip/LASzip) - Quickly turns bulky LAS files into compact LAZ files without information loss.
* [laz-perf](https://github.com/hobu/laz-perf) - Alternative LAZ implementation for C++ and JavaScript.
* [entwine](https://github.com/connormanning/entwine) - Entwine is a data organization library for massive point clouds, designed to conquer datasets of hundreds of billions of points as well as desktop-scale point clouds.
* [OpenDroneMap](https://github.com/OpenDroneMap/OpenDroneMap) - OpenDroneMap is a tool to postprocess drone, balloon, kite, and street view data to geographic data including orthophotos, point clouds, & textured mesh.
* [S2 Geometry](https://github.com/google/s2geometry) - Computational geometry and spatial indexing on the sphere.
* [TIN Terrain](https://github.com/heremaps/tin-terrain) - A command-line tool for converting heightmaps in GeoTIFF format into tiled optimized meshes.
* [tippecanoe](https://github.com/mapbox/tippecanoe) - Build vector tilesets from large collections of GeoJSON features.
* [Selene](https://github.com/kmhofmann/selene) - A C++14 image representation, processing and I/O library.
* [Pronto Raster](https://github.com/ahhz/raster) - C++ library for geographical raster data analysis.
* [valhalla](https://github.com/valhalla/valhalla) - Open Source Routing Engine for OpenStreetMap.
* [Halide](https://github.com/halide/Halide) - Halide is a programming language designed to make it easier to write high-performance image processing code on modern machines.
* [gdalcubes](https://github.com/appelmar/gdalcubes) - gdalcubes is a library to represent collections of Earth Observation (EO) images as on demand data cubes (or multidimensional arrays).
* [hydroflow](https://github.com/sistemalabgis/hydroflow) - Compute drainage orders in drainage basins using Strahler and Shreve methods.
* [otbtf](https://github.com/remicres/otbtf) - Deep learning with otb.
* [prepair](https://github.com/tudelft3d/prepair) - Automatic repair of single polygons (according to the OGC Simple Features / ISO19107 rules) using a constrained triangulation.
* [pprepair](https://github.com/tudelft3d/pprepair) - Validation and Automatic Repair of Planar Partitions.
* [OSMExpress](https://github.com/protomaps/OSMExpress) - Fast database file format for OpenStreetMap.
* [depthmapX](https://github.com/varoudis/depthmapX) - Multi-platform Spatial Network Analysis Software.


## C

* [Shapefile C Library](http://shapelib.maptools.org/) - Provides the ability to write simple C programs for reading, writing and updating (to a limited extent) .shp and .dbf files.
* [Datamaps](https://github.com/ericfischer/datamaps) - This is a tool for indexing large lists of geographic points or lines and dynamically generating map tiles from the index for display.
* [H3](https://github.com/uber/h3) - Hexagonal hierarchical geospatial indexing system.
* [YOLT](https://github.com/CosmiQ/yolt) - You Only Look Twice: Rapid Multi-Scale Object Detection In Satellite Imagery.
* [libpostal](https://github.com/openvenues/libpostal) - A C library for parsing/normalizing street addresses around the world. Powered by statistical NLP and open geo data.
* [libvips](https://github.com/libvips/libvips) - A fast image processing library with low memory needs.
* [udunits2](https://github.com/Unidata/UDUNITS-2) - API and utility for arithmetic manipulation of units of physical quantities.
* [FORCE](https://github.com/davidfrantz/force) - Framework for Operational Radiometric Correction for Environmental monitoring.


## Fortran
* [6S](http://6s.ltdri.org/) - Second Simulation of the Satellite Signal in the Solar Spectrum (6S) open source algorithm.
* [SWAT](https://github.com/WatershedModels/SWAT) - Implementation of SWAT model.
* [SPECFEM3D_GLOBE](https://github.com/geodynamics/specfem3d_globe) - SPECFEM3D_GLOBE simulates global and regional (continental-scale) seismic wave propagation.


## Go

* [S2](https://github.com/golang/geo) - S2 is a library for spherical geometry that aims to have the same robustness, flexibility, and performance as the best planar geometry libraries.
* [GoSpatial](https://github.com/jblindsay/go-spatial) - GoSpatial is a simple command-line interface program for manipulating geospatial data.
* [BuntDB](https://github.com/tidwall/buntdb) - BuntDB is an embeddable, in-memory key/value database for Go with custom indexing and geospatial support.
* [Go GDAL](https://github.com/lukeroth/gdal) - Go (golang) wrapper for GDAL, the Geospatial Data Abstraction Library.
* [Go-shp](https://github.com/jonas-p/go-shp) - Go library for reading and writing ESRI Shapefiles. Pure Golang implementation based on the ESRI Shapefile technical description.
* [Go-proj-4](https://github.com/pebbe/go-proj-4) - Go bindings for the Cartographic Projections Library PROJ.4.
* [Draw2D](https://github.com/llgcode/draw2d) - 2D rendering for different output (raster, pdf).
* [Go.Geo](https://github.com/paulmach/go.geo) - Geometry/geography library in Go.
* [geom](https://github.com/ctessum/geom) - Geometry objects and functions for Go.
* [go-geom](https://github.com/twpayne/go-geom) - Go library for handling geometries.
* [lidario](https://github.com/jblindsay/lidario) - A small Go library for reading and writing LiDAR (LAS) files.
* [BoxTree](https://github.com/tidwall/boxtree) - An R-tree implementation for Go.
* [gopostal](https://github.com/openvenues/gopostal) - Go (cgo) interface to libpostal for fast international address parsing/normalization.


## Rust

* [rust-geo](https://github.com/georust/rust-geo) - Geospatial primitives and algorithms for Rust.
* [rust-gdal](https://github.com/georust/rust-gdal) - Rust bindings for GDAL.
* [rust-proj](https://github.com/georust/rust-proj) - Rust bindings for Proj.
* [rust-geojson](https://github.com/georust/rust-geojson) - Library for serializing the GeoJSON vector GIS file format.
* [rust-topojson](https://github.com/georust/rust-topojson) - TopoJSON bindings and utilities for Rust.
* [rust-geohash](https://github.com/georust/rust-geohash) - Geohash for Rust.
* [rust-wkt](https://github.com/georust/rust-wkt) - Rust read/write support for well-known text (WKT).
* [rust-polyline](https://github.com/georust/rust-polyline) - Google Encoded Polyline encoding & decoding in Rust.
* [rust-geocoding](https://github.com/georust/rust-geocoding) - Geocoding library for Rust.
* [rust-osm](https://github.com/georust/rust-osm) - OSM XML serialization and other OpenStreetMap utilities.
* [rust-shapefile](https://github.com/georust/rust-shapefile) - Rust read/write support for shapefiles.
* [rust-gpx](https://github.com/georust/rust-gpx) - Rust read/write support for GPS Exchange Format (GPX).
* [Hecate](https://github.com/mapbox/Hecate) - Fast Geospatial Feature Storage API.
* [kdtree-rs](https://github.com/mrhooray/kdtree-rs) - K-dimensional tree in Rust for fast geospatial indexing and nearest neighbors lookup
* [Martin](https://github.com/urbica/martin) - Martin is a PostGIS vector tiles server suitable for large databases. Martin is written in Rust using Actix web framework.
* [WhiteboxTools](https://github.com/jblindsay/whitebox-tools) - An advanced geospatial data analysis platform.


## Ruby

* [Geokit](http://geokit.rubyforge.org/) - A Ruby gem & Rails plugin for easier map-based applications.
* [Rgeo](https://github.com/rgeo/rgeo) - RGeo is a geospatial data library for Ruby. It provides an implementation of the Open Geospatial Consortium's Simple Features Specification
* [Rgeo Shapefile](https://github.com/rgeo/rgeo-shapefile) - Optional module for RGeo for reading geospatial data from ESRI shapefiles.
* [Rgeo GeoJSON](https://github.com/rgeo/rgeo-geojson) - RGeo component for reading and writing GeoJSON.
* [ffi-geos](https://github.com/dark-panda/ffi-geos) - Low-level ruby bindings to GEOS library.
* [PostGIS ActiveRecord Adapter](https://github.com/rgeo/activerecord-postgis-adapter) - ActiveRecord adapter for PostGIS.
* [SpatiaLite ActiveRecord Adapter](https://github.com/rgeo/activerecord-spatialite-adapter) - ActiveRecord adapter for Spatialite.
* [Mongoid Geospatial](https://github.com/nofxx/mongoid-geospatial) - A Mongoid Extension that simplifies the use of MongoDB spatial features.
* [Ruby Geocoder](http://www.rubygeocoder.com/) - Integration with geocoding services.
* [ruby_postal](https://github.com/openvenues/ruby_postal) - Ruby bindings to libpostal for fast international address parsing/normalization.
* [Agroclimatology](https://github.com/beaorn/agroclimatology) - Ruby client for interacting with the NASA (POWER) Agroclimatology Web Resource.
* [Evapotranspiration](https://github.com/beaorn/evapotranspiration) - Ruby library for calculating reference crop evapotranspiration (ETo).


## PHP

* [GeoPHP](https://geophp.net/) - Advanced geometry operations in PHP.
* [PHP7 Mapnik](https://github.com/garrettrayj/php7-mapnik) - PHP extension for geospatial rendering with Mapnik.
* [geospatial](https://github.com/php-geospatial/geospatial) - PHP Extension to handle common geospatial functions.
* [geojson](https://github.com/jmikola/geojson) - GeoJSON implementation for PHP.
* [laravel-geo](https://github.com/eleven-lab/laravel-geo) - GeoSpatial integration on Laravel 5.2+ that supports MySQL and PostgreSQL.
* [shapefile](https://github.com/phpmyadmin/shapefile) - ESRI ShapeFile library for PHP.
* [ShapeReader](https://github.com/muka/ShapeReader) - A PHP library to parse ESRI Shape files.
* [php-libspatialite](https://github.com/rukandax/php-libspatialite) - PHP Query Builder for SQLite data with Spatial SQL Capabilities.
* [laragis](https://github.com/ralphschindler/laragis) - A standalone Geo/GIS Provider for Laravel.
* [li3_geo](https://github.com/nateabele/li3_geo) - Adds geospatial support to Lithium for multiple databases, including MongoDB, CouchDB and MySQL.
* [FreeGeoDB](https://github.com/delight-im/FreeGeoDB) - Free database of geographic place names and corresponding geospatial data.


## Lua

* [TerraME](http://www.terrame.org/doku.php) - TerraME is a programming environment for spatial dynamical modelling. It supports cellular automata, agent-based models, and network models running in 2D cell spaces.
* [Tarantool/GIS](https://github.com/tarantool/gis) - A full-featured geospatial extension for Tarantool.
* [geo.lua](https://github.com/RedisLabs/geo.lua) - A helper library for Redis geospatial indices.


## Lisp
* [cl-ewkb](https://github.com/filonenko-mikhail/cl-ewkb/) - Common Lisp PostGIS EWKB data model and encoder/decoder.
* [cl-proj](https://bitbucket.org/vityok/cl-proj) - CL-PROJ provides CFFI-based Common Lisp bindings for the PROJ.4 library.
* [utm](https://github.com/jl2/utm) - Lisp library for converting between latitude/longitude and UTM.


## Haskell

* [Naqsha](https://github.com/naqsha/naqsha) - Naqsha is a Haskell library to work with geospatial data types.
* [TerraHS](https://wiki.haskell.org/TerraHS) - TerraHS is a software component that enables the development of geographical applications in a functional language, using the data handling capabilities and spatial operations of TerraLib.


## Elixir

* [geo](https://github.com/bryanjos/geo) - A collection of GIS functions for Elixir.
* [Geometry Library](https://github.com/pkinney/topo) - A Geometry library for Elixir that calculates spatial relationships between two geometries.
* [distance](https://github.com/pkinney/distance) - Provides a set of distance functions for use in GIS or graphic applications.


## Swift

* [GEOSwift](https://github.com/GEOSwift/GEOSwift) - The Swift Geographic Engine.
* [turf-swift](https://github.com/mapbox/turf-swift) - A Swift language port of Turf.js.
* [MapboxDirections.swift](https://github.com/mapbox/MapboxDirections.swift) - Traffic-aware directions in Swift or Objective-C on iOS, macOS, tvOS, and watchOS.
* [Mapbox Navigation SDK for iOS](https://github.com/mapbox/mapbox-navigation-ios) - Turn-by-turn navigation logic and UI in Swift or Objective-C on iOS.
* [Apple MapKit](https://developer.apple.com/documentation/mapkit) - Display map or satellite imagery directly from your app's interface, call out points of interest, and determine placemark information for map coordinates.


## Scala

* [geoscript.scala](https://github.com/dwins/geoscript.scala) - Scala implementation of the GeoScript API.
* [mapnik2geotools](https://github.com/dwins/mapnik2geotools) - Using the Scala XML API to translate from Mapnik XML to GeoTools' SLD dialect.
* [GeoTrellis](https://github.com/locationtech/geotrellis) - GeoTrellis is a Scala library and framework that uses Spark to work with raster data.


## Groovy

* [GeoScript Groovy](https://github.com/geoscript/geoscript-groovy) - GeoScript Groovy is the Groovy implementation of GeoScript.


## Delphi

* [DSpatial](http://dspatial.sourceforge.net/) - DSpatial is an Open Source software development project to provide developers using Delphi with a library of tools for the use, manipulation, and visualization of spatial data.


## CSS

* [CartoCSS](https://www.mapbox.com/tilemill/docs/manual/carto/) - TileMills language.
* [MapCSS](http://wiki.openstreetmap.org/wiki/MapCSS) - MapCSS is a CSS-like language for map stylesheets.


## IDL
* [LandTrendr](https://github.com/KennedyResearch/LandTrendr-2012) - LandTrendr (Landsat-based Detection of Trends in Disturbance and Recovery) attempt to capture, label, and map changes in Earth's surface for use in science, natural resource management, and education.


## Julia 

* [RasterIO.jl](https://github.com/wkearn/RasterIO.jl) - Simple Raster Formats for Julia.
* [OpenStreetMaps.jl](https://github.com/tedsteiner/OpenStreetMap.jl) - This package provides basic functionality for parsing, viewing, and working with OpenStreetMap map data.
* [GDALfuns.jl](https://github.com/meggart/GDALfuns.jl) - Auto-generated low-level wrapper for the GDAL library.
* [JuliaGIS](https://github.com/wkearn/GIS.jl) - A package for the visualization and manipulation of geographic data.
* [LibGEOS.jl](https://github.com/JuliaGeometry/LibGEOS.jl) - LibGEOS is a LGPL-licensed package for manipulation and analysis of planar geometric objects, based on the libraries GEOS (the engine of PostGIS) and JTS (from which GEOS is ported).
* [LibLAS.jl](https://github.com/visr/LibLAS.jl) - Julia wrapper for LibLAS, a library for reading and writing the LAS LiDAR format.
* [GeoJSON.jl](https://github.com/JuliaGeo/GeoJSON.jl) - This library is developed independently of, but is heavily influenced in design by the python-geojson package.
* [Turf.jl](https://github.com/yeesian/Turf.jl) - This library is a port of Turf.js to the Julia programming language for geospatial analysis.
* [Images.jl](https://github.com/JuliaImages/Images.jl) - An image processing library for Julia.
* [GeoStats.jl](https://github.com/juliohm/GeoStats.jl) - Geostatistics in Julia.
* [ArchGDAL](https://github.com/yeesian/ArchGDAL.jl) - Vector and Raster interfaces.
* [Proj4.jl](https://github.com/JuliaGeo/Proj4.jl) - A simple wrapper around the Proj.4 cartographic projections library.
* [Geodesy.jl](https://github.com/JuliaGeo/Geodesy.jl) - Work with points defined in various coordinate systems.
* [Shapefile.jl](https://github.com/JuliaGeo/Shapefile.jl) - Parsing .shp files in Julia.
* [NetCDF.jl](https://github.com/JuliaGeo/NetCDF.jl) - NetCDF support for the julia programming language.
* [GeoInterface.jl](https://github.com/JuliaGeo/GeoInterface.jl) - A Julia Protocol for Geospatial Data.
* [GeoStatsImages.jl](https://github.com/juliohm/GeoStatsImages.jl) - Training images for geostastical simulation in Julia.
* [DataFrames.jl](https://github.com/JuliaStats/DataFrames.jl) - Tools for working with tabular data in Julia.
* [VoronoiDelaunay.jl](https://github.com/JuliaGeometry/VoronoiDelaunay.jl) - Fast, robust construction of 2D Delaunay and Voronoi tessellations on generic point types.
* [EcologicalNetwork.jl](https://github.com/PoisotLab/EcologicalNetwork.jl) - This julia package provides a common interface to analyze all types of data on ecological networks.
* [ClimateTools.jl](https://github.com/Balinus/ClimateTools.jl) - Collection of commonly-used tools in Climate Science.
* [Interpolations.jl](https://github.com/juliohm/Interpolations.jl) - This package implements a variety of interpolation schemes for the Julia language.
* [NMEA.jl](https://github.com/zznop/NMEA.jl) - NMEA.jl is a package for parsing NMEA GPS protocol sentences.
* [Watershed.jl](https://github.com/seung-lab/Watershed.jl) - This is a translation of Zlateski's C++ Watershed code.
* [ImageSegmentation.jl](https://github.com/JuliaImages/ImageSegmentation.jl) - Julia package for multiple Image Segmentation Algorithms.
* [ImageMorphology.jl](https://github.com/JuliaImages/ImageMorphology.jl) - This package provides morphology-related functionality to the Images.jl project.
* [ImageFiltering.jl](https://github.com/JuliaImages/ImageFiltering.jl) - ImageFiltering implements blurring, sharpening, gradient computation, and other linear filtering operations, as well nonlinear filters like min/max.
* [ImageTransformations.jl](https://github.com/JuliaImages/ImageTransformations.jl/tree/master/src) - This package provides support for image resizing, image rotation, and other spatial transformations of arrays.
* [ImageMetadata.jl](https://github.com/JuliaImages/ImageMetadata.jl) - ImageMetadata is a simple package providing utilities for working with images that have metadata attached.
* [Tinker.jl](https://github.com/JuliaImages/Tinker.jl) - Interactive graphical tool for complex image analysis.
* [ImageFeatures.jl](https://github.com/JuliaImages/ImageFeatures.jl) - Image feature detection for the Julia language.
* [ViziCities](https://github.com/UDST/vizicities#getting-started) - A framework for 3D geospatial visualization in the browser.
* [Terriajs](https://github.com/TerriaJS/terriajs) - A library for building rich, web-based geospatial data explorers. 
* [LazIO.jl](https://github.com/evetion/LazIO.jl) - Extends LasIO with Laszip integration.
* [LASindex.jl](https://github.com/evetion/LASindex.jl) - Pure Julia reader of lasindex .lax files.
* [LibSpatialIndex.jl](https://github.com/JuliaGeo/LibSpatialIndex.jl) - A library for spatially indexing kD bounding box data (based on libspatialindex).
* [GeoMakie.jl](https://github.com/JuliaPlots/GeoMakie.jl) - Geographical plotting utilities for Makie.jl


## JavaScript
* [OpenLayers](http://openlayers.org/) :star2: - Open source AJAX library.
* [Leaflet](http://leafletjs.com/) :star2: - Open-Source JavaScript Library for Mobile-Friendly Interactive Maps.
* [Google Maps API](https://developers.google.com/maps/documentation/javascript/?hl=pt-br) :star2: - Google Maps API for JavaScript.
* [gmaps.js](https://github.com/hpneo/gmaps) - gmaps.js allows you to use the potential of Google Maps in a simple way. 
* [Bing Maps V8 Web Control](https://msdn.microsoft.com/en-us/library/mt712542.aspx) - Bing Maps API for JavaScript.
* [Bing Maps V8 Interactive SDK](https://www.bing.com/api/maps/sdkrelease/mapcontrol/isdk#loadMapWithOptions+JS) - An interactive code sample gallery for Bing Maps V8.
* [Bing Maps V8 Code Samples](https://github.com/Microsoft/BingMapsV8CodeSamples) - A large collection of open source code samples for Bing Maps V8.
* [Bing Maps V8 TypeScript Definitions ](https://github.com/Microsoft/Bing-Maps-V8-TypeScript-Definitions) - TypeScript Definitions for the Bing Maps V8 web control.
* [ArcGIS API](https://developers.arcgis.com/javascript/) :star2: - ArcGIS API for JavaScript.
* [SuperMap iClient for JavaScript](http://iclient.supermap.io) - Cloud GIS web client development platform supportted by SuperMap.
* [deck.gl](https://github.com/uber/deck.gl) - WebGL2 powered geospatial visualization layers.
* [react-map-gl](https://github.com/uber/react-map-gl) - React friendly API wrapper around MapboxGL JS.
* [react-leaflet](https://github.com/PaulLeCam/react-leaflet) - React components for Leaflet maps.
* [Vue2Leaflet](https://github.com/KoRiGaN/Vue2Leaflet) - Vue 2 components for Leaflet maps.
* [Heatmap.js](https://www.patrick-wied.at/static/heatmapjs/) - A heatmap implementation for Javascript.
* [Thermo.js](https://github.com/dazuma/thermo.js) - Another heatmap implementation for Javascript.
* [Heatcanvas.js](https://github.com/sunng87/heatcanvas) - Yet another heatmap implementation for Javascript.
* [GeoExt](https://geoext.github.io/geoext3/) - Open Source and enables building desktop-like GIS applications through the web. It is a JavaScript framework that combines the GIS functionality of OpenLayers with the user interface of the ExtJS library provided by Sencha.
* [iTowns](http://www.itowns-project.org/) - A Three.js-based framework written in Javascript/WebGL for visualizing 3D geospatial data. It can connect to WMS/WMTS/TMS servers including elevation data and load many different data formats (3dTiles, gpx, KML and much much more).
* [proj4js](https://github.com/proj4js/proj4js) - JavaScript library to transform coordinates from one coordinate system to another, including datum transformations.
* [mapbox-gl-draw](https://github.com/mapbox/mapbox-gl-draw) - Draw tools for mapbox-gl-js.
* [mapboxgl-powerbi](https://github.com/mapbox/mapboxgl-powerbi) - Mapbox GL PowerBI custom visual.
* [NASA WebWorldWind](https://github.com/NASAWorldWind/WebWorldWind) - The NASA WorldWind Javascript SDK (WebWW) includes the library and examples for creating geo-browser web applications and for embedding a 3D globe in HTML5 web pages.
* [CesiumJS](https://github.com/AnalyticalGraphicsInc/cesium) - An open-source JavaScript library for world-class 3D globes and maps.
* [LuciadRIA](http://www.luciad.com/solutions/luciadria) - A JavaScript library for 3D globes and maps, with support for military symbology and desktop-like performance
* [geotiff.js](https://github.com/geotiffjs/geotiff.js) - geotiff.js is a small library to parse TIFF files for visualization or analysis.
* [geoblaze](https://github.com/GeoTIFF/geoblaze) - Geoblaze is a geospatial raster processing engine written purely in javascript.
* [Turf.js](http://turfjs.org/) :star2: - Advanced geospatial analysis for browsers and node.
* [JSTS](https://github.com/bjornharrtell/jsts) - Port of the Java JTS library.
* [Spatial](https://github.com/troufster/spatial) - A 2d spatial hash module for node.js.
* [PGRestAPI](https://github.com/spatialdev/PGRestAPI) - Node.js REST API for PostGres Spatial Entities.
* [Supercluster](https://github.com/mapbox/supercluster) - A crazy fast geospatial point clustering library for browsers and Node.
* [SQLite3](https://github.com/mapbox/node-sqlite3) - Asynchronous, non-blocking SQLite3 bindings for Node.js.
* [Windshaft](https://github.com/CartoDB/Windshaft) - A Node.js map tile library for PostGIS and torque.js, with CartoCSS styling.
* [kepler.gl](https://uber.github.io/kepler.gl/#/) - kepler.gl is a data-agnostic, high-performance web-based application for visual exploration of large-scale geolocation data sets.
* [Leaflet TimeDimension](https://github.com/socib/Leaflet.TimeDimension) - Add time dimension capabilities on a Leaflet map.
* [overpass-turbo](https://github.com/tyrasd/overpass-turbo) - A web based data mining tool for OpenStreetMap using Overpass API.
* [pixelmatch](https://github.com/mapbox/pixelmatch) - The smallest, simplest and fastest JavaScript pixel-level image comparison library. 
* [ui-leaflet](https://github.com/angular-ui/ui-leaflet) - AngularJS directive to embed an interact with maps managed by Leaflet library.
* [Geokit](https://github.com/developmentseed/geokit) - Geokit is a command-line interface (CLI) tool written in javascript, that contains all the basic functionalities for measurements, conversions and operations of geojson files.
* [arc.js](https://github.com/springmeyer/arc.js) - Calculate great circles routes as lines in GeoJSON or WKT format.
* [tilegarden](https://github.com/azavea/tilegarden) - Serverless raster and vector map tile generation using Mapnik and AWS Lambda.
* [OSM Building](https://osmbuildings.org/) - A JavaScript library for visualizing OpenStreetMap building geometry on 2D and 3D maps.
* [Galton](https://github.com/urbica/galton) - Lightweight Node.js isochrone server. Build isochrones using OSRM, Turf and concaveman.
* [TileStrata](https://github.com/naturalatlas/tilestrata) - A pluggable Node.js map tile server.
* [tilestrata-mapnik](https://github.com/naturalatlas/tilestrata-mapnik) - TileStrata provider for rendering tiles with mapnik.
* [TileMantle](https://github.com/naturalatlas/tilemantle) - A tool to warm up your tile server cache. Give it a URL template, geometry, and list of zoom levels and it will request tiles incrementally to warm it up.
* [landspeed.js](https://github.com/springmeyer/landspeed.js) - WMS server using node-mapnik.
* [tilelive-postgis](https://github.com/stepankuzmin/tilelive-postgis) - Implements the tilelive API for generating mapnik vector tiles from PostGIS.
* [GeoPackage.js](https://github.com/ngageoint/geopackage-js) - GeoPackage JS is an implementation of the OGC GeoPackage spec. This library works in both the browser and Node 4+.
* [mapshaper-proj](https://github.com/mbloch/mapshaper-proj) - A JavaScript port of the Proj.4 map projection library.
* [Geodesy](https://github.com/chrisveness/geodesy) - Libraries of geodesy functions implemented in JavaScript.
* [d3-geomap](https://d3-geomap.github.io/) - A library for creating geographical maps based on D3.js.
* [Arabesque](https://github.com/gflowiz/arabesque) - Arabesque is a web application for thematic mapping of flow and networks datasets.
* [Ginkgoch](https://ginkgoch.com) - Ginkgoch is a GIS visualization, analyze library on Node.js. It allows to build cross-platform GIS services, desktop and mobile apps.



## R

* [sf](https://github.com/r-spatial/sf) :star2: - Simple Features for R.
* [sp](https://cran.r-project.org/web/packages/sp/index.html) - Classes and Methods for Spatial Data.
* [rgdal](https://cran.r-project.org/web/packages/rgdal/index.html) - Bindings for the Geospatial Data Abstraction Library.
* [raster](https://cran.r-project.org/web/packages/raster/raster.pdf) :star2: - Reading, writing, manipulating, analyzing and modeling of gridded spatial data.
* [ggplot2](http://ggplot2.org/) - ggplot2 is a plotting system for R.
* [ggmap](https://cran.r-project.org/web/packages/ggmap/index.html) - Spatial Visualization with ggplot2.
* [rgeos](https://cran.r-project.org/web/packages/rgeos/index.html) - Interface to Geometry Engine - Open Source (GEOS) using the C API for topology operations on geometries.
* [rgrass7](https://cran.r-project.org/web/packages/rgrass7/index.html) - Interface Between GRASS 7 GIS and R.
* [RQGIS](https://cran.r-project.org/web/packages/RQGIS/index.html) - Establishes an interface between R and QGIS.
* [RSAGA](https://cran.r-project.org/web/packages/RSAGA/index.html) - SAGA Geoprocessing and Terrain Analysis in R.
* [RODBC](https://cran.r-project.org/web/packages/RODBC/index.html) - ODBC Database Access.
* [Rnetcdf](https://cran.r-project.org/web/packages/RNetCDF/index.html) - Interface to NetCDF Datasets.
* [ncdf4](https://cran.r-project.org/web/packages/ncdf4/index.html) - Provides a high-level R interface to data files written using Unidata's netCDF library (version 4 or earlier).
* [RPyGeo](https://cran.r-project.org/web/packages/RPyGeo/index.html) - ArcGIS Geoprocessing in R via Python.
* [shapefiles](https://cran.r-project.org/web/packages/shapefiles/index.html) - Read and Write ESRI Shapefiles.
* [Rgooglemaps](https://cran.r-project.org/web/packages/RgoogleMaps/index.html) - Overlays on Google map tiles in R.
* [leafletR](https://cran.r-project.org/web/packages/leafletR/index.html) - Interactive Web-Maps Based on the Leaflet JavaScript Library.
* [maptools](https://cran.r-project.org/web/packages/maptools/index.html) - Tools for Reading and Handling Spatial Objects.
* [RArcInfo](https://cran.r-project.org/web/packages/RArcInfo/index.html) - Functions to import data from Arc/Info V7.x binary coverages.
* [Akima](https://cran.r-project.org/web/packages/akima/index.html) - Interpolation of Irregularly and Regularly Spaced Data.
* [maps](https://cran.r-project.org/web/packages/maps/index.html) - Draw Geographical Maps.
* [PBSmapping](https://cran.r-project.org/web/packages/PBSmapping/index.html) - Mapping Fisheries Data and Spatial Analysis Tools.
* [PBSmodelling](https://cran.r-project.org/web/packages/PBSmodelling/index.html) - Provides modelling support.
* [Landsat](https://cran.r-project.org/web/packages/landsat/index.html) - Radiometric and topographic correction of satellite imagery.
* [spatstat](https://cran.r-project.org/web/packages/spatstat/index.html) - Spatial Point Pattern Analysis, Model-Fitting, Simulation, Tests.
* [s2](https://github.com/spatstat/s2) - R bindings for Google's s2 library for geometry on the sphere.
* [splancs](https://cran.r-project.org/web/packages/splancs/index.html) - Spatial and Space-Time Point Pattern Analysis.
* [smacpod](https://cran.r-project.org/web/packages/smacpod/index.html) - Various statistical methods for analyzing case-control point data.
* [DSpat](https://cran.r-project.org/web/packages/DSpat/index.html) - Fits inhomogeneous Poisson process spatial models to line transect sampling data and provides estimate of abundance within a region.
* [spatialsegregation](https://cran.r-project.org/web/packages/spatialsegregation/index.html) - Summaries for measuring segregation/mingling in multitype spatial point patterns with graph based neighbourhood description.
* [dbmss](https://cran.r-project.org/web/packages/dbmss/index.html) - Simple computation of spatial statistic functions of distance to characterize the spatial structures of mapped objects.
* [latticeDensity](https://cran.r-project.org/web/packages/latticeDensity/index.html) -  Contains functions that compute the lattice-based density estimator of Barry and McIntyre.
* [GriegSmith](https://cran.r-project.org/web/packages/GriegSmith/index.html) - Uses the Grieg-Smith method on 2 dimensional spatial data.
* [plotKML](https://cran.r-project.org/web/packages/plotKML/index.html) - Visualization of Spatial and Spatio-Temporal Objects in Google Earth.
* [OpenStreetMap](https://cran.r-project.org/web/packages/OpenStreetMap/index.html) - Access to Open Street Map Raster Images.
* [GEOmap](https://cran.r-project.org/web/packages/GEOmap/index.html) - Topographic and Geologic Mapping.
* [rworldmap](https://cran.r-project.org/web/packages/rworldmap/index.html) - Mapping Global Data.
* [rasterVis](https://cran.r-project.org/web/packages/rasterVis/index.html) - Visualization Methods for Raster Data.
* [spdep](https://cran.r-project.org/web/packages/spdep/index.html) - Spatial Dependence: Weighting Schemes, Statistics and Models.
* [spacetime](https://cran.r-project.org/web/packages/spacetime/index.html) - Classes and Methods for Spatio-Temporal Data.
* [geoR](https://cran.r-project.org/web/packages/geoR/index.html) - Analysis of Geostatistical Data.
* [ecespa](https://cran.r-project.org/web/packages/ecespa/index.html) - Functions for Spatial Point Pattern Analysis.
* [mapproj](https://cran.r-project.org/web/packages/mapproj/index.html) - Map Projections.
* [gstat](https://cran.r-project.org/web/packages/gstat/index.html) - Spatio-Temporal Geostatistical Modelling, Prediction and Simulation.
* [intamap](https://cran.r-project.org/web/packages/intamap/index.html) - Procedures for automated interpolation.
* [micromap](https://cran.r-project.org/web/packages/micromap/index.html) - Package provides linked micromaps using ggplot2.
* [Grid2Polygons](https://cran.r-project.org/web/packages/Grid2Polygons/index.html) - Converts a spatial object from class SpatialGridDataFrame to SpatialPolygonsDataFrame.
* [recmap](https://cran.r-project.org/web/packages/recmap/index.html) - Package provides rectangular cartograms with rectangle sizes reflecting for example population
* [geosphere](https://cran.r-project.org/web/packages/geosphere/index.html) - Permits computations of distance and area to be carried out on spatial data in geographical coordinates.
* [spsurvey](https://cran.r-project.org/web/packages/spsurvey/index.html) - Provides a range of sampling functions.
* [trip](https://cran.r-project.org/web/packages/trip/index.html) - Extends sp classes to permit the accessing and manipulating of spatial data for animal tracking.
* [GeoXp](https://cran.r-project.org/web/packages/GeoXp/index.html) - Permits interactive graphical exploratory spatial data analysis.
* [vec2dtransf](https://cran.r-project.org/web/packages/vec2dtransf/index.html) - Package for applying affine and similarity transformations on vector spatial data (sp objects).
* [spcosa](https://cran.r-project.org/web/packages/spcosa/index.html) - Spatial coverage sampling and random sampling from compact geographical strata created by k-means.
* [dggridR](https://cran.r-project.org/web/packages/dggridR/index.html) - Provides an interface to DGGRID for working with discrete global grids, using hexagons, triangles, and diamonds to overcome the issue that every bin have the same area.
* [hdeco](https://cran.r-project.org/web/packages/hdeco/index.html) -  Provides hierarchical decomposition of entropy for categorical map comparisons.
* [geojsonio](https://cran.r-project.org/web/packages/geojsonio/index.html) - Convert data to 'GeoJSON' or 'TopoJSON' from various R classes, including vectors, lists, data frames, shape files, and spatial classes.
* [geoaxe](https://cran.r-project.org/web/packages/geoaxe/index.html) - Split 'geospatial' objects into pieces. Includes support for some spatial object inputs, 'Well-Known Text', and 'GeoJSON'.
* [magclass](https://cran.r-project.org/web/packages/magclass/index.html) - Data class for increased interoperability working with spatial- temporal data together with corresponding functions and methods (conversions, basic calculations and basic data manipulation).
* [marmap](https://cran.r-project.org/web/packages/marmap/index.html) - Package is designed for downloading, plotting and manipulating bathymetric and topographic data in R.
* [cshapes](https://cran.r-project.org/web/packages/cshapes/index.html) - Package for CShapes, a GIS dataset of country boundaries (1946-today). Includes functions for data extraction and the computation of distance matrices and -lists.
* [taRifx](https://cran.r-project.org/web/packages/taRifx/index.html) - A collection of various utility and convenience functions.
* [lawn](https://cran.r-project.org/web/packages/lawn/index.html) - Client for 'Turfjs' for 'geospatial' analysis. The package revolves around using 'GeoJSON' data.
* [osmar](https://cran.r-project.org/web/packages/osmar/index.html) - Provides infrastructure to access OpenStreetMap data from different sources.
* [gmt](https://cran.r-project.org/web/packages/gmt/index.html) - Interface between the GMT map-making software and R.
* [RColorBrewer](https://cran.r-project.org/web/packages/RColorBrewer/index.html) - Provides color schemes for maps and other graphics.
* [classInt](https://cran.r-project.org/web/packages/classInt/index.html) - Selected commonly used methods for choosing univariate class intervals for mapping or other graphics purposes.
* [plotGoogleMaps](https://cran.r-project.org/web/packages/plotGoogleMaps/index.html) - Interactive plot device for handling the geographic data for web browsers.
* [ggsn](https://cran.r-project.org/web/packages/ggsn/index.html) - Adds north symbols and scale bars in kilometers to maps in geographic or metric coordinates.
* [spatgraphs](https://cran.r-project.org/web/packages/spatgraphs/index.html) - Graphs (or networks) and graph component calculations for spatial locations
* [geoRglm](https://cran.r-project.org/web/packages/geoRglm/index.html) - Functions for inference in generalised linear spatial models.
* [FRK](https://cran.r-project.org/web/packages/FRK/index.html) - Is a tool for spatial/spatio-temporal modelling and prediction with large datasets.
* [geospt](https://cran.r-project.org/web/packages/geospt/index.html) - Contains some geostatistical and radial basis functions, including prediction and cross validation.
* [RandomFields](https://cran.r-project.org/web/packages/RandomFields/index.html) - Methods for the inference on and the simulation of Gaussian fields are provided, as well as methods for the simulation of extreme value random fields.
* [CompRandFld](https://cran.r-project.org/web/packages/CompRandFld/index.html) - A set of procedures for the analysis of Random Fields using likelihood and non-standard likelihood methods is provided.
* [constrainedKriging](https://cran.r-project.org/web/packages/constrainedKriging/index.html) - Provides functions for efficient computations of nonlinear spatial predictions with local change of support.
* [spTimer](https://cran.r-project.org/web/packages/spTimer/index.html) - Fits, spatially predicts and temporally forecasts large amounts of space-time data.
* [SpatialTools](https://cran.r-project.org/web/packages/SpatialTools/index.html) - Tools for spatial data analysis. Emphasis on kriging. Provides functions for prediction and simulation.
* [sperrorest](https://cran.r-project.org/web/packages/sperrorest/index.html) - Implements spatial error estimation and permutation-based variable importance measures for predictive models using spatial cross-validation and spatial block bootstrap.
* [sgeostat](https://cran.r-project.org/web/packages/sgeostat/index.html) - An Object-oriented Framework for Geostatistical Modeling in S+ containing functions for variogram estimation, variogram fitting and kriging as well as some plot functions.
* [spatialCovariance](https://cran.r-project.org/web/packages/spatialCovariance/index.html) - Supports the computation of spatial covariance matrices for data on rectangles.
* [tgp](https://cran.r-project.org/web/packages/tgp/index.html) - Bayesian nonstationary, semiparametric nonlinear regression and design by treed Gaussian processes (GPs) with jumps to the limiting linear model (LLM).
* [regress](https://cran.r-project.org/web/packages/regress/index.html) - Functions to fit Gaussian linear model by maximising the residual log likelihood where the covariance structure can be written as a linear combination of known matrices.
* [FieldSim](https://cran.r-project.org/web/packages/FieldSim/index.html) - Tools for random fields and bridges simulations.
* [georob](https://cran.r-project.org/web/packages/georob/index.html) - Provides functions for fitting linear models with spatially correlated errors by robust and Gaussian Restricted Maximum Likelihood and for computing robust and customary point and block kriging predictions, along with utility functions for cross-validation and for unbiased back-transformation of kriging predictions of log-transformed data.
* [ExceedanceTools](https://cran.r-project.org/web/packages/ExceedanceTools/index.html) - Tools for constructing confidence regions for exceedance regions and contour lines.
* [deldir](https://cran.r-project.org/web/packages/deldir/index.html) - Calculates the Delaunay triangulation and the Dirichlet or Voronoi tessellation (with respect to the entire plane) of a planar point set.
* [tripack](https://cran.r-project.org/web/packages/tripack/index.html) - A constrained two-dimensional Delaunay triangulation package providing both triangulation and generation of voronoi mosaics of irregular spaced data.
* [ipdw](https://cran.r-project.org/web/packages/ipdw/index.html) - Functions are provided to interpolate geo-referenced point data via Inverse Path Distance Weighting.
* [SSN](https://cran.r-project.org/web/packages/SSN/index.html) - Spatial statistical modeling and prediction for data on stream networks, including models based on in-stream distance.
* [spmoran](https://cran.r-project.org/web/packages/spmoran/index.html) - Functions for estimating fixed and random effects eigenvector spatial filtering models.
* [SpatialEpi](https://cran.r-project.org/web/packages/SpatialEpi/index.html) - Methods and data for cluster detection and disease mapping.
* [OasisR](https://cran.r-project.org/web/packages/OasisR/index.html) - A set of indexes and tests for the analysis of social segregation.
* [smerc](https://cran.r-project.org/web/packages/smerc/index.html) - Provides statistical methods for the analysis of data areal data, with a focus on cluster detection.
* [gwrr](https://cran.r-project.org/web/packages/gwrr/index.html) - Fits geographically weighted regression (GWR) models and has tools to diagnose and remediate collinearity in the GWR models.
* [lctools](https://cran.r-project.org/web/packages/lctools/index.html) - Package provides researchers and educators with easy-to-learn user friendly tools for calculating key spatial statistics and to apply simple as well as advanced methods of spatial analysis in real data.
* [AMOEBA](https://cran.r-project.org/web/packages/AMOEBA/index.html) - A function to calculate spatial clusters using the Getis-Ord local statistic. It searches irregular clusters (ecotopes) on a map.
* [sparr](https://cran.r-project.org/web/packages/sparr/index.html) - Provides functions to estimate kernel-smoothed spatial and spatio-temporal densities and relative risk functions, and perform subsequent inference.
* [CARBayes](https://cran.r-project.org/web/packages/CARBayes/index.html) - Package implements Bayesian hierarchical spatial areal unit models.
* [glmmBUGS](https://cran.r-project.org/web/packages/glmmBUGS/index.html) - Automates running Generalized Linear Mixed Models, including spatial models, with WinBUGS, OpenBUGS and JAGS.
* [spaMM](https://cran.r-project.org/web/packages/spaMM/index.html) - Inference in mixed-effect models, including generalized linear mixed models with spatial correlations and models with non-Gaussian random effects.
* [PReMiuM](https://cran.r-project.org/web/packages/PReMiuM/index.html) - Dirichlet Process Bayesian Clustering, Profile Regression.
* [spacom](https://cran.r-project.org/web/packages/spacom/index.html) - Provides tools to construct and exploit spatially weighted context data.
* [geospacom](https://cran.r-project.org/web/packages/geospacom/index.html) - Generates distance matrices from shape files and represents spatially weighted multilevel analysis results.
* [spatsurv](https://cran.r-project.org/web/packages/spatsurv/index.html) - Bayesian inference for parametric proportional hazards spatial survival models; flexible spatial survival models.
* [spBayesSurv](https://cran.r-project.org/web/packages/spBayesSurv/index.html) - Bayesian Modeling and Analysis of Spatially Correlated Survival Data.
* [spselect](https://cran.r-project.org/web/packages/spselect/index.html) - Fits spatial scale (SS) forward stepwise regression, SS incremental forward stagewise regression, SS least angle regression (LARS), and SS lasso models.
* [nlme](https://cran.r-project.org/web/packages/nlme/index.html) - Fit and compare Gaussian linear and nonlinear mixed-effects models.
* [spatcounts](https://cran.r-project.org/web/packages/spatcounts/index.html) - Fit spatial CAR count regression models using MCMC.
* [McSpatial](https://cran.r-project.org/web/packages/McSpatial/index.html) - Provides functions for locally weighted regression, semiparametric and conditionally parametric regression, fourier and cubic spline functions, GMM and linearized spatial logit and probit, k-density functions and counterfactuals, nonparametric quantile regression and conditional density functions, Machado-Mata decomposition for quantile regressions, spatial AR model, repeat sales models, and conditionally parametric logit and probit.
* [splm](https://cran.r-project.org/web/packages/splm/index.html) - ML and GM estimation and diagnostic testing of econometric models for spatial panel data.
* [S2sls](https://cran.r-project.org/web/packages/S2sls/index.html) - Fit a spatial instrumental-variable regression by two-stage least squares.
* [spanel](https://cran.r-project.org/web/packages/spanel/index.html) - Fit the spatial panel data models: the fixed effects, random effects and between models.
* [HSAR](https://cran.r-project.org/web/packages/HSAR/index.html) - A library of the Hierarchical Spatial Autoregressive Model (HSAR), based on a Bayesian Markov Chain Monte Carlo (MCMC) algorithm.
* [spatialprobit](https://cran.r-project.org/web/packages/spatialprobit/index.html) - Bayesian Estimation of Spatial Probit and Tobit Models.
* [ProbitSpatial](https://cran.r-project.org/web/packages/ProbitSpatial/index.html) - Binomial Spatial Probit models for big data.
* [starma](https://cran.r-project.org/web/packages/starma/index.html) - Statistical functions to identify, estimate and diagnose a Space-Time AutoRegressive Moving Average (STARMA) model.
* [ade4](https://cran.r-project.org/web/packages/ade4/index.html) - Tools for multivariate data analysis. Several methods are provided for the analysis (i.e., ordination) of one-table (e.g., principal component analysis, correspondence analysis), two-table (e.g., coinertia analysis, redundancy analysis), three-table (e.g., RLQ analysis) and K-table (e.g., STATIS, multiple coinertia analysis).
* [adehabitat](https://cran.r-project.org/web/packages/adehabitat/index.html) - A collection of tools for the analysis of habitat selection by animals.
* [adehabitatHR](https://cran.r-project.org/web/packages/adehabitatHR/index.html) - A collection of tools for the estimation of animals home range.
* [adehabitatHS](https://cran.r-project.org/web/packages/adehabitatHS/index.html) - A collection of tools for the analysis of habitat selection.
* [adehabitatLT](https://cran.r-project.org/web/packages/adehabitatLT/index.html) - A collection of tools for the analysis of animal movements.
* [adehabitatMA](https://cran.r-project.org/web/packages/adehabitatMA/index.html) - A collection of tools to deal with raster maps.
* [pastecs](https://cran.r-project.org/web/packages/pastecs/index.html) - Regulation, decomposition and analysis of space-time series.
* [vegan](https://cran.r-project.org/web/packages/vegan/index.html) - Ordination methods, diversity analysis and other functions for community and vegetation ecologists.
* [tripEstimation](https://cran.r-project.org/web/packages/tripEstimation/index.html) - Data handling and estimation functions for animal movement estimation from archival or satellite tags.
* [spind](https://cran.r-project.org/web/packages/spind/index.html) - Functions for spatial methods based on generalized estimating equations (GEE) and wavelet-revised methods (WRM), functions for scaling by wavelet multiresolution regression (WMRR), conducting multi-model inference, and stepwise model selection.
* [rangeMapper](https://cran.r-project.org/web/packages/rangeMapper/index.html) - Tools for easy generation of (life-history) traits maps based on species range (extent-of-occurrence) maps.
* [siplab](https://cran.r-project.org/web/packages/siplab/index.html) - A platform for experimenting with spatially explicit individual-based vegetation models.
* [ModelMap](https://cran.r-project.org/web/packages/ModelMap/index.html) - Creates sophisticated models of training data and validates the models with an independent test set, cross validation, or in the case of Random Forest Models, with Out Of Bag (OOB) predictions on the training data. 
* [SpatialPosition](https://cran.r-project.org/web/packages/SpatialPosition/index.html) - Computes spatial position models: Stewart potentials, Reilly catchment areas, Huff catchment areas.
* [Watersheds](https://cran.r-project.org/web/packages/Watersheds/index.html) - Methods for watersheds aggregation and spatial drainage network analysis.
* [Rcitrus](http://www.leg.ufpr.br/Rcitrus/) - Spatial analysis of plant disease incidence.
* [ngspatial](https://cran.r-project.org/web/packages/ngspatial/index.html) - Provides tools for analyzing spatial data, especially non- Gaussian areal data.
* [bfastSpatial](https://github.com/loicdtx/bfastSpatial) - Package to pre-process gridded time-series data in order for them to be analyzed with change detection algorithms such as bfast. Uses classes from the raster package and includes utilities to run the algorithms and post-process the results.
* [teamlucc](https://github.com/azvoleff/teamlucc) -  Is designed to facilitate analysis of land use and cover change (LUCC) around the monitoring sites of the Tropical Ecology Assessment and Monitoring (TEAM) Network.
* [RStoolbox](https://cran.r-project.org/web/packages/RStoolbox/index.html) :star2: - Toolbox for remote sensing image processing and analysis such as calculating spectral indices, principal component transformation, unsupervised and supervised classification or fractional cover analyses.
* [sits](https://github.com/gilbertocamara/sits) - satellite image time series package for R.
* [dtwSat](https://github.com/vwmaus/dtwSat) - Time-Weighted Dynamic Time Warping for satellite image time series analysis.
* [googleway](https://github.com/SymbolixAU/googleway) - R Package for accessing and plotting Google Maps.
* [geojsonsf](https://github.com/SymbolixAU/geojsonsf) - Conversion between sf and geojson.
* [ncdfgeom](https://github.com/USGS-R/ncdfgeom) - NetCDF-CF Geometry and Timeseries Tools for R.
* [tidytransit](https://github.com/r-transit/tidytransit) - 'sf'-compatible package to analyze transit schedules, routes, and stops.
* [lucCalculus](https://github.com/e-sensing/lucCalculus) - Spatiotemporal calculus for land use change trajectories.
* [lidR](https://github.com/Jean-Romain/lidR) - R package for airborne LiDAR data manipulation and visualisation for forestry application.
* [uavRst](https://github.com/gisma/uavRst) - UAV related Remote Sensing Toolbox.
* [getSpatialData](https://github.com/16EAGLE/getSpatialData) - An R package making it easy to query, preview, download and preprocess multiple kinds of spatial data via R.
* [landscapemetrics](https://github.com/r-spatialecology/landscapemetrics) - landscapemetrics is an R package for calculating landscape metrics for categorical landscape patterns in a tidy workflow.
* [stars](https://github.com/r-spatial/stars) - Spatiotemporal tidy arrays for R.
* [vapour](https://github.com/hypertidy/vapour) - A lightweight GDAL API package for R.
* [ffraster](https://github.com/hypertidy/ffraster) - Treat ff arrays as raster objects, and vice versa.
* [tidync](https://github.com/hypertidy/tidync) - Systematic approaches to NetCDF data extraction, manipulation and visualization.
* [geodist](https://github.com/hypertidy/geodist) - Ultra lightweight, ultra fast calculation of geo distances.
* [GeospatialLineGraphs](https://github.com/Brideau/GeospatialLineGraphs) - A library for creating geospatial line graphs along lines of latitude.
* [phenofit](https://github.com/kongdd/phenofit) - A state-of-the-art Vegetation Phenology extraction package.
* [rayshader](https://github.com/tylermorganwall/rayshader) - rayshader is an open source R package for producing 2D and 3D hillshaded maps of elevation matrices using a combination of raytracing, spherical texture mapping, and ambient occlusion.
* [Prioritizr](https://github.com/prioritizr/prioritizr) - The prioritizr R package uses integer linear programming (ILP) techniques to provide a flexible interface for building and solving conservation planning problems.
* [ModelR](https://github.com/Model-R/modelr_pkg) - A workflow for ecological niche models based on dismo.
* [gdalcubes_R](https://github.com/appelmar/gdalcubes_R) - R package for gdalcubes to process collections of Earth observation image collection as on demand data cubes.
* [ggspatial](https://github.com/paleolimbot/ggspatial) - A ggplot2 R extension for plotting Spatial* objects.
* [exactextractr](https://github.com/isciences/exactextractr) - R package for fast and accurate raster zonal statistics.
* [kuenm](https://github.com/marlonecobos/kuenm) - kuenm is an R package designed to make the process of model calibration and final model creation easier and more reproducible, and at the same time more robust.
* [whiteboxR](https://github.com/giswqs/whiteboxR) - R frontend of [WhiteboxTools](https://github.com/jblindsay/whitebox-tools).
* [phenopix](https://cran.r-project.org/web/packages/phenopix/index.html) - A collection of functions to process digital images, depict greenness index trajectories and extract relevant phenological stages. 
* [rsMove](https://cran.r-project.org/web/packages/rsMove/index.html) - Tools that support the combined use of animal movement and remote sensing data.
* [rnaturalearth](https://github.com/ropensci/rnaturalearth) - An R package to hold and facilitate interaction with Natural Earth map data.
* [ranger](https://github.com/imbs-hl/ranger) - A Fast Implementation of Random Forests.
* [osmplotr](https://github.com/ropensci/osmplotr) - Data visualisation using OpenStreetMap objects.
* [osmdata](https://github.com/ropensci/osmdata) - R package for downloading OpenStreetMap data.
* [vapour](https://github.com/hypertidy/vapour) - A lightweight GDAL API package for R.
* [polyclip](https://github.com/baddstats/polyclip) - R package polyclip: a port of the Clipper library for polygon geometry.
* [cartography](https://github.com/riatelab/cartography) - Thematic Cartography with R.
* [ROSM](https://github.com/paleolimbot/rosm) - Plot Open Street Map and Other Tiles in R.
* [nngeo](https://github.com/michaeldorman/nngeo) - k-Nearest Neighbor Join for Spatial Data.
* [wordcloud2](https://github.com/Lchiffon/wordcloud2) - R interface to wordcloud for data visualization.
* [fasterize](https://github.com/ecohealthalliance/fasterize) - High performance raster conversion for modern spatial data.
* [earthEngineGrabR](https://github.com/JesJehle/earthEngineGrabR) - The earthEngineGrabR is an interface between R and the Google Earth Engine, which simplifies the acquisition of remote sensing data.
* [stlnpp](https://github.com/Moradii/stlnpp) - Spatio-temporal point patterns on linear networks.
* [geom](https://github.com/paleolimbot/geom) - Vectorized geometries and low-level GEOS access.
* [terra](https://github.com/rspatial/terra) - terra is an R package that replaces raster. It has a very similar, but simpler, interface, and it is much faster.
* [wt](https://github.com/paleolimbot/wk) - Lightweight Well-Known Geometry Parsing.


## Mobile Development

* [Mapbox Android SDK](https://www.mapbox.com/android-sdk/) - An open source toolset for building mapping applications for Android devices.
* [Mapbox iOS SDK](https://www.mapbox.com/ios-sdk/) - An open source toolset for building mapping applications for iPhone and iPad devices.
* [Google Maps API for Android](https://developers.google.com/maps/android/) - Google maps for Android.
* [Google Maps API for iOS](https://developers.google.com/maps/ios/) - Google maps for iOS.
* [Nutiteq Maps SDK](http://www.nutiteq.com/nutiteq-sdk/overview/) - C++ maps library for iOS, Android, Windows Phone and Xamarin with bindings for Java, ObjectiveC and C#.
* [WhirlyGlobe/Maply](http://mousebird.github.io/WhirlyGlobe/) - Objective C code that is able to read and render vector tiles(and style with mapnik xml) on iOS devices.
* [mapbox-navigation-android](https://github.com/mapbox/mapbox-navigation-android) - Mapbox Navigation SDK for Android.
* [Apple MapKit](https://developer.apple.com/documentation/mapkit) - Display map or satellite imagery directly from your app's interface, call out points of interest, and determine placemark information for map coordinates.
* [MAPS.ME](https://github.com/mapsme/omim) - MAPS.ME — Offline OpenStreetMap maps for iOS and Android.


## Geospatial Big Data

* [Google Earth Engine](https://earthengine.google.com/) :star2: - Is a cloud computing platform for processing satellite imagery and other Earth observation data.
* [GeoMesa](https://github.com/locationtech/geomesa) - GeoMesa is a suite of tools for working with big geo-spatial data in a distributed fashion.
* [GeoWave](https://github.com/locationtech/geowave) - GeoWave provides geospatial and temporal indexing on top of Accumulo and HBase.
* [GeoTrellis](https://github.com/locationtech/geotrellis) - GeoTrellis is a geographic data processing engine for high performance applications.


## Visualization 

* [Processing](https://processing.org/) - Processing is a flexible software sketchbook and a language for learning how to code within the context of the visual arts.
* [P5.js](https://p5js.org/) - Javascript library that starts with the original goal of Processing.
* [Processing.py](http://py.processing.org/) - Python mode for Processing.
* [D3.js](https://d3js.org/) - D3.js is a JavaScript library for manipulating documents based on data.
* [openFrameworks](http://openframeworks.cc/) - openFrameworks is an open source C++ toolkit for creative coding.
* [Folium](https://github.com/python-visualization/folium) - Python Data. Leaflet.js Maps.
* [Blender GIS](https://github.com/domlysz/BlenderGIS) - Blender addons to make the bridge between Blender and geographic data.
* [tippecanoe](https://github.com/mapbox/tippecanoe) - Build vector tilesets from large collections of GeoJSON features.
* [Kosmtik](https://github.com/kosmtik/kosmtik) - Very lite but extendable mapping framework to create Mapnik ready maps with OpenStreetMap data (and more).
* [mplleaflet](https://github.com/jwass/mplleaflet) - Easily convert matplotlib plots from Python into interactive Leaflet web maps.
* [three.js](https://threejs.org/) - A javascript 3D library which makes WebGL simpler
* [Strava](https://github.com/marcusvolz/strava) - Create artistic visualisations with your exercise data.
* [CityEngine-Twitter](https://github.com/urschrei/CityEngine-Twitter) - Visualise Twitter activity using a procedurally-generated 3D city model.
* [PostGIS Preview](https://github.com/NYCPlanning/labs-postgis-preview) - A lightweight node api and frontend for quickly previewing PostGIS queries. 
* [BlenderGIS](https://github.com/domlysz/BlenderGIS) - Blender addons to make the bridge between Blender and geographic data.
* [circlize](https://github.com/jokergoo/circlize) - Circular visualization in R. Circular layout is an efficient way for the visualization of huge amounts of information. 
* [Skia](https://skia.org/) - Skia is a complete 2D graphic library for drawing Text, Geometries, and Images.
* [geoplot](https://github.com/ResidentMario/geoplot) -  High-level Python geospatial plotting library. It's an extension to cartopy and matplotlib which makes mapping easy.
* [GeoJs](https://github.com/OpenGeoscience/geojs) - High-performance visualization and interactive data exploration of scientific and geospatial location aware datasets.
* [Cinder](https://libcinder.org/) - Cinder is a free and open source library for professional-quality creative coding in C++.
* [Peak map](https://github.com/anvaka/peak-map) - Allows you to visualize elevation of any area on the map with filled area charts.


## Tools

* [Projection  Wizard](http://projectionwizard.org/) - Helps you select an appropriate projection for your map, depending on the area that you are mapping.
* [GeoGig](http://geogig.org/) - GeoGig is a Distributed Version Control System (DVCS) specially designed to handle geospatial data efficiently
* [MapShaper](http://mapshaper.org/) - Tools for editing Shapefile, GeoJSON, TopoJSON and CSV files.
* [landsat-espa-util](https://github.com/loicdtx/landsat-espa-util) - Library for querying and ordering Landsat Surface Reflectance data via ESPA.
* [TileMill](https://github.com/mapbox/tilemill) - TileMill is a modern map design studio powered by Node.js and Mapnik.
* [DataPillager](https://github.com/gdherbert/DataPillager) - Download data from Esri service.
* [Osm2pgsql](https://github.com/openstreetmap/osm2pgsql) - osm2pgsql is a tool for loading OpenStreetMap data into a PostgreSQL.
* [52North SOS](http://52north.org/communities/sensorweb/sos/) - A reference implementation of the [OGC Sensor Observation Service specification (version 2.0)]
* [Maptiks](https://maptiks.com/) - Maptiks its a tool that provides in-depth user insights by tracking how visitors click, pan and zoom on your maps.
* [Generic Mapping Tools](https://github.com/GenericMappingTools/gmt) - GMT is an open source collection of about 90 command-line tools for manipulating geographic and Cartesian data sets.
* [CODA](http://stcorp.github.io/coda/doc/html/index.html) - The Common Data Access toolbox (CODA) provides a set of tools for ingesting, processing, and analyzing remote sensing data.


## Cheat sheets

* [Fiona-Rasterio-Shapely Cheat Sheet](https://github.com/sgillies/frs-cheat-sheet) - A cheat sheet for Fiona/Rasterio/Shapely command-line geodata tools.
* [GDAL](https://github.com/dwtkns/gdal-cheat-sheet) - Cheat sheet for GDAL/OGR command-line tools.
* [PostGIS](http://www.postgis.us/downloads/postgis21_cheatsheet.pdf) - Cheat sheet for PostGIS.
* [PostGIS 2](https://gist.github.com/kidpixo/5698476) 
* [PostGIS Raster](http://www.postgis.us/downloads/postgis20_raster_cheatsheet.pdf) 


## Data Sources

* [TZ Timezone Shapefiles](http://efele.net/maps/tz/world/) - Polygon boundaries of world timezones.
* [USGS Earth Explorer](http://earthexplorer.usgs.gov/) - Provides online search,metadata export, and data download for earth science data from the archives of the USGS.
* [GeoNames](http://www.geonames.org/) - The GeoNames geographical database covers all countries and contains over eight million place names (cities, postal codes, countries) that are available for download free of charge.
* [Mapzen](https://mapzen.com/metro-extracts) - It provides data in OSM/PBF and Esri shapefile formats for popular cities.
* [Geofabrik](http://download.geofabrik.de/) - This is another source of prepared OpenStreetMap data. This distribution is generally built nightly and comes in OSM XML, pbf, and shapefile (for very popular areas) formats.
* [Natural Earth](http://www.naturalearthdata.com/) - This site offers public domain map data sets that contain both raster and vector data.
* [ASTER Data](https://lpdaac.usgs.gov/dataset_discovery/aster) - Download ASTER data.
* [INPE Database](http://www.dgi.inpe.br/CDSR/) - Download free satellite data including MODIS, Landsat (1-7), ResourceSat (1-2) and CBERS (2, 2B and 4) data.
* [CBERS on AWS](https://github.com/fredliporace/cbers-on-aws) - Information, tools and data related to the China-Brazil Earth Resources Satellite (CBERS) PDS on AWS.
* [Sentinel 2 AWS](http://sentinel-pds.s3-website.eu-central-1.amazonaws.com/) - Sentinel 2 data on Amazon S3.
* [Copernicus Open Access Hub](https://scihub.copernicus.eu/dhus/#/home) - Sentinel data from scihub.
* [Cityscapes Dataset](https://www.cityscapes-dataset.com/) -  large-scale dataset that contains a diverse set of stereo video sequences recorded in street scenes from 50 different cities, with high quality pixel-level annotations of 5 000 frames in addition to a larger set of 20 000 weakly annotated frames.
* [Scale Open Datasets](https://scale.com/open-datasets?utm_campaign=Spatial%20Awareness&utm_medium=email&utm_source=Revue%20newsletter) - Open Datasets for Autonomous Driving.


## Resources

* [IndexDatabase](http://www.indexdatabase.de/) - A database for remote sensing indices.
* [Cartographical Map Projections](http://www.progonos.com/furuti/MapProj/Normal/TOC/cartTOC.html) - A good introduction to projected coordinate systems
* [Spatialreference.org](http://spatialreference.org/) - Source for coordinate system information.
* [ESRI Shapefile Specs](http://www.esri.com/library/whitepapers/pdfs/shapefile.pdf) - Shapefile specifications.
* [GeoJSON.io](http://geojson.io/) - geojson.io is a quick, simple tool for creating, viewing, and sharing maps.
* [TileJSON.io](http://tilejson.io/) - tilejson.io is a simple viewer for raster tile sets (Enter tile URL, layer properties, share).
* [GDAL/OGR Cookbook](https://pcjericks.github.io/py-gdalogr-cookbook/) - Simple code snippets on how to use the Python GDAL/OGR API.
* [Geopython](https://github.com/urschrei/Geopython) - Notebooks and libraries for spatial/geo Python explorations.



## Conferences

* [FOSS4G](http://foss4g.org/) - Free and Open Source Software for Geospatial.
* [State of the Map](https://stateofthemap.org/) - is the annual event for all mappers and OpenStreetMap users.
* [GEOINFO](http://www.geoinfo.info/geoinfo2017/) - The GEOINFO series (Brazilian Symposium on Geoinformatics) is an annual conference for exploring ongoing research, development and innovative applications on geographic information science and related areas.
* [SBSR](http://sbsr.com.br/br/node/1379) - Bi-annual Brazilian National Symposium on Remote Sensing.


## Podcasts

* [Scene From Above](http://scenefromabove.org/index.html) - Earth observation, remote sensing, geospatial and geeky chat


## References and other awesome lists

* [Essential Python Geospatial Libraries](http://carsonfarmer.com/2013/07/essential-python-geo-libraries/) 
* [GeoJSON](https://github.com/tmcw/awesome-geojson)
* [Vector Tiles](https://github.com/mapbox/awesome-vector-tiles)
* [Spatial R](https://cran.r-project.org/web/views/Spatial.html)
* [Awesome Spatial](https://github.com/RoboDonut/awesome-spatial/blob/master/README.md)
* [Awesome GIS - sshuair](https://github.com/sshuair/awesome-gis)
* [Awesome SQLite](https://github.com/planetopendata/awesome-sqlite) 
* [Awesome Python](https://github.com/vinta/awesome-python/blob/master/README.md)
* [Awesome Satellite Imagery Datasets](https://github.com/chrieke/awesome-satellite-imagery-datasets)
* [Awesome Sentinel](https://github.com/Fernerkundung/awesome-sentinel)
* [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision)
* [Awesome Deep Vision](https://github.com/kjw0612/awesome-deep-vision)
* [Awesome Semantic Segmentation](https://github.com/mrgloom/awesome-semantic-segmentation)
* [Awesome Object Detection](https://github.com/amusi/awesome-object-detection)
* [Awesome SAR](https://github.com/RadarCODE/awesome-sar)
* [GeoRails](http://daniel-azuma.com/articles/georails/)
* [Cartography / mapping / web design resources](https://github.com/tolomaps/resources)
