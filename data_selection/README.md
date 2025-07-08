# Data Selection Directory

This folder contains preprocessed label files and supporting metadata used during the solar flare data curation and selection process.

## Contents

- `image_labels.csv` — Labeled image records used in classification (flare vs. non-flare), including time-aligned metadata.
- `image_labels.txt` — Text version of the labeled image list, used for quick human-readable review.
- `sampling_logs/` — Logs of the random sampling process for flare vs. non-flare image balance.
- `all_downloadable_files/` — Clean markdown files containing clickable URLs for all hosted FITS, HEK, PNG, and ASDF files stored on AWS S3.
