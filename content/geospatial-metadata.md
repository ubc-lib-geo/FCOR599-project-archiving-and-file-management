---
layout: default
title: Geospatial Metadata
nav_order: 3
---

# Geospatial Metadata

Metadata is information that describes information (or anything really – think about product labels). It's super important to understand the value of metadata and how it can continually benefit you, your data, and the users of your data. Metadata describes your data so it can be used, shared, and understood widely.

**Your README file is an important part of your dataset's metadata**

The U.S. Geological Survey has prepared a handy document which prompts you to think about what is important to include your data's metadata. You should be prepared to answer these questions from [USGS Metadata in Plain Language](https://geology.usgs.gov/tools/metadata/tools/doc/ctc/)

# Examples of Geospatial Metadata

Here are two examples of metadata records for geodata. The first link goes to a web page with metadata elements formatted for discovery. Metadata elements are there (title, contact info, description, purpose, etc.), but they've been styled for human readability in the form of this web page. The second link is plain XML – meant for programmatic discovery and transformation into new formats.

1. [metadata formatted for web discovery](https://catalogue.data.gov.bc.ca/dataset/fire-incident-locations-historical)
2. [xml-encoded metadata](https://raw.githubusercontent.com/OpenGeoMetadata/edu.stanford.purl/master/sv/613/mt/4586/iso19139.xml)

# The Difficulties with Metadata

Frankly, metadata is pretty boring, and there are lots of more exciting things you'd probably rather do with your data than document and describe it. It can take a lot of time to create, and it might often seem like there is no clear choice for the best standard or format to use.

### ...BUT

If you don't create quality metadata, it could have significant negative effects on your data and your credibility.

Bad metadata negatively affects:

- integrity
- discoverability
- preservability
- useablity

# Metadata Types

You can think about metadata in these 4 categories: descriptive, technical, discovery, and administrative.

## Descriptive Metadata

Descriptive metadata is pretty self explanatory. This gives you and others all the necessary information describing your data or study, including how it was derived and uncertainty errors. It will include things like:

- Abstract/methodology
- Attribute descriptions
- Purpose
- Uncertainty errors
- Access

## Technical Metadata

Technical metadata is highly subject-specific. Different industries may have different technical metadata requirements. It will include things like:

- CRS / projection / datum information
- Attribute data types
- Software used
- Character encoding

## Discovery Metadata

Discovery metadata is used to index and link your data with others. When you search and filter data by subject, you're using discovery metadata. It will include things like:

- title
- date
- keywords
- geographic extent

## Administrative Metadata

Administrative metadata provides information about ownership, update frequencies, and terms of use. It will include things like:

- Copyright statements or licenses
- Contact information
- Status

# Metadata Standards

You all probably understand the general need for standards, and those same things can apply to metadata. Yes, there are a lot of metadata standards, and that's ok. They have a tendency to be thought of as very rigid and rules-based, but they can also be flexible. Why do we have them? They can be essential to ease transformation/conversion processes that might happen to your metadata, and they ensure your metadata is properly interpreted.

In GIS there are two widely used standards that have rules for what should be included in metadata records, how it is described, and how it's structured/encoded. : **FGDC** and **ISO 19115/19139**.

# ISO Metadata

ISO has recently emerged as the recommended choice between the two due to its flexibility, comprehensiveness, and wide recognition. Complete documentation for ISO standards cost money, but there are tools you can use to automatically encode your metadata to ISO standards.

# Metadata Tools and Editors

The most common way to create and edit geographic metadata is by using a Desktop GIS software like ArcGIS Pro. But there are also many other tools you can use if you 're not using a GIS. For example:

- [ArcGIS Pro!](https://pro.arcgis.com/en/pro-app/latest/help/metadata/best-practices-for-editing-metadata.htm)
- [catMDEdit](https://catmdedit.sourceforge.io/)
- [mdEditor.org](https://www.mdeditor.org/)
- [GeoNetwork](https://geonetwork-opensource.org/)
- [and more!!](https://wiki.osgeo.org/wiki/Metadata_software)

Creating metadata can be tedious. But remember: metadata will make your data more reproducible, sharable, and impactful.
