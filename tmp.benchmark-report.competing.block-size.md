| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --quantity=block-size tmp.sample` | 90.7 ± 0.6 | 89.8 | 92.6 | 1.00 |
| `dust tmp.sample` | 115.6 ± 4.5 | 112.4 | 136.8 | 1.28 ± 0.05 |
| `dua --count-hard-links tmp.sample` | 251.1 ± 8.0 | 242.1 | 271.8 | 2.77 ± 0.09 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 213.7 ± 1.3 | 211.6 | 216.0 | 2.36 ± 0.02 |
| `gdu --non-interactive --no-progress tmp.sample` | 172.7 ± 3.0 | 168.0 | 177.6 | 1.90 ± 0.04 |
| `du --count-links tmp.sample` | 202.9 ± 1.1 | 201.4 | 204.9 | 2.24 ± 0.02 |
