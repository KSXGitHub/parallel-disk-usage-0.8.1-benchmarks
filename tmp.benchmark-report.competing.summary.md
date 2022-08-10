| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `pdu --max-depth=1 tmp.sample` | 116.7 ± 6.9 | 111.9 | 146.8 | 1.00 |
| `dutree --summary tmp.sample` | 306.3 ± 0.4 | 305.5 | 306.8 | 2.63 ± 0.16 |
| `dua --apparent-size tmp.sample` | 230.9 ± 10.7 | 216.4 | 250.5 | 1.98 ± 0.15 |
| `du --apparent-size --summarize tmp.sample` | 179.8 ± 0.3 | 179.2 | 180.3 | 1.54 ± 0.09 |
