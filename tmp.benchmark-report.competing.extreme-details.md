| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --min-ratio=0 tmp.sample` | 603.7 ± 1.9 | 600.8 | 605.8 | 3.30 ± 0.01 |
| `dutree tmp.sample` | 3739.3 ± 7.2 | 3731.9 | 3751.7 | 20.43 ± 0.08 |
| `ncdu -o /dev/stdout -0 tmp.sample` | 191.5 ± 0.5 | 190.6 | 192.4 | 1.05 ± 0.00 |
| `du --apparent-size tmp.sample` | 183.0 ± 0.6 | 182.0 | 184.0 | 1.00 |
