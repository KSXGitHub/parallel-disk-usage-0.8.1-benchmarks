| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --quantity=len tmp.sample` | 113.6 ± 0.6 | 112.6 | 115.4 | 1.00 |
| `dust --apparent-size tmp.sample` | 134.8 ± 2.8 | 132.6 | 145.9 | 1.19 ± 0.03 |
| `dua --apparent-size tmp.sample` | 240.4 ± 14.4 | 217.8 | 265.8 | 2.12 ± 0.13 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 193.6 ± 0.7 | 193.0 | 195.5 | 1.70 ± 0.01 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 190.3 ± 2.7 | 187.7 | 196.5 | 1.67 ± 0.03 |
| `du --apparent-size tmp.sample` | 184.8 ± 0.3 | 184.2 | 185.4 | 1.63 ± 0.01 |
