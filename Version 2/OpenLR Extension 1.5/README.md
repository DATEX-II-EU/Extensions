# OpenLR Extension 1.5

Status definition refers to ISO 14817
Card

Implemented Node

Extension object
Point, Line, Area

Extension information
This is an updated version of the previous 1.3 version. This version mainly upgrades to version 2.2 of DATEX II and should be compliant with OpenLR version 1.5 and forward, now also supporting Areas!

This is an draft level B extension for OpenLR.

OpenLR is an open, compact and royalty-free dynamic location referencing method which enables reliable data exchange and cross-referencing using digital maps of different vendors and versions. OpenLR helps to enhance existing applications and generates opportunities for new services. It facilitates new business opportunities in various areas of Intelligent Transport Systems (ITS) such as traffic information services, map content exchange and Cooperative Systems where precise and compact dynamic location information is needed.

Dynamic location referencing is a requirement for many ITS and LBS (location based systems) systems and services. The use of various location reference methods will limit the interoperability of systems. A universal standard across a variety of applications will enable system integration and open the market for LBS.

DATEX II was designed for being able to be extended with user specific needs, national requirements and upcoming new specifications and standards. Swedish Transport Administration and the Dutch National Datawarehouse for Traffic information have jointly and together with TomTom developed an extension for OpenLR in DATEX II.

OpenLR has been designed for the use case of transferring traffic information from a centre to in-vehicle systems, built-in or used as an add-on (PND, Smart Phone). The information transferred can consist of the current traffic situation at a certain location, a traffic forecast or special alerts. The corresponding locations are roads or a list of connected roads. Additionally OpenLR supports point locations which are zero-dimensional elements in a map that specify a geometric location. Use cases for point locations are e.g. point of interests (POIs), petrol stations and speed cameras.

Compared to the existing RDS-TMC method every location in a map can be transferred using OpenLR. Besides the XML format a binary format for compact and bandwidth efficient transmission is supported. The goal of OpenLR is the wide-scale adoption by the industry at large. OpenLR is therefore proposed as an open standard in an Open Source framework.

The OpenLR extension for DATEX II makes it possible to use DATEX II with an extended location referencing model containing OpenLR. This makes it possible e.g. to deliver on the fly referencing in OpenLR format from the source of the information e.g. a Traffic Information Centre.

The full EA Model file and XML Schema which incorporate OpenLR into the Level A model are downloadable below. Also the separate xmi export file just containing the Extension package is made available for download.

More information about OpenLR can be found at www.openlr.org

Organization name
Swedish Transport Administration, TomTom International B.V. Dutch National DataWarehouse for Traffic Information (NDW(

Contact name
Jonas Jäderberg, Sven Baselau, Bard de Vries

Organization description
The Swedish Transport Administration is responsible for long-term planning of the transport system for road, rail, maritime and air traffic in Sweden.
TomTom is a digital mapping and routing company that focuses on car navigation.
The Dutch National dataWarehouse for Traffic information is the central point for distribution Traffic and Travelinformation from joint road operators in The Netherlands

Contact mail
jonas.jaderberg@viati.se, Sven.Baselau@tomtom.com, bard.de.vries@rws.nl

Website
www.trafikverket.se www.tomtom.com www.ndw.nu

Country/Region
Sweden, Netherlands

Centre type
TMC
