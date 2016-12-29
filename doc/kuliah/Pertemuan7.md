Background

MapServer is a freeware and open source application which allows kita displaying spatial data (maps) on the web. Applications Singer First developed at the University of Minesotta, Murai Law to review the project Fornet (A project to review the management of Natural Resources) which is sponsored NASA (National Aeronautics and Space Administration). Supports NASA developed project followed WITH TerraSIP to review data management Land. When Singer, BECAUSE nature Yang Open (open source), MapServer development is done by developers from different gatra.

Discussion

What Is a Map Server?
MapServer Program Form A CGI (Common Gateway Interface). The program will be executed on the web server, and based on some parameters Specific (especially the hearts Configuration File Form * MAP) will generate data that the which are to be Sent to a web browser, both hearts Shape image map or other form.

MapServer has fitur¬fitur following:
Data Format displays spatial vector hearts Such as: Shapefile (ESRI), ArcSDE (ESRI), PostGIS and different vector data formats using OGR library lay WITH
Data displays hearts spatial raster formats like: TIFF / GeoTIFF, EPPL7 And different raster data formats using GDAL library lay WITH
Quadtree indexing of data using spatial hearts, so that can be done operasi¬operasi spatial Quick WITH
can be developed (adjusted), WITH Exodus That can be arranged using file¬file Template
Screening can be the object based on the value, based on the point, area, OR-based A Certain spatial objects
Form letters supports TrueType rendering Characters
USE supports raster and vector The di¬tiled (dibagi¬bagi sub Being smaller parts so the process for the review take and display images can be accelerated)
PETA describes the elements can be Operates automatically: Your scale Graphics, indexes and legends PETA PETA
hearts using your scale depiction of spatial objects
describe the thematic map can be constructed using Expression The logical mapun regular expression
From the label can be displays of spatial objects, WITH label can be set such that NO overlap
Configuration can be set Operating on the fly through The URL parameter specified ON
can be handle Various projection system operates quickly
When singer, in addition can be access MapServer as a CGI program, kita can be access MapServer as Mapscript module, through different scripting languages: PHP, Perl, Python OR Java. Diplomacy access fungsi¬fungsi MORE MapServer through scripts will facilitate application development. Developers can choose the language What blanch be familiar.



How MapServer WORK?
Map Server WORKING WITH Application Operating alongside web server. Web Server RECEIVE MAP requests through MapServer. MapServer generates requests and send Ke Against PETA web servers such as ON the following picture.

Main Function Of MapServer is doing the reading data from Many Sources and put into layers simultaneously Operating Being a graphic file. One form of the layer can Saja satellite image. EACH WITH A layer overlay each other and displayed into the web browser.

Main Components
MapServer generates graphical output Form filed based on the input that was provided by the user. The key component is MapServer executable CGI Consisting Of course, PETA Files, Source Data and image output. As shown below ALL THE WORK Components Together, the taxable income users make requests / perminataan Then CGI will access the map files, depict information Yang obtained from the Data Sources And Back display ON THE MAP.

MapServer executable
Operates is simple MapServer running executable CGI ON Applicability Operative Technical web server is a process-based AT HTTP stateless. Stateless Was A Country That process continued WITH request to stop running. CGI application RECEIVE request of the State From the web server, then the process is done and returns the response OR web Data Into Server. Very simple CGI WORK NOT AN programming required for the review can be used. We Stayed perform basic editing text based, runtime configuration file, MAKE web page, and placing WORK ON web server. MapServer CGI executable as Broker BETWEEN WORK WITH MAP Program Files The web server asks PETA. Demand in the hearts miss Forms CGI parameters on Towards MapServer web server. The image created by MapServer then feed back into the Web Server And then towards the user through a web browser.
MapServer Map File.
