| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --quantity=blksize tmp.sample` | 118.9 ± 2.0 | 116.1 | 125.3 | 1.00 |
| `dust tmp.sample` | 152.8 ± 2.1 | 149.8 | 157.3 | 1.29 ± 0.03 |
| `dua tmp.sample` | 264.5 ± 15.0 | 242.6 | 294.6 | 2.23 ± 0.13 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 198.4 ± 0.4 | 197.6 | 199.0 | 1.67 ± 0.03 |
| `gdu --non-interactive --no-progress tmp.sample` | 198.8 ± 2.8 | 193.7 | 204.1 | 1.67 ± 0.04 |
| `du tmp.sample` | 187.5 ± 0.7 | 186.5 | 189.3 | 1.58 ± 0.03 |
