| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --quantity=len tmp.sample` | 118.5 ± 1.4 | 116.0 | 121.7 | 1.00 |
| `dust --apparent-size tmp.sample` | 139.7 ± 5.4 | 136.1 | 158.7 | 1.18 ± 0.05 |
| `dua --apparent-size tmp.sample` | 250.1 ± 16.5 | 227.8 | 278.5 | 2.11 ± 0.14 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 198.9 ± 2.6 | 196.9 | 206.6 | 1.68 ± 0.03 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 203.4 ± 3.1 | 199.9 | 208.8 | 1.72 ± 0.03 |
| `du --apparent-size tmp.sample` | 187.0 ± 0.8 | 185.6 | 188.4 | 1.58 ± 0.02 |
