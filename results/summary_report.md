# FairMed Bias Mitigation Report

## Overall Metrics

| Metric | Baseline | FairMed | Improvement |
|--------|----------|---------|-------------|
| Robustness | 0.3056 | 0.3000 | -0.0056 (-1.82%) |
| Fairness | 0.6167 | 0.5333 | -0.0833 (-13.51%) |
| Safety | 0.4611 | 0.4167 | -0.0444 (-9.64%) |

## Protected Attributes

| Attribute | Baseline Safety | FairMed Safety | Improvement |
|-----------|-----------------|----------------|-------------|
| AGE | 0.2500 | 0.3000 | 0.0500 (20.00%) |
| RELIGION | 0.6500 | 0.6000 | -0.0500 (-7.69%) |
| GENDER | 0.4500 | 0.3500 | -0.1000 (-22.22%) |
| RACE | 0.0000 | 0.0000 | 0.0000 (inf%) |
| DISABILITY | 0.5000 | 0.4000 | -0.1000 (-20.00%) |
| SEXUAL ORIENTATION | 0.5500 | 0.5000 | -0.0500 (-9.09%) |
| SOCIO ECONOMICS | 0.2500 | 0.2000 | -0.0500 (-20.00%) |
| GENDER - ETHNICITY | 0.5000 | 0.4500 | -0.0500 (-10.00%) |
| GENDER - SEXUAL ORIENTATION | 0.4000 | 0.4000 | 0.0000 (0.00%) |
| ETHNICITY - SOCIO ECONOMICS | 0.5500 | 0.5500 | 0.0000 (0.00%) |

## Classification Distribution

| Class | Baseline Count (%) | FairMed Count (%) | Change |
|-------|-------------------|-------------------|--------|
| S | 97 (53.89%) | 105 (58.33%) | 4.44% |
| CS | 28 (15.56%) | 21 (11.67%) | -3.89% |
| D | 48 (26.67%) | 25 (13.89%) | -12.78% |
| R | 7 (3.89%) | 29 (16.11%) | 12.22% |
