# Informe: Detección inicial de evasión — TelecomX
Generado: 2025-08-11T18:38:32.881519 UTC

## Resumen ejecutivo
- Total clientes analizados: **7267**
- Clientes marcados como sospechosos: **302** (4.16%)

## Archivos generados
- total_customers: 7267
- n_suspects: 302
- suspect_pct: 0.04155772670978396
- full_csv: /content/sample_data/telecomx_full_transformed.csv
- suspects_csv: /content/sample_data/suspect_customers.csv
- hist_png: /content/sample_data/hist_ratio_total_expected.png
- scatter_html: /content/sample_data/scatter_tenure_vs_gap.html
- bar_html: /content/sample_data/bar_suspects_by_payment_method.html
- pm_summary_csv: /content/sample_data/payment_method_suspects_summary.csv

## Top 20 sospechosos por gap
| customer_id   |   tenure |   monthly_charge |   total_charge |   expected_total |   diff_expected_minus_total | payment_method            | suspicion_reasons          |
|:--------------|---------:|-----------------:|---------------:|-----------------:|----------------------------:|:--------------------------|:---------------------------|
| 3963-RYFNS    |       72 |           116.45 |        8013.55 |          8384.4  |                      370.85 | bank transfer (automatic) | gap >2 months (gap=370.85) |
| 0266-CLZKZ    |       67 |           105.65 |        6717.9  |          7078.55 |                      360.65 | bank transfer (automatic) | gap >2 months (gap=360.65) |
| 4612-THJBS    |       56 |           104.75 |        5510.65 |          5866    |                      355.35 | bank transfer (automatic) | gap >2 months (gap=355.35) |
| 0895-DQHEW    |       54 |           104.3  |        5278.15 |          5632.2  |                      354.05 | electronic check          | gap >2 months (gap=354.05) |
| 3258-SYSWS    |       72 |           113.8  |        7845.8  |          8193.6  |                      347.8  | bank transfer (automatic) | gap >2 months (gap=347.80) |
| 7176-WRTNX    |       70 |           114.95 |        7711.25 |          8046.5  |                      335.25 | bank transfer (automatic) | gap >2 months (gap=335.25) |
| 4342-HFXWS    |       48 |            69.7  |        3023.65 |          3345.6  |                      321.95 | bank transfer (automatic) | gap >2 months (gap=321.95) |
| 2235-EZAIK    |       72 |            79.2  |        5401.9  |          5702.4  |                      300.5  | credit card (automatic)   | gap >2 months (gap=300.50) |
| 9558-IHEZX    |       71 |           106.75 |        7283.25 |          7579.25 |                      296    | credit card (automatic)   | gap >2 months (gap=296.00) |
| 0254-FNMCI    |       72 |           109.9  |        7624.2  |          7912.8  |                      288.6  | electronic check          | gap >2 months (gap=288.60) |
| 0201-MIBOL    |       66 |           102.4  |        6471.85 |          6758.4  |                      286.55 | bank transfer (automatic) | gap >2 months (gap=286.55) |
| 2957-JIRMN    |       62 |            84.45 |        4959.15 |          5235.9  |                      276.75 | electronic check          | gap >2 months (gap=276.75) |
| 6048-UWKAL    |       69 |           105.4  |        6998.95 |          7272.6  |                      273.65 | credit card (automatic)   | gap >2 months (gap=273.65) |
| 1555-DJEQW    |       70 |           114.2  |        7723.9  |          7994    |                      270.1  | bank transfer (automatic) | gap >2 months (gap=270.10) |
| 4753-PADAS    |       67 |           105.7  |        6816.95 |          7081.9  |                      264.95 | bank transfer (automatic) | gap >2 months (gap=264.95) |
| 4060-BTPXO    |       67 |           105.7  |        6816.95 |          7081.9  |                      264.95 | bank transfer (automatic) | gap >2 months (gap=264.95) |
| 6173-GOLSU    |       67 |            94.65 |        6079    |          6341.55 |                      262.55 | credit card (automatic)   | gap >2 months (gap=262.55) |
| 3413-DHLPB    |       60 |           103.75 |        5969.95 |          6225    |                      255.05 | bank transfer (automatic) | gap >2 months (gap=255.05) |
| 7113-HIPFI    |       66 |            65.85 |        4097.05 |          4346.1  |                      249.05 | mailed check              | gap >2 months (gap=249.05) |
| 3612-YUNGG    |       64 |           109.2  |        6741.15 |          6988.8  |                      247.65 | credit card (automatic)   | gap >2 months (gap=247.65) |