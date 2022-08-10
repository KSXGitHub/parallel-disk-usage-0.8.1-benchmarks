| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --max-depth=1 tmp.sample` | 117.9 ± 1.4 | 115.3 | 121.4 | 1.00 |
| `dutree --summary tmp.sample` | 303.0 ± 2.9 | 301.4 | 310.8 | 2.57 ± 0.04 |
| `dua --apparent-size tmp.sample` | 239.0 ± 12.8 | 224.5 | 261.9 | 2.03 ± 0.11 |
| `du --apparent-size --summarize tmp.sample` | 181.7 ± 0.5 | 180.8 | 182.7 | 1.54 ± 0.02 |
