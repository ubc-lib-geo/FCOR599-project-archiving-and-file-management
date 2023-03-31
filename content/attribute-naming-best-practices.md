---
layout: default
title: Attribute Naming Best Practices
parent: Geospatial Data Management
nav_order: 2
---

# Attribute Naming

When working with vector data you may encounter additional difficulties with naming attribute field names, especially if they're the product of a calculation using other field names. So it's good to abide by some important rules. If you need to start a codebook to define condensed attribute names, use any software or tool you're comfortable using to create it, like Google Docs, but you should save it as a file in a plain text format like .txt or .md. Just as with file naming conventions, attribute naming best practices include being **consistent** and keeping file names **short** and **descriptive**.

## Character Length

Be aware of character limits – Shapefile limit is 10. Other filetypes different have different specs, but a Shapefile's 10 character limit is notoriously small.

Do
{: .label .label-green }
POPDEN_20

Dont
{: .label .label-red }
population_density_2020

## Delimiters

Don't waste characters on `_` if you don't need to. Use camelCase when necessary to divide field elements.

Do
{: .label .label-green }
fieldName

Dont
{: .label .label-red }
thisismyfieldname

## Codebooks

Codebooks list your field names and labels and include descriptions of your data and attributes. For an example see the "Data Dictionary" for the [BC Digital Roads Atlas](https://catalogue.data.gov.bc.ca/dataset/digital-road-atlas-dra-demographic-partially-attributed-roads).

If you begin creating a codebook for your data, be sure to keep it up to date.
