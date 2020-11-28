# india-local-government-directory

Data dump of entities from the India Local Government Directory. These include the official listing of administrative units with unique identifier codes.

## Contents

**Reference Lookups**
- City/town directory with mapping to other levels `Urban local bodies with coverage`
- Village directory with mapping to other levels `Subdistrict, Village, Block and GPS mapping`

**Administrative**

1. States `All States of India`
2. Districts `All Districts of India`
3. Subdistricts (tehsil, taluka, mandal, circle) `All Sub-Districts of India`
4. Villages `All Villages of India`

**Political**

1-2. Parliament and assembly constituencies `State Wise Parliament Constituency and Assembly Constituency`
 - Per state (incomplete)

3. Local bodies:  
  - Rural local bodies (district/intermediate/village panchayat) `All PRI Local Bodies of India`
  - Traditional local bodies (village council/authority/development council/development commitee/employment council/development board, area employment council) `All Traditional Local Bodies of India`
  - Urban local bodies (municpal corporation, municipality, municipal council, town panchayat) `All Urban Local Bodies of India`
4. Urban and rural wards
  - Urban wards per state (incomplete) `Wards of Urban local bodies`
  - Rural wards per state (incomplete) `Wards of Rural local bodies`

**Statistical**

- Blocks `All Blocks of India`

## Metadata

**Source**

India Local Government Directory https://lgdirectory.gov.in/downloadDirectory.do

**Date of retrieval**

28 November 2020

**License**

[Government Open Data License – India](https://data.gov.in/sites/default/files/Gazette_Notification_OGDL.pdf)

## Reference

- https://en.wikipedia.org/wiki/Administrative_divisions_of_India
- https://wiki.openstreetmap.org/wiki/India/Boundaries
- https://www.geonames.org/countries/IN/india.html

## Updates

Contribute updates or missing files:

- Download the relevant file from https://lgdirectory.gov.in/downloadDirectory.do as a CSV
- Clone repo and organise file in relevant section
- Validate CSV to make it searchable in Github 
  - Set commas as delimiter. Replace ','->' ' and ';'->','
- Submit PR


