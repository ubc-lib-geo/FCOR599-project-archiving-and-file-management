---
layout: default
title: File Naming Best Practices
parent: Geospatial Data Management
nav_order: 1
---

# File Naming

Naming files doesn't seem super important, but it's one of the better investments you can make in good data management habits. Best practices include being **consistent** and keeping file names **short** and **descriptive**.

## Dates

If you use dates in your filenames, use the YYYYMMDD format. Dates formatted this way can be chronologically sortable and searched (within "homework" or other section of your files).

Do
{: .label .label-green }
homework_20200319.txt

Dont
{: .label .label-red }
homework_19032020.txt

## Identifiers

Identifiers are handy when you need to apply unique labels or abbreviations to organize your files. This also helps to keep similar files together and make them easy to "browse". Use unique abbreviations for project names or grants, separated by a `_` .

Do
{: .label .label-green }
fhabc_notes.txt

Dont
{: .label .label-red }
forest_history_association_of_BC_notes.txt

## Descriptors

Descriptors are often necessary in addition to an identifier, and should be just enough to describe the content. Keep them minimal and try to keep them unique.

Do
{: .label .label-green }
fhabc_grantProposal.pdf

Dont
{: .label .label-red }
fhabc.pdf

## Delimiters

Separating filename elements with delimiters allow for more flexibility to describe and organize your files. However, many special characters can confuse software or operating systems. For example databases will typically only accept file and attribute names with `_` delimiters.

Do
{: .label .label-green }
fhabc_grantProposal_v01.pdf

Dont
{: .label .label-red }
fhabc, grant proposal -->[v01].pdf

## Versions

If you are updating the same file with versions, then make sure you're consistent with how versions are differentiated. Note versions sequentially or with unique date and time.

Do
{: .label .label-green }
NRC_userGuidelines_v04.doc

Do
{: .label .label-green }
MSL-fraserRiverSamples-20200319-0900.csv

Dont
{: .label .label-red }
userGuidelines_final_edits_2_forreal.doc

## Other Important Things

- Be aware of character limits
- Don't start filenames with a number or underscore
- Don't use spaces as delimiters

UBC Library has a very good [guide on file naming best practices](https://researchdata.library.ubc.ca/plan/organize-your-data/). The Library is also a place to start with questions regarding data management best practices.
