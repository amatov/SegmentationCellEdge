## Segmention Cell Edge

The Matlab code I wrote to segment cellular outline.

## Quick start

This repository implements cell-outline segmentation by pixel
intensity thresholding and active contours in Matlab. See
[DEPENDENCIES.md](DEPENDENCIES.md) for the Image Processing Toolbox
requirement.

## Repository contents

- `segmentOutline.m` -- the main function; computes the cellular
  outline via thresholding and active contours.
- `cutFirstHistMode.m` -- implements Rosin's unimodal thresholding
  algorithm (see LICENSE).
- `histogram.m`, `arbitraryGrid.m`, `countEntries.m`, `normList.m`,
  `perpVector.m` -- supporting utilities.
- `reports/` -- the Rosin (2001) reference paper.
- **License:** see [LICENSE](LICENSE) -- research/educational use.

## About

The code computes the extent of the cellular outline, which improved the accuracy of the segmentation from 45%, of the existing approach, to 95%, by pixel intensity thresholding and active contour for the publication:

Emma Spanjaard, Ihor Smal, Nicos Angelopoulos, Ingrid Verlaan, Alex Matov, Erik Meijering, Lodewyk Wessels, Hans Bos, Johan de Rooij "Quantitative Imaging of Focal Adhesion Dynamics and their Regulation by HGF and Rap1 Signaling" (2014).

For detailed information, see: https://www.researchgate.net/publication/388842022_Quantitative_Cell_Division_and_Migration_in_Medicine
