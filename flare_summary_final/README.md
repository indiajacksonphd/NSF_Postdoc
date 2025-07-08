# Flare Summary Final

This directory contains the complete curated list of solar flares used in the NOAA-to-HEK matching and subsequent data extraction workflow. These files were produced during the flare validation phase of the project and support both analysis and reproducibility.

## Main Files

- `flare_hek_peaks_data.csv`  
  Full set of matched NOAA SEP events and HEK flare peaks across Solar Cycle 24 (2010–2020+).

- `noaa_flare_peaks_2010_and_above.csv`  
  Extracted NOAA flare events with corresponding peak timing and GOES metadata, used for initial HEK queries.

## Subdirectory: `flare_selection/`

This folder contains only the finalized flare event candidates used to download image cutouts. These flares passed all selection filters (timing, data completeness, instrument coverage) and were used for both FITS and ASDF dataset construction.

Files inside:
- `flare_hek_peaks_data_2014.csv`  
  Subset focused on the year 2014 (solar maximum), filtered for modeling and ASDF conversion.

- `strongest_flares_2014_SDO_AIA_summary.csv`  
  Final top flare events selected from 2014 based on peak intensity and AIA image availability.

