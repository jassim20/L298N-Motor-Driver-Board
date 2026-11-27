# Manufacturing Outputs

Designer-supplied v1.1.0 archives: [Gerber ZIP](Gerber.zip), [NC Drill ZIP](NC%20Drill.zip), and [combined fabrication ZIP](L298N-Fabrication.zip). The separate archives match the exports generated on 27 November 2026 at 5:25 PM. The combined archive was repackaged from the same exported files.

## Layer map

| Extension | Function |
| --- | --- |
| GTL / GBL | Top / bottom copper |
| GTS / GBS | Top / bottom solder mask |
| GTO / GBO | Top / bottom overlay |
| GTP / GBP | Top / bottom paste |
| GM | Board profile |
| TXT | NC drill data |

The original reports and auxiliary files are retained. The NC drill report lists 55 plated round holes using 1.000, 1.016, 1.200, 1.270 and 2.000 mm tools. The archive contains the Gerber and NC Drill directories.

The original revision was fabricated and functionally tested according to the designer. The updated revision has not been independently tested. A DRC run following the ECO reported zero violations; a repeat DRC on the final saved revision, independent DFM approval and a manufacturer-specific stackup are not documented. Verify the Gerber and drill files before production. See the repository LICENSE for copyright and usage terms.
