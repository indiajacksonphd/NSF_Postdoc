## 📓 Jupyter Notebooks

These notebooks document the full FITS-to-ASDF solar data processing pipeline developed during the NSF AGS-PRF fellowship. Each step is modular and reproducible.

- **`1_NOAA_Current_SEP_List.ipynb`**  
  Scrapes the NOAA Solar Energetic Particle (SEP) Event List and saves key information including flare max times for future analysis.

- **`2_NOAA_HEK_Flare_Summary_Pipeline.ipynb`**  
  Queries the Heliophysics Event Knowledgebase (HEK) for each SEP flare, extracting start/end times and metadata.

- **`3_Flare_Selection_Extraction.ipynb`**  
  Focuses on 2014 solar maximum; filters and selects the most intense flares from five high-activity dates.

- **`4_JSOC_Web_Extraction_Save.ipynb`**  
  Interfaces with the JSOC API to request and download full-resolution FITS images for selected flare intervals.

- **`5_FITS_ASDF_Metadata_Pipeline.ipynb`**  
  Combines FITS data, HEK metadata, and label information into ASDF files for streamlined ML ingestion.
