# MSPP

## 1.0.9
- Contained cleavage including checkbox for calculating the ratio
- Changed the nomenclature of items
- Added "Ctrl-F" function
- Refined the chart and added SVG/PNG export functions

## 1.0.8
- Added the feature save/load experiments containing manual curated ratio
- Peptide ratio visualization is provided for the experiments

## 1.0.7
- Added Chimera parameter calculation logic instead of using chimera parameters

## 1.0.6
- Fixed not finding miss cleavages with other charges
- Removed old logic of peptide selection
- Able to handle data with no Fraction column

## 1.0.5
- Fixed the bug of keeping inappropriate charges
- Stored chimera paramters and protein lists in the session
- Fixed the summary export header

## 1.0.4
- Replaced the missed cleaved peptide scan number with the actual sequence
- Optimized the query speed

## 1.0.3
- Fixed the missed cleavages selection
- Merged the missed cleaved peptide into the main peptide
- Revised the interfaces in the result page

## 1.0.2
- Fixed the missed cleaved peptide included without matching the charge state
- Fixed the logic of checking the peptide ratio tolerance which should be difference between the respective mod and non mod items
- Added the check box to take decisions muanually if discrepancies in peptide ratio happens
- Added the charge state in the peptide detail box
- Implemented the export data with peptide ratio

## 1.0.1
- Added peptide tolerance option for filtering less important data
- Included missed cleavage sequences for the quantification
- Description field has ```Retention time```, ```m/z value```, ```peptide squence```

## 1.0.0
- electron-updater works in MacOSX and Windows
