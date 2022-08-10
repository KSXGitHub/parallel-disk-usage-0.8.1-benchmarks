| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort --max-depth=1 tmp.sample` | 112.3 ± 1.7 | 111.0 | 120.0 | 1.00 |
| `dua --apparent-size tmp.sample` | 235.0 ± 16.3 | 214.1 | 264.8 | 2.09 ± 0.15 |
| `ncdu -o /dev/null -0 tmp.sample` | 192.0 ± 0.3 | 191.5 | 192.5 | 1.71 ± 0.03 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 184.7 ± 2.8 | 181.3 | 189.7 | 1.64 ± 0.03 |
| `du --apparent-size --summarize tmp.sample` | 179.0 ± 0.7 | 178.2 | 180.2 | 1.59 ± 0.02 |
