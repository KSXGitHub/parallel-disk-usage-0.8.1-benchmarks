| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --progress tmp.sample` | 206.5 ± 0.4 | 205.4 | 206.9 | 1.04 ± 0.02 |
| `ncdu -o /dev/stdout -1 tmp.sample` | 198.6 ± 0.7 | 197.9 | 200.4 | 1.00 ± 0.02 |
| `gdu --show-apparent-size --non-interactive tmp.sample` | 197.7 ± 3.5 | 193.0 | 204.0 | 1.00 |
