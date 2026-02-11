
# Imagesensing-in-GEE

GENERATING IMAGES SUCH AS :-
1.TRUE COLOR IMAGES

2.RAW NDVI WITH CLOUD

3.SENTINEL1 VV

4.SENTINEL1 VH

5.CLOUD MASKED NDVI

6.RECONSTRUCTED NDVI USING SAR

SOFTWARE/-
A collection of scripts and assets for image sensing and analysis using Google Earth Engine (GEE). This repository provides example workflows, helper scripts, and documentation for working with satellite imagery in GEE.

## Contents
- `scripts/` — Example Earth Engine scripts (JavaScript and Python) for common image processing tasks
- `data/` — Small sample datasets, masks, and ancillary files used by the examples
- `notebooks/` — Jupyter notebooks demonstrating usage and visualization workflows
- `docs/` — Additional documentation and guides

## Requirements
- A Google Earth Engine account (https://earthengine.google.com/)
- Earth Engine CLI (`earthengine`) for exporting and running some scripts (optional)
- Python 3.8+ (if using Python scripts)
- Optional: Node.js (for running JavaScript examples locally with the Earth Engine API)

## Quick start
1. Clone the repository:

   ```bash
   git clone https://github.com/phimatrix/Imagesensing-in-GEE.git
   cd Imagesensing-in-GEE
2. Authenticate with Earth Engine (if using the CLI or API):
3. earthengine authenticate
4. Open an example script in scripts/ or notebooks/ and follow the comments to run processing tasks.

after finding the different images we will find the raw data of NDVI and reconstructed fused NDVI data from fusion.py
