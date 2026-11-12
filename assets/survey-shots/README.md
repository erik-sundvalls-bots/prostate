# Images from other prostate-map projects

`report.html` shows four illustrations from the 2026-11-12 survey of other
open-source prostate schematics. They are kept few on purpose. Only the
Tesseract-MI SVGs in `../tesseract-svgs/` are under that repository’s MIT
license. None of the files in this folder are covered by this repository’s
Apache License 2.0.

ACR licenses PI-RADS under CC BY-NC-ND 4.0, as quoted at
https://radiopaedia.org/cases/prostate-sector-map-pi-rads-v21. The survey
notes that several repositories embed the ACR sector-map figure, and that
derivatives of that figure are not freely reusable. That caveat applies to the
adambisa and Slicer images below.

“No license” means the survey found no LICENSE file and no GitHub license, so
all rights reserved by default.

## adambisa_rakathon_sector-map.jpg

- Project: https://github.com/adambisa/rakathon-2026 (ProstaPaper, Rakathon 2026 Brno)
- File copied from the repository: `packages/extraction/templates/sector-map.jpg`
  (https://github.com/adambisa/rakathon-2026/blob/HEAD/packages/extraction/templates/sector-map.jpg)
- Survey rank 1. Drawing: 2D React SVG, vector paths traced from the PI-RADS figure. Scheme: v2.1, 38 prostate sectors plus sv L/R (and urethra). License: none. Last commit noted: 2026-10-21.
- The survey’s evidence filename is `shots/adambisa_rakathon_sector-map.jpg`. This file is the sector-map image stored in that repository.

## SlicerPIRADS_prostate_sector_map.png

- Project: https://github.com/SlicerProstate/SlicerPIRADS
- File copied from the repository: `SlicerPIRADS/Resources/Images/prostate_sector_map.png`
  (https://github.com/SlicerProstate/SlicerPIRADS/blob/master/SlicerPIRADS/Resources/Images/prostate_sector_map.png)
- Survey rank 4. Drawing: 2D Qt dialog using this PNG plus 39 checkable buttons. Scheme: PI-RADS v2, 39 sectors, no base PZpm. License: BSD-3-Clause. Last commit noted: 2020-05-12 (not in the Slicer ExtensionsIndex).
- The survey’s evidence filename is `shots/SlicerPIRADS_prostate_sector_map.png`.

## hwangsi_PIRADSreport.png

- Project: https://github.com/hwangsi/PIRADSreport
- Screenshot taken 2026-11-12 of `prostate_pirads_tool.html` from that repository (https://github.com/hwangsi/PIRADSreport/blob/master/prostate_pirads_tool.html), with no lesion added.
- Survey rank 2. The notes say the evidence shot is the form only, and that the map appears after adding a lesion. Scheme: v2.1, 38 prostate sectors. License: MIT. Last commit noted: 2026-07-12.

## teedr_prostate-visualization.png

- Project: https://github.com/teedr/prostate-visualization
- Live page: https://prostate-visualization.vercel.app/
- Screenshot taken 2026-11-12 of that live page.
- Survey rank 10. Drawing: 2D grid plus a 3D three.js schematic. Scheme: biopsy 12-core (lateral/medial × base/mid/apex), not PI-RADS. License: none. Last commit noted: 2026-08-21.
