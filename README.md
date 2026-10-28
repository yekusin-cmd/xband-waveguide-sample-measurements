# X-band WR-90 waveguide S-parameter measurements

Measurement data of the article: Y. E. Kuşin, A. Ç. Yapıcı, M. Palandöken,
"Thickness-Aware Machine-Learning Extraction of the Permittivity of 3-D-Printed
Dielectrics in the X-Band Using a Rectangular Waveguide", Measurement Science
and Technology, 2026.

Ten Keysight FieldFox N9918A CSV exports (S11 and S21, real/imaginary parts,
201 points) recorded on a WR-90 sample holder after TRL calibration at the
waveguide flanges. Files are unmodified instrument exports; only the names
were changed to the sample names used in the article.

Naming: S1 / S2 = measurement session (26 July 2026, sweep 6.555-13.11 GHz /
7 August 2026, sweep 8.2-12.4 GHz), one TRL calibration and one empty-holder
file per session; d = caliper thickness; printA / printB = the two Zetamix 4.5
prints; run1-run3 = three independent disassembly/reassembly mountings of the
RT/duroid 5870 sample.

| File | Sample (article) | d (mm) |
|---|---|---|
| S1_empty_holder.csv | empty holder, session 1 | - |
| S1_RO3003_d3.048mm.csv | RO3003 (two stacked 1.524 mm laminates) | 3.048 |
| S1_Zetamix4.5_printA_d3.22mm.csv | Zetamix 4.5, print A | 3.22 |
| S1_Zetamix7.5_d2.90mm.csv | Zetamix 7.5 | 2.90 |
| S2_empty_holder.csv | empty holder, session 2 | - |
| S2_RTduroid5870_d3.18mm_run1.csv | RT/duroid 5870, mounting 1 (Table 4) | 3.18 |
| S2_RTduroid5870_d3.18mm_run2.csv | RT/duroid 5870, mounting 2 | 3.18 |
| S2_RTduroid5870_d3.18mm_run3.csv | RT/duroid 5870, mounting 3 | 3.18 |
| S2_Zetamix2.2_d3.50mm.csv | Zetamix 2.2 | 3.50 |
| S2_Zetamix4.5_printB_d3.35mm.csv | Zetamix 4.5, print B | 3.35 |

The extraction uses the normalized transmission n21(f) = S21,sample / S21,empty
with the empty-holder file of the same session (equation (1) of the article).
Table 4 of the article uses run 1 of RT/duroid 5870; the value 2.449 +/- 0.010
in Section 5.2.2 is the mean of runs 1-3.
