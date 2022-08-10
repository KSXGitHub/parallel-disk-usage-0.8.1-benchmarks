| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort tmp.sample` | 112.5 ± 0.5 | 111.7 | 114.1 | 1.00 |
| `du --apparent-size tmp.sample` | 182.8 ± 0.4 | 182.2 | 183.6 | 1.62 ± 0.01 |
| `dua --apparent-size tmp.sample` | 225.8 ± 10.3 | 211.0 | 241.5 | 2.01 ± 0.09 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 191.9 ± 0.3 | 191.3 | 192.6 | 1.71 ± 0.01 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 184.4 ± 1.9 | 181.4 | 187.2 | 1.64 ± 0.02 |
