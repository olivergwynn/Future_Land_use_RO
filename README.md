# Future Land Use RO-Crate 
## Version

Current version: 2024-06-14

## Provider

  - Organization: [Mid-Ohio Regional Planning Commission](https://morpc.org)
  - Contact: 
    - Name: Oliver Gwynn
	- E-mail: ogwynn@morpc.org

## Disclaimer

This data kit is a work in progress.

## Introduction

This notebook demonstrates the process of preparing a Research Object Crate (RO-Crate) for the Future Land Use dataset. The dataset contains spatial and attribute information, which will be split into two separate files: a Shapefile containing just the geographies and a unique identifier, and a CSV file containing the unique identifier and the remaining fields. The CSV file will be structured according to a Frictionless table schema to ensure consistency and quality. Additionally, the notebook will export the resulting data as a GeoPackage for further use.

## Outputs
This outputs a RO-Crate containing land use codes, a zipped shapefile, and land use attribute csv.

Each output is accompanied by a [Frictionless Resource file](https://specs.frictionlessdata.io/data-resource/), which provides a high-level description of the data and a link to the associated table schema.  The Resource file also provides the [MD5 checksum](https://en.wikipedia.org/wiki/Md5sum) ("hash") and the file size ("bytes") of the data file to allow for integrity checking.

The table schema is described by a [Frictionless Schema file](https://specs.frictionlessdata.io/table-schema/), which describes each of the fields contained in the table, including its name and type, and sometimes provides additional metadata about the table.

This proccess also crates a GeoPackage

## Processes

The outputs are produced by a process which complies and transforms the data:

  1. A fully-automated process implemented as a Jupyter notebook


## Inputs

The process requires a zipped Land Use shapefile and CSV file

  1. Files can come from [MORPC](https://public-morpc.hub.arcgis.com/datasets/22ac0071b4234a41a0414e0c9121e23f_20/about) and placed in input data directory (`./assets/input_data/`)


## Revision history

### 2024-06-14 Oliver Gwynn <ogwynn@morpc.org>

Initial WIP version. 
