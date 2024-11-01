# DAA\_Generator

A simple Excel file that enables the automatic creation of customs DAA documents based on the XML file downloaded from the customs website.

## Features

- UserForm for selecting malts or beers
- Save button to duplicate the sheet with values only (values are pasted as values, and interactive buttons are removed)
- List of the most frequent addresses for sending beers
- Import of inbound DAA with Anker Malts (automatic recognition of the reference if present in the malt database. This occasionally needs to be updated by adding new references from the latest price lists)
- Import of inbound DAA with various malts (cells marked with `@@` need to be filled in manually)
- Import of outbound DAA with various malts (cells marked with `@@` need to be filled in manually)
- Import of inbound/outbound DAA with beers
  - If the import generates an error in some cell, it means the beer is not recognized. It should be added to the beer database, specifying the number of units per case and the capacity of each unit.

## Bugs to Fix

1. Add the case where the shipment involves wines.



