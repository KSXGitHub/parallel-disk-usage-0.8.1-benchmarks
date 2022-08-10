| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --quantity=blksize tmp.sample` | 114.2 ± 0.7 | 113.3 | 116.5 | 1.00 |
| `dust tmp.sample` | 148.6 ± 2.3 | 146.3 | 156.9 | 1.30 ± 0.02 |
| `dua tmp.sample` | 248.0 ± 13.2 | 228.4 | 269.8 | 2.17 ± 0.12 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 192.5 ± 0.6 | 192.0 | 194.2 | 1.69 ± 0.01 |
| `gdu --non-interactive --no-progress tmp.sample` | 186.3 ± 2.6 | 182.0 | 191.0 | 1.63 ± 0.02 |
| `du tmp.sample` | 183.5 ± 0.4 | 182.9 | 184.5 | 1.61 ± 0.01 |
