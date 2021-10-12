HMDB_Converting

## Purpose: 
To convert HMDB xml files to mgf. Each record is parsed against the structures .sdf file to create a psuedo mgf. 

## Warning
The mgfs produced DO NOT contain the precursor m/z values and the charge states are assumed based on ionization. PEPMASS values are calculated by adding the 1H mass to the listed molecular mass from .sdf file. 

## Requires: 
You MUST download the structures.sdf file from HMDB found here: https://hmdb.ca/system/downloads/current/structures.zip
You MUST download the hmdb_experimental_msms_spectra.zip (for xml format) found here: http://specdb.wishartlab.com/downloads/exports/spectra_xml/hmdb_experimental_msms_spectra.zip

You MUST place these items in the Input_Files directory. 

Package requirements found in requirements file. 
