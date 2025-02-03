#  Analyse non-CO2 impacts in the AR6 database

This code analyses emissions trends in scenarios in the AR6 database which meet certain temperature trends. 

In order to run this, you will need to import AR6 emissions data in both harmonised (infiller) and unharmonised formats, along with the metadata for it, available from:
https://data.ene.iiasa.ac.at/ar6/


Historical data, available from either RCMIP:
https://zenodo.org/records/4589756
or PRIMAP:
https://zenodo.org/records/5494497

And EDGAR data, available from:
https://edgar.jrc.ec.europa.eu/emissions_data_and_maps

These databases need to be put in the input folder, "./input". You can then run the main script, which produces the required results in the output folder.
