| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --progress tmp.sample` | 204.6 ± 0.4 | 204.2 | 205.2 | 1.11 ± 0.01 |
| `ncdu -o /dev/stdout -1 tmp.sample` | 191.7 ± 0.6 | 190.9 | 192.8 | 1.04 ± 0.01 |
| `gdu --show-apparent-size --non-interactive tmp.sample` | 184.7 ± 2.4 | 181.3 | 189.1 | 1.00 |
