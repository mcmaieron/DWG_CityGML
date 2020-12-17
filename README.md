# Digital 3D Model of Porto Alegre
## General Information
This project comes from the case study present in my master's thesis. In this project a partial semantic 3D city model of Porto Alegre - Brazil has been created based on datasets provided by the [Municipality of Porto Alegre (PMPA)](http://www2.portoalegre.rs.gov.br/spm/default.php?p_secao=310). Different 3D feature types were derived from existing public 2D and 3D datasets using spatial and semantic transformations. The resulting 3D city model is represented in a homogenized and integrated way using the international standard [CityGML](https://www.citygml.org/) of the [Open Geospatial Consortium (OGC)](http://www.opengeospatial.org/). This project also presents an approach for integrating open data, performing the semantic “enrichment” of the instances associating official data with Volunteered Geographic Information (VGI) data from [OpenStreetMaps (OSM)](https://www.openstreetmap.org/).

All data transformations and manipulations were performed using the ‘[Feature Manipulation Engine’ by Safe Software](https://www.safe.com/). The FME Workspaces created in order to generate this semantic 3D city model are made available in this repository. For some digitization steps that
were performed manually, the open-source [QGIS](https://qgis.org/en/site/) was used.

## Content
* **FME Workspaces**
  
  This folder contains all FME Workspaces created in the process of generating the semantic 3D city model of Porto Alegre. The workspaces were commented on, explaining the steps taken to achieve the necessary data integration. Bookmarks were used to organize the implementation according to the implemented CityGML modules.

 
## Software
**Feature Manipulation Engine (FME)**

The Software ‘Feature Manipulation Engine’ (FME) was developed by the canadian company Safe Software. Data from different sources and in different formats can be imported into FME using so called ‘Readers’. This data then can be manipulated using ‘Transformers’. After the manipulation is complete, the newly generated data can be exported into the desired output format using so called ‘Writers’.


## Disclaimer

These FME Workspaces are free to use. No warranties or guarantee on the correctness, completeness, or appropriateness for any specific use is given. In no case I can be held liable for damages, caused directly or indirectly, by using or working with these Workspaces or software tools. 
