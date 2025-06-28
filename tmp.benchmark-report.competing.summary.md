| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --max-depth=1 tmp.sample` | 87.0 ± 0.4 | 86.5 | 88.6 | 1.00 |
| `dutree --summary tmp.sample` | 388.6 ± 1.7 | 386.9 | 392.1 | 4.46 ± 0.03 |
| `dua --count-hard-links tmp.sample` | 251.6 ± 11.5 | 234.4 | 274.6 | 2.89 ± 0.13 |
| `du --count-links --summarize tmp.sample` | 199.9 ± 1.5 | 197.6 | 203.6 | 2.30 ± 0.02 |
