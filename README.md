# US coastal infrastructure dataset

A harmonised attribute table over two coastal geometries for the United States:
about 51,000 shoreline segments of roughly 1 km and about 16,000 coastal
facilities, sharing one schema. Observations only, no scores or rankings.

This repository is being assembled ahead of the data paper. It currently holds
the **Coastal Infrastructure Explorer**, a phone-first map of a subset of the
dataset, served from the `gh-pages` branch:

https://connorjmack.github.io/coastal-infrastructure-us/

The explorer shows three views: shoreline attributes coloured along the coast,
coastal facilities within 5 km of the shore, and the number of federal
regulatory layers covering each segment. It loads static files only. There are
no forms, cookies, analytics or server code.

## Data sources

Every layer on the explorer comes from an open-access source. Facility and
regulatory layers are US federal products (17 U.S.C. 105) except the marine
energy sites, which come from the PRIMRE/OpenEI wiki (CC BY-SA 4.0), and the
desalination inventory, which is an academic dataset with no stated licence.
The basemap is Esri World Ocean Base, used under Esri's terms of use.

The full data dictionary, source table and licence audit will be published here
with the dataset deposit.

## Roadmap

- Processing and export code for the dataset deposit
- Data dictionary and per-column source attribution
- Deposit DOI and citation
