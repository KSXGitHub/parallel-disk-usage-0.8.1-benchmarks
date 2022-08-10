| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort tmp.sample` | 118.5 ± 2.1 | 116.1 | 124.8 | 1.00 |
| `du --apparent-size tmp.sample` | 186.4 ± 0.8 | 185.3 | 188.3 | 1.57 ± 0.03 |
| `dua --apparent-size tmp.sample` | 244.8 ± 7.3 | 231.4 | 251.9 | 2.07 ± 0.07 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 197.2 ± 0.6 | 196.3 | 198.2 | 1.66 ± 0.03 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 198.4 ± 5.2 | 192.0 | 210.7 | 1.67 ± 0.05 |
