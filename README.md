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

## About HMDB: 

HMDB is offered to the public as a freely available resource. Use and re-distribution of the data, in whole or in part, for commercial purposes requires explicit permission of the authors and explicit acknowledgment of the source material (HMDB) and the original publication (see below). We ask that users who download significant portions of the database cite the HMDB paper in any resulting publications.

    Wishart DS, Tzur D, Knox C, et al., HMDB: the Human Metabolome Database. Nucleic Acids Res. 2007 Jan;35(Database issue):D521-6. 17202168

    Wishart DS, Knox C, Guo AC, et al., HMDB: a knowledgebase for the human metabolome. Nucleic Acids Res. 2009 37(Database issue):D603-610. 18953024

    Wishart DS, Jewison T, Guo AC, Wilson M, Knox C, et al., HMDB 3.0 — The Human Metabolome Database in 2013. Nucleic Acids Res. 2013. Jan 1;41(D1):D801-7. 23161693

    Wishart DS, Feunang YD, Marcu A, Guo AC, Liang K, et al., HMDB 4.0 — The Human Metabolome Database for 2018. Nucleic Acids Res. 2018. Jan 4;46(D1):D608-17. 29140435 