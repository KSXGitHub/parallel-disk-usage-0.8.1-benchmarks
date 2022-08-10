| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --min-ratio=0 tmp.sample` | 603.6 ± 2.2 | 600.3 | 607.3 | 3.23 ± 0.02 |
| `dutree tmp.sample` | 3480.6 ± 5.8 | 3473.2 | 3492.5 | 18.61 ± 0.08 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 198.2 ± 0.9 | 197.0 | 200.2 | 1.06 ± 0.01 |
| `du --apparent-size tmp.sample` | 187.0 ± 0.7 | 186.0 | 189.0 | 1.00 |
