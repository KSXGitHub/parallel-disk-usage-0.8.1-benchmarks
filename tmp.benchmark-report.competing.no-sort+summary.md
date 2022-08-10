| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --no-sort --max-depth=1 tmp.sample` | 118.0 ± 1.8 | 115.6 | 122.8 | 1.00 |
| `dua --apparent-size tmp.sample` | 243.0 ± 11.8 | 226.2 | 262.1 | 2.06 ± 0.10 |
| `ncdu -o /dev/null -0 tmp.sample` | 197.0 ± 0.6 | 196.2 | 198.2 | 1.67 ± 0.03 |
| `gdu --show-apparent-size --non-interactive --no-progress tmp.sample` | 201.3 ± 9.9 | 191.6 | 223.2 | 1.71 ± 0.09 |
| `du --apparent-size --summarize tmp.sample` | 182.0 ± 0.6 | 181.1 | 183.2 | 1.54 ± 0.02 |
