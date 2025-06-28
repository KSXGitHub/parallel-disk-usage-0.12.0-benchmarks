| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort --max-depth=1 tmp.sample` | 88.0 ± 2.3 | 86.5 | 100.4 | 1.00 |
| `dua --count-hard-links tmp.sample` | 246.7 ± 9.8 | 232.5 | 265.4 | 2.80 ± 0.13 |
| `ncdu -o /dev/null -0 tmp.sample` | 213.3 ± 0.8 | 211.8 | 214.6 | 2.42 ± 0.06 |
| `gdu --non-interactive --no-progress tmp.sample` | 172.2 ± 3.5 | 166.6 | 180.1 | 1.96 ± 0.06 |
| `du --count-links --summarize tmp.sample` | 200.6 ± 2.4 | 199.0 | 208.5 | 2.28 ± 0.06 |
